# ملفات جزء Git وGitHub

- رابط المستودع: https://github.com/sameer-8o/ldcw6123-youtube-python
- رابط سجل عمليات الرفع إلى GitHub: https://github.com/sameer-8o/ldcw6123-youtube-python/commits/main/
- `Git_Development_History.md`: نص باللغة الإنجليزية جاهز لإضافته إلى التقرير.
- `git-log.txt`: الناتج الحقيقي للأمر `git log --oneline --graph`.
- `git-log-detailed.txt`: تفاصيل التواريخ والملفات التي تغيرت في كل commit.
- `youtube-recommendation-assistant-with-git.zip`: نسخة كاملة تتضمن الكود والتوثيق والاختبارات ومجلد `.git` الذي يحفظ التاريخ.
- `youtube-recommendation-assistant.bundle`: نسخة احتياطية مستقلة لسجل Git.

## للتقرير

أضف نص `Git_Development_History.md` وسجل Git إلى قسم التطوير. المستودع أصبح عامًا؛ يمكن للمحاضر فتح الروابط دون دعوة.

بدأ السجل من الكود الذي أرسلته جاهزًا. توجد 4 commits محلية فعلية للاستيراد والتوثيق والتحقق وتوضيح طريقة التسليم؛ وهي لا تثبت مراحل برمجة سابقة لم يكن لها سجل Git متاح.

سجل الموقع يعرض عمليات الرفع عبر المتصفح. سجل التطوير المحلي المرفق محفوظ في ملفات النص وداخل ZIP وGit bundle؛ أرقام commits المحلية تختلف عن commits الرفع إلى الموقع.

## تشغيل الاختبارات

من مجلد المستودع بعد فك الضغط:

```bash
python -m unittest discover -s tests -v
```

النتيجة المسجلة: 10 اختبارات ناجحة، واختبار واحد بفشل متوقع يوثق مشكلة موجودة عند إدخال الرمز `²`. كود البرنامج محفوظ كما أرسلته تمامًا.

## استعادة المستودع من النسخة الاحتياطية

```bash
git clone youtube-recommendation-assistant.bundle restored-project
```

هذا يحفظ الـcommits. إذا رغبت لاحقًا في ربط النسخة المستعادة بمستودع GitHub، غيّر رابط origin إلى رابط المستودع.

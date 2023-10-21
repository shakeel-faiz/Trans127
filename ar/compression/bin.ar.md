{
   "date":"2023-07-20",
   "keywords":[
      "BIN",
      "BIN File",
      "file",
      "BIN file extension",
      "extension",
      "file"
   ],
   "author":{
      "display_name":"Shakeel Faiz"
   },
   "draft":"false",
   "toc":true,
   "title":"تنسيق ملف BIN - ملف MacBinary المشفر",
   "description":"تعرف على تنسيق BIN وواجهات برمجة التطبيقات التي يمكنها إنشاء ملفات BIN وفتحها.",
   "linktitle":"BIN",
   "menu":{
      "docs":{
         "identifier":"compression-bin",
         "parent":"compression"
      }
   },
   "lastmod":"2023-07-20"
}

## ما هو ملف BIN؟

يمكن أن يشير ملف BIN، في سياق أجهزة كمبيوتر Macintosh، إلى ملف محفوظ بتنسيق MacBinary. MacBinary هو تنسيق ملف مصمم خصيصًا لنقل ملفات Macintosh عبر الإنترنت أو البريد الإلكتروني أو FTP أو الوسائط المحمولة. الغرض من MacBinary هو الحفاظ على بنية الملف الكاملة وسمات ملفات Macintosh، بما في ذلك تفرع البيانات وتفرع الموارد، داخل ملف واحد.

يحقق تنسيق MacBinary ذلك عن طريق تغليف تفرع موارد نظام الملفات الهرمي Macintosh (HFS) وتفرع البيانات في ملف مضغوط. ويتضمن أيضًا رأس مكتشف يحتوي على بيانات تعريف مهمة حول الملف. من خلال الجمع بين كل هذه المكونات في ملف واحد، يضمن MacBinary أن الملف يحتفظ بسلامته ويمكن نقله ومشاركته بسهولة عبر منصات مختلفة.

مع التقدم في أنظمة ملفات Apple وبروتوكولات نقل الملفات، أصبح استخدام ملفات BIN وتنسيق MacBinary أقل شيوعًا. أدى إدخال تنسيقات الملفات مثل ZIP والانتقال إلى أنظمة الملفات الأكثر حداثة، مثل HFS+ وAPFS، إلى تقليل الحاجة إلى الملفات المشفرة بنظام MacBinary. توفر أنظمة الملفات الأحدث هذه طرقًا أكثر كفاءة للتعامل مع سمات الملفات، وتفرعات الموارد، وتفرعات البيانات، مما يجعل تنسيق MacBinary أقل أهمية في مشهد الحوسبة اليوم.

## تنسيق ملف BIN - مزيد من المعلومات

في الأيام الأولى لأجهزة كمبيوتر ماكنتوش، تم تخزين الملفات في قسمين منفصلين بسبب قيود البيانات. يحتوي "تفرع الموارد" على بيانات منظمة، بينما يحتوي "تفرع البيانات" على بيانات غير منظمة. بينما تعامل نظام التشغيل Mac OS الكلاسيكي مع هذه التشعبات كملف واحد، فإن نقل الملفات إلى أنظمة غير تابعة لنظام التشغيل Mac أدى إلى فقدان البيانات لأنها لم تتعرف على التشعبات ككيان واحد. ولمعالجة هذه المشكلة، تم إنشاء تنسيق MacBinary بواسطة أفراد مثل Dennis Brothers وHarry Chesley وYves Lempereur. قام MacBinary بضغط ودمج التفرعات في ملف واحد، يُعرف باسم ملف BIN، لنقلها إلى أنظمة غير تابعة لنظام Mac. عند العودة إلى نظام التشغيل Mac OS، سيتم فصل الشوكات مرة أخرى. مع التحول بعيدًا عن نظام HFS القائم على الشوكة في العقد الأول من القرن الحادي والعشرين، انخفض استخدام تنسيق MacBinary بشكل ملحوظ. اليوم، من النادر العثور على ملف BIN مشفر بواسطة MacBinary إلا إذا صادفت ملفًا قديمًا على نظام غير Mac أو قمت بتنزيله من الإنترنت.

لقد مر تنسيق MacBinary بالعديد من الإصدارات بمرور الوقت لاستيعاب التغييرات في أنظمة Macintosh ومعالجة الملفات. فيما يلي بعض الإصدارات المختلفة لتنسيق MacBinary:

- **MacBinary I:** الإصدار الأولي من MacBinary، الذي تم تقديمه في أواخر الثمانينات. لقد قام بدمج تفرع الموارد وتفرع البيانات في ملف ثنائي واحد، مما يسمح بنقل ملفات ماكنتوش عبر الأنظمة الأساسية.

- **MacBinary II:** تم إصدار هذا الإصدار في أوائل التسعينيات، وقد تم تحسينه على تنسيق MacBinary الأصلي عن طريق إضافة معلومات إضافية، مثل نوع الملف وأكواد المنشئ، إلى رأس الملف الثنائي. ساعدت هذه الرموز في الحفاظ على سلامة ملفات Macintosh وتحديد هويتها أثناء النقل.

- **MacBinary III:** أدى تنسيق MacBinary III، الذي تم تقديمه في منتصف التسعينيات، إلى تحسين الإصدارات السابقة من خلال تضمين بيانات تعريف إضافية، مثل اسم الملف وتواريخ إنشاء الملف وتعديله، في رأس الملف الثنائي. وقد سمح ذلك بحفظ أكثر شمولاً لسمات ملف Macintosh أثناء النقل.

- **MacBinary IV:** تم تطوير MacBinary IV لمعالجة مشكلات التوافق مع نظام التشغيل Mac OS X الناشئ في أوائل العقد الأول من القرن الحادي والعشرين. لقد أدرج تغييرات للتكيف مع بنية نظام الملفات الجديد والسمات المقدمة في نظام التشغيل Mac OS X.

## كيفية فتح ملف BIN؟

يمكن فتح ملفات MacBinary Encoded BIN باستخدام أدوات ضغط متنوعة. بالنسبة لمستخدمي macOS، تعد **Apple Archive Utility** خيارًا مناسبًا. يمكن لمستخدمي Windows استخدام برامج مثل **Smith Micro StuffIt Deluxe** لاستخراج محتويات ملف MacBinary Encoded BIN. هناك خيار آخر لمستخدمي macOS وهو **The Unarchiver**، وهي أداة متعددة الاستخدامات قادرة على التعامل مع تنسيقات ملفات متعددة، بما في ذلك MacBinary.

من المهم ملاحظة أن امتداد الملف .bin يتم استخدامه بواسطة تنسيقات ملفات مختلفة، وليس فقط MacBinary. لذلك، إذا واجهت ملف BIN لا يمكن فتحه باستخدام الأدوات المساعدة المذكورة أعلاه، فقد يتم حفظه بتنسيق مختلف. في مثل هذه الحالات، قد تحتاج إلى تحديد تنسيق الملف المحدد واستخدام البرنامج أو الأداة المساعدة المناسبة المصممة لهذا التنسيق للوصول إلى محتويات الملف.

## ملفات BIN الأخرى

فيما يلي أنواع الملفات الأخرى التي تستخدم امتداد الملف **.bin**.

- [BIN - Binary Disc Image File](/disc-and-media/bin/)
- [BIN - Unix Executable File](/executable/bin/)
- [BIN - BlackBerry IT Policy File](/settings/bin/)
- [BIN - Sega Genesis Game ROM](/game/bin/)
- [BIN - PSX PlayStation BIOS Image](/game/bin-pcsx/)

## مراجع

* [MacBinary](https://en.wikipedia.org/wiki/MacBinary)
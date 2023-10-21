{
  "date": "2023-09-27",
  "keywords": [
    "cfg",
    "cfg file",
    "cfg m.u.g.e.n configuration file",
    "what is a cfg file",
    "how to open cfg file",
    "file",
    "cfg file extension",
    "extension"
  ],
  "author": {
    "display_name": "Shakeel Faiz"
  },
  "draft": "false",
  "toc": true,
  "title": "CFG File Format - M.U.G.E.N Configuration File",
  "description": "تعرف على تنسيق ملف التكوين CFG M.U.G.E.N وواجهات برمجة التطبيقات التي يمكنها إنشاء ملفات CFG وفتحها.",
  "linktitle": "CFG M.U.G.E.N",
  "menu": {
    "docs": {
      "identifier": "game-cfg-mugen",
      "parent": "game"
    }
  },
  "lastmod": "2023-09-27"
}

## ما هو ملف CFG؟

يشير ملف CFG في سياق M.U.G.E.N إلى "ملف تكوين M.U.G.E.N." **M.U.G.E.N** هو محرك ألعاب قتال ثنائي الأبعاد قابل للتخصيص تم تطويره بواسطة Elecbyte. يمكن للمستخدمين إنشاء شخصياتهم ومراحلهم وحتى تعديل سلوك اللعبة وقواعدها عن طريق تحرير ملفات التكوين المختلفة، بما في ذلك ملفات CFG.

فيما يلي نظرة عامة أساسية على ما قد تجده في ملف M.U.G.E.N `.cfg`:

1. **تكوين النظام**: غالبًا ما تحتوي ملفات CFG على إعدادات تتعلق بالسلوك العام لمحرك اللعبة. يتضمن ذلك أشياء مثل دقة الشاشة وإعدادات الصوت وتكوين الإدخال (لوحة المفاتيح أو عصا التحكم أو تعيينات وحدة التحكم).
    
2. **الإعدادات الافتراضية للشخصيات والمراحل**: يمكنك تحديد الإعدادات الافتراضية للشخصيات والمراحل. على سبيل المثال، يمكنك تحديد الشخصيات والمراحل التي سيتم تحميلها عند بدء اللعبة.
    
3. **خيارات اللعب**: يمكن لملفات M.U.G.E.N `.cfg` أيضًا التحكم في خيارات اللعب المختلفة مثل الحدود الزمنية الدائرية، وحجم الضرر، والمزيد.
    
4. **التصحيح والتطوير**: قد يستخدم المستخدمون المتقدمون ملفات `.cfg` لأغراض التصحيح والتطوير. يمكن لهذه الإعدادات التحكم في كيفية عرض معلومات تصحيح الأخطاء على الشاشة أو تحديد السلوكيات الأخرى المتعلقة بالتطوير.
    
5. **تكوين حزمة الشاشة**: حزم الشاشة هي سمات مرئية تغير شكل اللعبة ومظهرها. يمكن لملفات `.cfg` تحديد حزمة الشاشة المستخدمة وتكوين عناصرها المتنوعة.
    
6. **سلوك الذكاء الاصطناعي**: يتيح لك M.U.G.E.N تحديد كيفية تصرف الشخصيات التي يتحكم فيها الكمبيوتر (AI) في المعارك. يمكن أن تحتوي ملفات `.cfg` على إعدادات تتعلق بصعوبة الذكاء الاصطناعي وسلوكه.

## M.U.G.E.N Configuration File 

يعد ملف M.U.G.E.N CFG (التكوين) عنصرًا حاسمًا للمبدعين في عالم ألعاب القتال المخصصة. إنها تمكنهم من تشكيل القواعد الأساسية للعبتهم. يتضمن ذلك عوامل مثل المدة التي تستغرقها كل جولة، ومستوى التحدي الذي يقدمه الخصوم الذين يتحكم فيهم الكمبيوتر، ووتيرة اللعبة، ومدى تأثير المجموعات على الضرر، وأكثر من ذلك بكثير.

علاوة على ذلك، يسمح ملف CFG للمبدعين بتحديد إعدادات عرض اللعبة، مثل دقة الشاشة، وتحديد ما إذا كان يجب على M.U.G.E.N تشغيل المؤثرات الصوتية والموسيقى أثناء اللعب. بالنسبة لأولئك الذين هم على دراية جيدة بتعقيدات M.U.G.E.N، يوفر هذا الملف إمكانية تعديل مجموعة من الإعدادات الأخرى المتعلقة باللعبة لصياغة تجربة لعب فريدة من نوعها.

افتراضيًا، يوجد ملف CFG الأساسي لـ M.U.G.E.N، والمعروف باسم "mugen.cfg"، في مجلد بيانات البرنامج. في حين أنه من الممكن تحرير إعدادات اللعبة مباشرة داخل هذا الملف، فمن المستحسن بشكل عام إنشاء نسخة احتياطية أولاً. ويضمن هذا الاحتياط إمكانية إعادة M.U.G.E.N إلى إعداداته الأصلية بسهولة إذا لزم الأمر، مما يمنع أي تغييرات غير مقصودة من تعطيل تجربة اللعب الخاصة بك.

## M.U.G.E.N - Game Engine

M.U.G.E.N هو محرك ألعاب قتال ثنائي الأبعاد متعدد الاستخدامات وقابل للتخصيص بدرجة كبيرة تم تطويره بواسطة Elecbyte. يرمز الاسم "M.U.G.E.N" إلى "Mugen Ultimate Game Engine". تم إصداره لأول مرة في عام 1999 واكتسب منذ ذلك الحين مجتمعًا مخصصًا من المستخدمين والمبدعين الذين يستخدمون المحرك لتصميم وتطوير ألعاب القتال ثنائية الأبعاد الخاصة بهم.

فيما يلي بعض الميزات والجوانب الرئيسية لـ M.U.G.E.N:

1. **شخصيات قابلة للتخصيص:** يتيح M.U.G.E.N للمستخدمين إنشاء واستيراد شخصياتهم الخاصة (المعروفة باسم "المقاتلين" أو "العفاريت") إلى اللعبة. يمكن للمبدعين تصميم مجموعات حركات ورسوم متحركة وهجمات خاصة فريدة لهذه الشخصيات، مما يجعل من الممكن تضمين أي شخصية تقريبًا من مختلف الامتيازات أو الإبداعات الأصلية.
    
2. **المراحل:** بالإضافة إلى الشخصيات، يمكن للمستخدمين أيضًا إنشاء وتخصيص المراحل التي تدور فيها المعارك. يمكن أن تحتوي هذه المراحل على عناصر تفاعلية وخلفيات فريدة.
      
3. **حزم الشاشة:** حزم الشاشة هي سمات مرئية تعمل على تغيير المظهر العام للعبة، بما في ذلك القوائم وشاشات اختيار الشخصيات وأشرطة الحياة. يمكن للمستخدمين إنشاء ومشاركة حزم الشاشة الخاصة بهم لإضفاء مظهر ومظهر فريد على ألعابهم.
    
4. **الصوت والموسيقى:** يستطيع منشئو المحتوى إضافة مؤثرات صوتية وموسيقى خلفية إلى ألعابهم، مما يعزز تجربة الألعاب بشكل عام.
    
5. **البرمجة:** يمكن للمستخدمين المتقدمين استخدام لغة البرمجة النصية المضمنة لإنشاء سلوكيات شخصية معقدة وآليات لعب فريدة وتأثيرات خاصة.

## كيفية فتح ملف CFG؟

ملفات M.U.G.E.N CFG هي مستندات نصية عادية، مما يجعلها قابلة للوصول باستخدام العديد من برامج تحرير النصوص. على نظام التشغيل Windows، يمكنك استخدام Microsoft Notepad أو WordPad، بينما يمكن لمستخدمي macOS استخدام Apple TextEdit لهذا الغرض. تتيح برامج التحرير هذه للمستخدمين عرض وتعديل إعدادات التكوين داخل ملفات CFG بسهولة.

البرامج التي تفتح ملفات CFG أو تشير إليها

- Elecbyte M.U.G.E.N
- Notepad
- TextEdit

## ملفات CFG أخرى

فيما يلي أنواع الملفات الأخرى التي تستخدم امتداد الملف **.cfg**.

**Settings**
- [CFG - Celestia Configuration File](/settings/cfg-celestia/)
- [CFG - Citrix Server Connection File](/settings/cfg-citrix/)
- [CFG - MAME Configuration File](/settings/cfg-mame/)
- [CFG - LightWave Configuration File](/settings/cfg-lightwave/)

**Game**
- [CFG - Wesnoth Markup Language File](/game/cfg-wesnoth/)
- [CFG - M.U.G.E.N Configuration File](/game/cfg-mugen/)
- [CFG - Source Engine Configuration File](/game/cfg-sourceengine/)

**System & Misc**
- [CFG - CFG File](/system/cfg/)
- [CFG - Cal3D Model Configuration File](/misc/cfg-cal3d/)

## مراجع
* [Mugen (game engine)](https://en.wikipedia.org/wiki/Mugen_(game_engine))
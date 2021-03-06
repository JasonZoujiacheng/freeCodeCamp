---
title: Wiki Git Aliases
localeTitle: Wiki Git Aliases
---
بالنسبة لمعظم المطورين ، يتم إنفاق الكثير من وقتنا في Terminal ويتم صرف معظمه كتابة أوامر Git. لقد أنشأنا مجموعة من اختصارات لوحة المفاتيح مع الأسماء المستعارة Bash والوظائف لتسريع سير العمل الخاص بك وحفظ مئات من ضغطات المفاتيح كل يوم.

تسمح لك Git بتعيين الأسماء المستعارة ولكنها محدودة ولا توفر لك سوى عدد قليل من ضغطات المفاتيح (أي بدلاً من git checkout يمكنك كتابة git co ، ولكن لا يزال عليك كتابة git). نظرًا لأن مترجم سطر الأوامر الافتراضي في Bash هو Terminal ، فيمكنك أيضًا تعيين الأسماء المستعارة لـ Bash لتقليل ضغطات المفاتيح بشكل أكبر.

وهنا لائحة من الأسماء المستعارة جيت باش ووظائفها. لاستخدامها بنفسك ، قم فقط بإضافتها إلى الملف الذي تقوم بتخزين الأسماء المستعارة / الدوال فيه. (على `~/.bash_profile` أو `~/.bashrc` )

عند النسخ واللصق ، من المهم الحفاظ على التباعد. (أي للأسماء المستعارة ، يجب عدم وجود مسافات قبل وبعد علامات متساوية ، وبالنسبة للوظائف ، يجب أن يكون هناك مسافة بعد قوس التجويف الافتتاحي للإعلان وفاصلة منقوطة بعد الأمر. لا تنس إعادة تحميل الملف الخاص بك ( source `~/.bash_profile` ) أو `~/.bash_profile` تشغيل المحطة الطرفية بعد إجراء التغييرات.
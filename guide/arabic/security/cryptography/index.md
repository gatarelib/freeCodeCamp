---
title: Cryptography
localeTitle: التشفير
---
## التشفير

الهدف الأساسي من التشفير هو تمكين شخصين من التواصل عبر القناة غير الآمنة بطريقة لا يستطيع شخص ثالث فهم ما يقال. يمكن أن تكون هذه القناة خط هاتف أو شبكة كمبيوتر.

بدأ استخدام التشفير من قبل الرومان من أجل جعل الرسائل في المعركة غير قابل للقراءة من قبل العدو إذا تم التخلص منها.

كان التشفير قبل العصر الحديث مرادفا فعليا للتشفير ، وتحويل المعلومات من حالة مقروءة إلى هراء واضح.

يُستخدم التشفير الحديث في البيانات بحيث يكون هناك طرف واحد فقط أو طرف معتمد فقط لديه القدرة على الوصول إلى المعلومات.

أصبح التشفير على مر السنين أكثر تقدما.

### مثال

المعلومات التي يريد الشخص الواحد إرسالها إلى Person2 ، والتي نسميها "نص عادي" ، يمكن أن تكون نصًا ، أو بيانات رقمية ، أو أي نوع من البيانات على الإطلاق. يقوم Person1 بتشفير النص العادي ، باستخدام مفتاح محدد مسبقًا ، وإرسال "النص المشفر" الناتج عبر القناة. لا يمكن لـ Person3 ، عند رؤية النص المشفر في القناة ، تحديد ما هو النص العادي ، ولكن الشخص 2 ، الذي يعرف مفتاح التشفير ، يمكنه فك تشفير النص المشفر وإعادة بناء النص العادي.

### قيصر سايفر (شيفت سايفر)

وكان أول سايفر معروف هو سايفر قيصر. ceasar cypher يعمل عن طريق تحويل الحروف من "نص عادي" بمقدار معين لأعلى أو لأسفل في الأبجدية.

من منظور الشخص الخارجي ، تظهر الرسالة على أنها أحرف عشوائية بمسافات بينهما.

### التشفير الحديث

يستخدم التشفير الحديث أرقامًا عشوائية تقريبًا ووظائف صوتية رياضية من أجل السماح بالاتصال الآمن. لا يمكن اختراق هذه المسارات التي تم تطويرها حديثًا بسهولة بسبب هيكلها ، مما يتطلب حتى أجهزة الكمبيوتر العملاقة حتى تصل إلى مئات السنين.

هناك نوعان رئيسيان من التشفير الحديث:

### 1) تشفير المفتاح المتماثل أو المفرد:

تشفير المفتاح المتماثل هو طريقة تشفير حيث يستخدم كلا الطرفين مفتاح واحد فقط للتشفير وفك التشفير. هذه الخوارزميات ، بسبب تصميمها ، بشكل عام أسرع بكثير من تشفير المفتاح العام أو غير المتماثل.

تتضمن بعض تقنيات التشفير المتماثلة: معيار تشفير البيانات (DES) ، معيار التشفير المتقدم (AES) ، Blow Fish ، وسمكتان ، RC4.

### 2) غير متماثل أو مفتاح التشفير العام:

توفر خوارزميات التشفير غير المتماثلة لكل مستخدم مفتاحين: أحدهما عام والآخر خاص. أي رسالة مشفرة بمفتاح واحد من الزوج لا يمكن فك تشفيرها إلا مع الأخرى.

بعض التقنيات غير المتماثلة تشمل: RSA ، Diffie-Hellman ، DSS (Digital Signature Standard) ، ElGamal.

### تجزئة التشفير

تم تصميم معظم وظائف هاش التجفير لاتخاذ سلسلة من أي طول كمدخل وإنتاج قيمة تجزئة بطول ثابت.

يجب أن تكون وظيفة تجزئة التشفير قادرة على تحمل جميع الأنواع المعروفة من هجوم cryptanalytic.

### تجزئة التشفير

دالة هاش التشفير هي نوع من وظيفة البعثرة المصممة لتكون وظيفة أحادية الاتجاه (دالة تستهلك الكثير من الوقت والموارد من أجل إجهاض القوة). الغرض الرئيسي من التجزئة يتعامل مع intregrity الرسالة ، لذلك نفس الرسالة تؤدي دائما إلى التجزئة نفسها.

#### معلومات اكثر:

*   [تشفير: النظرية والتطبيق من قبل دوجلاس ستينسون](https://www.crcpress.com/Cryptography-Theory-and-Practice-Third-Edition/Stinson/p/book/9781584885085)
*   [TechTarget على التشفير](http://searchsecurity.techtarget.com/definition/encryption)
*   [دليل تشفير](https://www.tutorialspoint.com/cryptography/index.htm)
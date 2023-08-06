
# مقدمة في Bootstrap

اذا سبق و قمت بتطوير صفحات ويب ف لابد أن تنسيق الواجهات بإستخدام html و CSS مألوف عليك. تساعد html و CSS في تشكيل هيكل الصفحة وتنسيق عناصرها مثل الجداول، النصوص، النماذج والأزرار وغيرها من عناصر الصفحة. الآن حان الوقت لتتعلم Bootstrap والذي قد يختصر عليك الكثير من الوقت في تنسيق الصفحات دون الحاجة لبدء تنسيق العنصر من الصفر. بدايةً Bootstrap هي عبارة عن مكتبة مكتوبة بـ html , css و javascript لتصميم الواجهات في صفحات الويب. من اهم خصائص Bootstrap هي السرعه بالتنفيذ لأنها ستختصر عليك الكثير من الأسطر من خلال استخدام `class` واحد مكتوب من قِبل Bootstrap، يدعم أي متصفح مثل قوقل كروم فاير فوكس وغيرها.
بحيث التطوير في Bootstrap يكون بشكل اسرع لأنه يوفر Classes للتنسيق مكتوبه ومجهزه مسبقاً. سواء كان لتنسيق العناصر (مثل الجداول، النصوص، النماذج والأزرار وغيرها) أو حتى تنسيق موقعك كاملاً من خلال استخدام Templates جاهزه توفرها Bootstrap. بالاضافه الى انه يعتبر Responsive والتي تعني ان محتوى الصفحه يتماشى مع أي حجم شاشه ينعرض فيها (مثل: PC, smart phone).

حتى نتمكن من البدء في استخدام Bootstrap نحتاج اولاً الى انشاء مجلد جديد للمشروع. مثلاً بإسم `MyProject`, بداخل هذا المجلد سأقوم بإنشاء ملف بإسم `main.html` حتى نتمكن من اضافة Bootstrap classes بداخلة. شكل مجلدك يجب أن يكون كالتالي:

![](https://paper-attachments.dropbox.com/s_1AC9903E3EEBB6063308875CE65038B1C37D7FA861422AA32C76E1CF02534AF4_1627469371200_image.png)


سنقوم الآن بزيارة [موقع Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/) والنزول حتى جزئية `Start template` 


![](https://paper-attachments.dropbox.com/s_1AC9903E3EEBB6063308875CE65038B1C37D7FA861422AA32C76E1CF02534AF4_1627469693465_image.png)



قم بنسخ هذا الكود ولصقه في ملف `main.html` 


    <!doctype html>
    <html lang="en">
      <head>
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
    
        <!-- Bootstrap CSS -->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    
        <title>Hello, world!</title>
      </head>
      <body>
        <h1>Hello, world!</h1>
    
        <!-- Optional JavaScript; choose one of the two! -->
    
        <!-- Option 1: Bootstrap Bundle with Popper -->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    
        <!-- Option 2: Separate Popper and Bootstrap JS -->
        <!--
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
        -->
      </body>
    </html>

سأقوم بحذف أجزاء `comments`  حتى يصبح شكل الملف كالتالي:


    <!doctype html>
    <html lang="en">
      <head>
    
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
    
        <!-- Bootstrap CSS -->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    
        <title>Hello, world!</title>
      </head>
      <body>
        <h1>Hello, world!</h1>
        
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    
      </body>
    </html>

الآن أنت جاهز لإستخدام `Bootstrap Classes` .


## بعض الأمثلة لطريقة استخدام Bootstrap Classes

**١. الألوان Colors**
يدعم Bootstrap مجموعة من الألوان نستطيع استخدامها بشكل مباشر عن طريق كتابة الإسم في الـclass الخاص بالوسم لدينا 



## ألوان النص 

نلاحظ في المثال التالي مجموعة من الألوان التي يوفرها إيطار عمل Bootstrap للنصوص ونستطيع استخدامها عن طريق كتابة text وبعدها إسم اللون داخل الـclass الخاص بالوسم لاحظ المثال التالي: 


    <p class="text-primary">.text-primary</p>
    <p class="text-secondary">.text-secondary</p>
    <p class="text-success">.text-success</p>
    <p class="text-danger">.text-danger</p>
    <p class="text-warning">.text-warning</p>
    <p class="text-info">.text-info</p>
    <p class="text-light bg-dark">.text-light</p>
    <p class="text-dark">.text-dark</p>
    <p class="text-body">.text-body</p>
    <p class="text-muted">.text-muted</p>
    <p class="text-white bg-dark">.text-white</p>
    <p class="text-black-50">.text-black-50</p>
    <p class="text-white-50 bg-dark">.text-white-50</p>

المخرجات:


![](https://paper-attachments.dropbox.com/s_BC46414885B5059F98922AA5B83E0A18642B25017B37BB52600E37C8B5AE6D8A_1601278078097_Screen+Shot+1442-02-11+at+10.27.35+AM.png)


فمثلًا لو أردنا اللون الأخضر الذي يدل على النجاح فإننا نكتب في الـclass الخاص بالوسم text-success كما هو موضح بالمثال أعلاه.

## ألوان الخلفية

نستطيع أيضًا استخدام الألوان التي يوفرها إيطار عمل Bootstrap كلون خلفية عن طريق كتابة bg وبعدها إسم اللون في الـclass الخاص بالوسم كما بالمثال التالي: 


    <div class="p-3 mb-2 bg-primary text-white">.bg-primary</div>
    <div class="p-3 mb-2 bg-secondary text-white">.bg-secondary</div>
    <div class="p-3 mb-2 bg-success text-white">.bg-success</div>
    <div class="p-3 mb-2 bg-danger text-white">.bg-danger</div>
    <div class="p-3 mb-2 bg-warning text-dark">.bg-warning</div>
    <div class="p-3 mb-2 bg-info text-white">.bg-info</div>
    <div class="p-3 mb-2 bg-light text-dark">.bg-light</div>
    <div class="p-3 mb-2 bg-dark text-white">.bg-dark</div>
    <div class="p-3 mb-2 bg-white text-dark">.bg-white</div>
    <div class="p-3 mb-2 bg-transparent text-dark">.bg-transparent</div>

المخرجات:


![](https://paper-attachments.dropbox.com/s_BC46414885B5059F98922AA5B83E0A18642B25017B37BB52600E37C8B5AE6D8A_1601278311263_Screen+Shot+1442-02-11+at+10.31.34+AM.png)


٢. **الجداول Tables**
نظرًا للاستخدام الواسع للجداول فقد طورت Bootstrap جداول قابلة للإستخدام والتنسيق حسب حاجة المستخدم لذا فقط نحتاج إضافة table في عنصر class إلى الوسم <table> ثم نستطيع إستخدام عدة خيارات لتعديل التنسيق عن طريق إضافتها في عنصر class . 

نلاحظ بالمثال التالي التنسيق الأساسي للجداول باستخدام الـ Bootstrap: 


    <table class="table">
     <thead>
          <tr>
              <th scope="col">#</th>
              <th scope="col">الإسم</th>
              <th scope="col">البريد الإلكتروني</th>
              <th scope="col">العمر</th>
          </tr>
      </thead>
       <tbody>
           <tr>
              <th scope="row">1</th>
              <td>عبدالله محمد</td>
              <td>abdullah@test.com</td>
              <td>24</td>
          </tr>
           <tr>
              <th scope="row">2</th>
              <td>سارة سلطان</td>
              <td>sarah@test.com</td>
              <td>27</td>
           </tr>
            <tr>
                <th scope="row">3</th>
                <td>أحمد سالم</td>
                <td>ahmad@test.com</td>
                <td>20</td>
              </tr>
            </tbody>
          </table>

المخرجات: 

![](https://paper-attachments.dropbox.com/s_AD072EFB10947C39E36BD5109722E884D6791A86D0A1BFFC1EEA2D79F5B5E7A9_1600683449033_Screen+Shot+1442-02-04+at+1.17.06+PM.png)



ولجعل الجدول بلون داكن dark mood نقوم باستخدام table-dark في الـ class الخاص بوسم `<table>` كما بالمثال التالي:


    <table class="table table-dark">
     <thead>
          <tr>
              <th scope="col">#</th>
              <th scope="col">الإسم</th>
              <th scope="col">البريد الإلكتروني</th>
              <th scope="col">العمر</th>
          </tr>
      </thead>
       <tbody>
           <tr>
              <th scope="row">1</th>
              <td>عبدالله محمد</td>
              <td>abdullah@test.com</td>
              <td>24</td>
          </tr>
           <tr>
              <th scope="row">2</th>
              <td>سارة سلطان</td>
              <td>sarah@test.com</td>
              <td>27</td>
           </tr>
            <tr>
                <th scope="row">3</th>
                <td>أحمد سالم</td>
                <td>ahmad@test.com</td>
                <td>20</td>
              </tr>
            </tbody>
          </table>
    

المخرجات:

![](https://paper-attachments.dropbox.com/s_AD072EFB10947C39E36BD5109722E884D6791A86D0A1BFFC1EEA2D79F5B5E7A9_1600697503047_Screen+Shot+1442-02-04+at+5.11.25+PM.png)


يمكن أيضًا جعل رأس الجدول بلون فاتح أو داكن عن طريق تغيير class الـوسم `<thaed>` إما thead-light للون الفاتح أو thead-dark للون الداكن كما بالمثال التالي: 


     <table class="table">
            <thead class="thead-light">
              <tr>
                ......
              </tr>
            </thead>
            <tbody>
              <tr>
               ......
              </tr>
            </tbody>
          </table>
    


    
     <table class="table">
            <thead class="thead-dark">
              <tr>
                ......
              </tr>
            </thead>
            <tbody>
              <tr>
               ......
              </tr>
            </tbody>
          </table>

المخرجات: 


![](https://paper-attachments.dropbox.com/s_AD072EFB10947C39E36BD5109722E884D6791A86D0A1BFFC1EEA2D79F5B5E7A9_1600760666452_Screen+Shot+1442-02-05+at+10.43.53+AM.png)

![](https://paper-attachments.dropbox.com/s_AD072EFB10947C39E36BD5109722E884D6791A86D0A1BFFC1EEA2D79F5B5E7A9_1600760773082_Screen+Shot+1442-02-05+at+10.45.58+AM.png)



لجعل الجدول بشكل مخطط الصفوف نستخدم table-striped داخل class في الوسم `<table>` كما بالمثال التالي:


      <table class="table table-striped">
            <thead>
              <tr>
                ...
              </tr>
            </thead>
            <tbody>
              <tr>
              ...
              </tr>
            </tbody>
          </table>

المخرجات: 

![](https://paper-attachments.dropbox.com/s_AD072EFB10947C39E36BD5109722E884D6791A86D0A1BFFC1EEA2D79F5B5E7A9_1600761459013_Screen+Shot+1442-02-05+at+10.57.28+AM.png)


**٣.الشارات Badges**

سنتعرف على كيفية استخدام الأصناف المُعرَّفة مسبقًا في إطار العمل Bootstrap لإضافة علامات مميزة أو عدَّاد صغير أو شارات على عناصر في الصفحة.


## مثال

تتمدَّد الشارات `badge‎`  لتوافق قياس العنصُر الأب المباشر وذلك باستخدام وحدات القيّاس `em`. لاحظ المثال التالي:


    <h1>مثال  <span class="badge badge-secondary">جديد</span></h1>
    <h2>مثال <span class="badge badge-secondary">جديد</span></h2>
    <h3>مثال <span class="badge badge-secondary">جديد</span></h3>
    <h4>مثال <span class="badge badge-secondary">جديد</span></h4>
    <h5>مثال <span class="badge badge-secondary">جديد</span></h5>
    <h6>مثال <span class="badge badge-secondary">جديد</span></h6>

المخرجات:

![](https://paper-attachments.dropbox.com/s_5A0B8F26B7362B3E86DE8894CBF37323F9456FF9540E8FE00F320B087BB4A5BD_1601281773496_Screen+Shot+1442-02-11+at+11.29.11+AM.png)


كما يمكن استخدام Badges كجزء من الروابط أو الأزرار لإنشاء عدّاد كما بالمثال التالي أضفنا badge badge-light في الـclass الخاص بـ `<``**span>**`  :


    <button type="button" class="btn btn-primary">
                                         الإشعارات <span class="badge badge-light">4</span>
    </button>

المخرجات:

![](https://paper-attachments.dropbox.com/s_5A0B8F26B7362B3E86DE8894CBF37323F9456FF9540E8FE00F320B087BB4A5BD_1601282054412_Screen+Shot+1442-02-11+at+11.34.02+AM.png)


قد تكون الشارات مربكة لمستخدمي برامج قراءة الشاشة والتقنيات المساعدة المماثلة. صحيح أنّ تنسيق الشارات يوفر إشارات بصرية تبيّن الغرض منها، لكن لن يحصل مستخدمو برامج قراءة الشاشة والتقنيات المساعدة إلا على محتوى الشارة . هذا قد يجعلها تبدوا ك عبارات من كلمات وأرقام عشوائية في نهاية الجملة أو الرابط أو الزر. ما لم يكن السياق واضحًا (كما هو الحال مع مثال "الإشعارات" ) ، يُفضَّل تضمين سياق إضافي مع الجزء المخفي.


    <button type="button" class="btn btn-primary">
      Profile <span class="badge badge-light">9</span>
      <span class="sr-only">رسائل غير مقروءة</span>
    </button>

المخرجات:


![](https://paper-attachments.dropbox.com/s_5A0B8F26B7362B3E86DE8894CBF37323F9456FF9540E8FE00F320B087BB4A5BD_1601282340247_Screen+Shot+1442-02-11+at+11.38.48+AM.png)

## شارات حسب السياق

يمكن تغيير مظهر Badges حسب السياق كما بالمثال التالي: 


    <span class="badge badge-primary">أوليّ</span>
    <span class="badge badge-secondary">ثانويّ</span>
    <span class="badge badge-success">نجاح</span>
    <span class="badge badge-danger">خطر</span>
    <span class="badge badge-warning">تحذير</span>
    <span class="badge badge-info">معلومة</span>
    <span class="badge badge-light">فاتح</span>
    <span class="badge badge-dark">داكن</span>

المخرجات:

![](https://paper-attachments.dropbox.com/s_5A0B8F26B7362B3E86DE8894CBF37323F9456FF9540E8FE00F320B087BB4A5BD_1601282442336_Screen+Shot+1442-02-11+at+11.40.32+AM.png)



## الشارات - rounded badges

يمكن استخدام الخاصية `badge-pill` في الـclass لجعل الشارة بشكل مدور كما بالمثال التالي: 


    <span class="badge badge-pill badge-primary">أوّلي</span>
    <span class="badge badge-pill badge-secondary">ثانويّ</span>
    <span class="badge badge-pill badge-success">نجاح</span>
    <span class="badge badge-pill badge-danger">خطر</span>
    <span class="badge badge-pill badge-warning">تحذير</span>
    <span class="badge badge-pill badge-info">معلومة</span>
    <span class="badge badge-pill badge-light">فاتح</span>
    <span class="badge badge-pill badge-dark">داكن</span>

المخرجات: 

![](https://paper-attachments.dropbox.com/s_5A0B8F26B7362B3E86DE8894CBF37323F9456FF9540E8FE00F320B087BB4A5BD_1601282577358_Screen+Shot+1442-02-11+at+11.42.28+AM.png)

## الروابط

يمكن استخدام الشارات داخل روابط `<a>`  لتوفير شارات يمكن النقر عليها كما بالمثال التالي:


    <a href="#" class="badge badge-primary">أوليّ</a>
    <a href="#" class="badge badge-secondary">ثانويّ</a>
    <a href="#" class="badge badge-success">نجاح</a>
    <a href="#" class="badge badge-danger">خطر</a>
    <a href="#" class="badge badge-warning">تحذير</a>
    <a href="#" class="badge badge-info">معلومة</a>
    <a href="#" class="badge badge-light">فاتح</a>
    <a href="#" class="badge badge-dark">داكن</a>

المخرجات:

![](https://paper-attachments.dropbox.com/s_5A0B8F26B7362B3E86DE8894CBF37323F9456FF9540E8FE00F320B087BB4A5BD_1601282770740_Screen+Shot+1442-02-11+at+11.45.27+AM.png)

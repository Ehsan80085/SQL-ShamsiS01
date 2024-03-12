<h1 dir="rtl">نام و نام خانوادگی: احسان موسی وند</h1>
<h2 dir="rtl">آزمایشگاه پایگاه داده 2</h2>
<h2 dir="rtl">استاد میثاق یاریان</h2>

<div dir="rtl">
  <h1 dir="rtl">موضوع: تفاوت‌های SQL و NoSQL</h1>
تفاوت‌های اصلی این دو مدل در چگونگی ساخت آن‌ها، نوع اطلاعاتی که ذخیره می‌کنند و چگونگی ذخیره کردن آن‌هاست.
<br>
1- 	SQL
<br>
این نوع بانک‌ها دارای ساختار و ارتباط بین موجودیت‌ها (Table ها) می‌باشند، به عنوان مثال، تصور کنید نیاز است تا اطلاعات یک سازمان که شامل، ساختار معاونت ها یا واحدهای زیرمجموعه، سمت‌های سازمانی، اطلاعات پرسنل و... هستند را ذخیره نماییم، طبیعاتا نیاز است تا برای مشخص نمودن سلسله مراتب سازمانی بین افراد یا ارتباط واحدها بامعاونت ها و... از این مدل استفاده شود، زیرا بین هر یک از این مفاهیم ارتباطی وجود دارد.
  <br>
مثال: پرسنلی که سمت ایشان "کارشناس جذب و استخدام" هست و در واحد منابع انسانی یک سازمان فعالیت دارد.
  <br>
در این مثال پرسنل می‌تواند یک یا چندین سمت داشته باشد و یا بالعکس، یک سمت می‌تواند به چندین پرسنل انتساب داده شود.
  <br>
پس برای پیاده سازی این مفهوم، نیاز داریم تا اطلاعات به صورت ساختار یافته باشند و ارتباطاتی بین آنها باشد پس طبیعاتا باید از مدل SQL استفاده نماییم.
  <br>
این مدل، می‌تواند باتوجه به نیاز، برای تمامی انواع داده استفاده شود.
  <br>
باتوجه به ساختاریافته بودن این مدل، نیاز است تا شِمای (Schema) دیتابیس از قبل تعریف شود و اطلاعات باتوجه به همین شِما وارد شوند، همچنین وقتیکه قصد خواند داده ها از این دیتابیس را داشته باشیم، با یک ساختار منظم و مشخص روبه رو هستیم. 
  <br>
2- 	NoSQL

این مدل با SQL کاملا متفاوت است، در NoSql ها خبری از جداول و رابطه ی بین آن ها نیست و تفاوت های بنیادی با پایگاه داده های SQL دارند.
<br>
به عنوان نقطه مقابل مدل قبلی، دیتابیس‌های NoSQL دارای ساختار مشخصی نبوده و بجای اینکه داده‌ها در جدول‌ها ذخیره شوند، در سندها ذخیره می‌شوند، مثال: برای ذخیره سازی پیوست‌ها مانند (تصاویر، مقالات، ویدیوها و موارد مختلف دیگر) در یک سند ذخیره کرد و به سادگی آن‌ها را پیدا نمود.
همچنین لازم به ذکر است که این مدل نیازند توان پردازشی بیشتری می‌باشد.
<br>
2-1- 	انواع مختلف
<br>
->	Key-Value
<br>
این متد با استفاده از یک کلید منحصر به فرد، یک مقدار را ذخیره می‌کند.
<br>
Cassandra، Azure، LevelDB و Riak نمونه‌هایی از این متد می‌باشند.
<br>
->	Column Store
<br>
این متد مشابه مدل ذخیره سازی SQL عمل می‌کند اما تفاوتی که دارد این است که هر ردیف از دیتا، نام و فرمت هر ستون می‌تواند متفاوت باشد.
<br>
->	Document
<br>
همان مدل Key-Value با پیچیدگی‌های بیشتر می‌باشد  و به صورت سند‌هایی از نوع json ذخیره می‌شوند.
<br>
MongoDB و CouchDB نمونه های این متد هستند.
<br>
->	Graph
<br>
با استفاده از این متد می‌توانید داده ها را به صورت گراف مشاهده/ویرایش نمایید، نمونه‌هایی از آن Polyglot و Neo4J است.
<br>
<br>
3- 	نتیجه
انتخاب مناسب بین SQL و NoSQL به شرایط خاص سناریوی پیاده سازی شما بستگی دارد، برخی از سناریو ها ممکن است حتی از ترکیبی از هر دو نوع پایگاه داده بهره ببرند تا به بهترین شکل نیازهای مختلف داده‌ای را برآورده کنند.





</div>

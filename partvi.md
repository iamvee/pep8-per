<h1 align=right>‫اصول نام‌گذاری:</h1>

<p align=right>‫سبک‌های نام‌‌گذاری مختلفی وجود داره. سبک‌های زیر جزء مرسوم‌ترین اونها هستن:</p>

<p align=right>‫* یک حرف کوچک (b)</p>

<p align=right>‫* یک حرف بزرگ (B)</p>

<p align=right>‫* حروف کوچک</p>

<p align=right>‫* حروف_کوچک_با_خط_زیر</p>

<p align=right>‫* حروف بزرگ</p>

<p align=right>‫* حروف_بزرگ_با_خط_زیر</p>

<p align=right>‫* کلمات با حرف اوّل بزرگ (CapWords) زمانیکه با سبک CapWords یک کلمه با اختصار رو می‌نویسید بهتره همه‌ی حروف کلمه‌ی اختصار رو به شکل بزرگ بنویسید. مثلاً HTTPServerError بهتر از HttpServerError هست.</p>

<p align=right>‫* MixedCase (با کاراکتر‌های اولیه‌ی کوچک با حالت CapitalizedWords متفاوت هست.)</p>

<p align=right>‫* کلمات_با_حروف_اوّل_بزرگ_به_همراه_خط_زیر.</p>

<p align=right>‫یه نوع استایل نام‌گذاری وجود داره به شکلی که نام‌ها با یک پیشوند دسته‌بندی می‌شن. درسته توی پایتون زیاد مرسوم نیست. برای مثال تابع ‪os.stat()‬ یک tuple برمی‌گردونه که اسامیشون به شکل زیر هستن: st_mode، st_size و امثال این‌ها.</p>

<p align=right>‫در کتابخانه‌ی X11 از کاراکتر X اوّل همه‌ی توابع عمومی استفاده می‌شود امّا در پایتون این استایل بیهوده هستِ چون نام خصوصیات و متد‌ها با پیشوند اسم شئ شروع می‌شه و اسم توابع با پیشوند اسم ماژول.</p>

<p align=right>‫علاوه بر این‌ها، فرم‌های خاص زیر از خط زیر در ابتدا و انتها استفاده می‌کنند که می‌توانند با سبک‌های نام گذاری قبلی بصورت ترکیبی مورد استفاده قرار گیرند:</p>

<p align=right>‫* ‌یک‌ـ‌خط‌زیر‌ـ‌درابتدا: XXXXXXXXXXXXXXXXXX. برای مثال دستور ‪from M import *‬ اشیائی که با خط زیر شروع می‌شن رو ایمپورت نمی‌کنه. این حالت به بقیه برنامه‌نویس‌ها می‌گه که این متد یا خصیصه پرایویت هست.</p>

<p align=right>‫* یک_خط‌زیر_درانتهاـ: برای جلوگیری از تعارض متغیر با keyword‌های پایتون:</p>

<pre><code>Tkinter.Toplevel(master, class_='ClassName')
</code></pre>

<p align=right>‫* __دوخط‌زیر_در ابتدا:XXXXXXXXXXXXX</p>

<p align=right>‫* __دوخط‌زیر_درابتدا_وانتها__: اشیاء و خصوصیات جادویی که در فضای نام کاربری موجود هستند. مانند __init__، __import__ یا __file__. هرگز از چنین اسامی استفاده نکنید، مگر برای استفاده در مستندسازی.</p>

<p align=center><a href="https://github.com/vahit/pep8-per/blob/master/partvii.md">بعدی</a> <a href="https://github.com/vahit/pep8-per/blob/master/partv.md">قبلی</a></p>
# OSLAB7
1.<br/>
در hard link<br/>
هر تغییری که بر روی Hard Link یا فایل اصلی انجام بدهید بر روی هر دو اعمال می شود<br/>
اگر فایل اصلی را تغییر بدید، هارد لینک تغییر نمی کند<br/>
در استفاده از آن نمی توان در بین چند فایل سیستم یا پارتیشن استفاده کرد<br/>
به دلیل اینکه ساختار inode ها متفاوت است و شماره گذاری ها متفاوت است Hard Link ها فقط در یک فایل سیستم قابل پیاده سازی هستند
ساختار Soft Link ها بسیار انعطاف پذیر است و شما از هر جایی می توانید به جای دیگر Soft Link بزنید و هیچگونه مشکلی در خصوص محل و فایل سیستم در Soft Link ها وجود ندارد<br/>
زمانی که اسم فایل اصلی تغییر بدیم soft link خراب می شود و دیگر نمی توان ا زآن استفاده کرد<br/>

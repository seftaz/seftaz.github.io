# seftaz.github.io

ابتدا برای ساختن این پروژه ما در گیتهاب یک organization ساخته و در ادامه یک مخزن با نام seftaz.github.io ساختیم که صفحه فرانت ما همین دامنه نیز باشد.

در ادامه در یک جدول Kanban ساختیم که در آن PO تسک ها و یوزر استوری های مورد نظرش را در backlog قرار میداد و در ادامه آن ها توسط دولوپر ها از شرایط ready به in progress رفته و بعد از رفتن به review و انجام تست ها و کد زده شده به مرحله done میرفتیم. در زیر تعدادی از مراحل این کار را میبینیم.

![kanban1](https://github.com/seftaz/seftaz.github.io/assets/79263953/82fd286a-ab78-4e6e-bdc5-5667eb1861db)
![kanban2](https://github.com/seftaz/seftaz.github.io/assets/79263953/355902f3-e2eb-4f84-a56d-babac51bc559)



در ابتدای کار نیز برای اینکه برنچ main ما مهم بود آن را به حالت پروتکتد درآوردیم. برای این کار هم ابتدا تسک به یک توسعه‌دهنده تخصیص داده شد و در کانبان هم قرار داده شد و در نهایت به حالت done در آمد. همچنین با توجه به نام ریپو، به طور خودکار بر روی seftaz.github.io دیپلوی شد که در تصاویر زیر کانبان را آپدیت کردیم.

![protect main](https://github.com/seftaz/seftaz.github.io/assets/79263953/7abe9b86-9955-466b-8107-94fefb5073f3)*محافظت از main*
![kanban3](https://github.com/seftaz/seftaz.github.io/assets/79263953/f5543080-e35d-49f6-99db-e4231b364331)
![kanban4](https://github.com/seftaz/seftaz.github.io/assets/79263953/ec7f56ee-aa51-4fb1-a0e2-cb8fd70043ba)


حال در ادامه برای ابتدا کلون کردن پروژه از git bash استفاده کردیم و در ادامه نیز برنچ dev را ساختیم و محتویات اصلی و اولیه سایت که صفحه index.html بود را توسعه دادیم.

![image_2024-03-08_19-26-55](https://github.com/seftaz/seftaz.github.io/assets/79263953/6470813c-fda8-4aa5-9edb-a93a1c704b64)*ورود به gitbash و ساخت دایرکتوری پروژه برای کلود کردن برنچ dev*

![image_2024-03-08_19-30-55](https://github.com/seftaz/seftaz.github.io/assets/79263953/c4663004-3eb7-4cc7-9042-423ca1b53056)*کلون کردن برنچ dev*

در ادامه پروژه را در داحل vscode بردیم و از این IDE برای کد زدن کمک گرفتیم.


![image_2024-03-08_19-33-36](https://github.com/seftaz/seftaz.github.io/assets/79263953/cedf848b-015b-4b9b-82ed-945d640de88c)*ورود به پروژه در vscode*


پس از آن فایل .gitignore را با توجه به IDE و زبان مورد استفاده درست کردیم. و آن را پوش کردیم

![image_2024-03-08_19-38-59](https://github.com/seftaz/seftaz.github.io/assets/79263953/20651e05-c3b6-4243-a7d8-0fb9ba08a142)*اضافه کردن فایل .gitignore*

![image_2024-03-08_19-39-14](https://github.com/seftaz/seftaz.github.io/assets/79263953/61164a3b-62fe-4c10-8513-ecafb61fa0a8)*فایل .gitignore*

![image_2024-03-08_20-00-29](https://github.com/seftaz/seftaz.github.io/assets/79263953/2dee922a-3e68-470c-ba99-8127521a7841)*تغییر وضعیت ساخت gitignore*

![image_2024-03-08_20-06-41](https://github.com/seftaz/seftaz.github.io/assets/79263953/480117f1-cbb0-4932-9ae7-f66ab2cab302)*پوش کردن کامیت جدید*



در ادامه ابتدا شروع به ساختن صفحه اصلی و اولیه پروژه کردیم تا یک front اولیه داشته باشیم. برای این کار از html و bootstrap استفاده کردیم.

![image_2024-03-08_20-12-46](https://github.com/seftaz/seftaz.github.io/assets/79263953/7b56a463-dabd-47c1-b1ba-b939ac2c7812)*شروع اضافه کردن صفحه‌ی اصلی*

![image_2024-03-08_20-13-13](https://github.com/seftaz/seftaz.github.io/assets/79263953/e1fb72bf-115e-4e02-b53f-f82c1746f0f3)*نوشتن کلیات header صفحه‌ی اصلی از یک کد آماده*

![image_2024-03-08_20-14-21](https://github.com/seftaz/seftaz.github.io/assets/79263953/26d8a355-402d-47f4-8d76-3fc84c964eed)*کامیت و پوش فایل index.html*

![image_2024-03-08_20-17-08](https://github.com/seftaz/seftaz.github.io/assets/79263953/fbf5f714-248b-4f61-ba88-a1c72e47eb90)*اضافه کردن فایل style.css از strat bootstrap*

![image_2024-03-08_20-19-01](https://github.com/seftaz/seftaz.github.io/assets/79263953/63cd0787-f439-4e74-9fda-75dd379c0bcf)*اضافه کردن فایل cssها (با وجود اینکه در gitignore هست، برای بار اول باید پوش بشود)*

![image_2024-03-08_20-34-11](https://github.com/seftaz/seftaz.github.io/assets/79263953/dfc0cd9b-3dc9-4faa-a05b-9f4df82e6c54)*اضافه کردن کدهای مورد نیاز bootstrap در index.html*

![image_2024-03-08_20-45-12](https://github.com/seftaz/seftaz.github.io/assets/79263953/451c1028-b906-4069-9e7a-764bae777f26)
![image_2024-03-08_20-45-12 (2)](https://github.com/seftaz/seftaz.github.io/assets/79263953/6a825c01-2e1e-4a39-8492-7da77702f701)*اضافه کردن بخش nav bar و پوش کردن*

![image_2024-03-08_20-56-24 (2)](https://github.com/seftaz/seftaz.github.io/assets/79263953/ff5f6657-27fd-48ff-80bf-59cacc053266)
![image_2024-03-08_20-56-24](https://github.com/seftaz/seftaz.github.io/assets/79263953/1f32f2d0-ad93-4628-82df-0abf3a96be74)*اضافه کردن body صفحه اصلی و مشاهده روی local*


قبل از بردن این تغییرات به روی main، ورکفلوهای مربوط به CI/CD را انجام میدهیم تا با هر تغییر به روی main، به طور خودکار CI/CD انجام شود. ابتدا ورکفلو مربوطه که یک basic structure هست از خود github workflows دریافت میکنیم و در برنچ ci-cd پوش میکنیم. سپس درخواست مرج با main ارسال میکنیم که توسط دولوپر دیگر بررسی و approve میشود.

![image_2024-03-08_21-43-20](https://github.com/seftaz/seftaz.github.io/assets/79263953/7333d34c-2cda-4ace-a098-8eedf8b3858c)*قبول کردن pull request برای مرج برنچ ci/cd*

حال درخواست pull request از برنچ dev را بررسی میکنیم. اینجا به طور کاملا اتفاقی و برنامه‌ریزی‌نشده، چون هردو برنچ از gitignore های مختلفی استفاده کردند به conflict میخوریم.

![conflict gitignore](https://github.com/seftaz/seftaz.github.io/assets/79263953/b9bf8319-97f8-4950-a33b-91d61d240349)*تداخل هنگام merge*

![resolve](https://github.com/seftaz/seftaz.github.io/assets/79263953/d56078fc-b92f-4e12-a77f-7db2017dca4f)*رفع تداخل با ترکیب دو فایل و کامیت کردن*

حال pull request را review میکنیم و کامنت میگذاریم. سپس تایید میشود و به روی main میرود.

![review](https://github.com/seftaz/seftaz.github.io/assets/79263953/75a9d0a3-5315-4f62-8d46-c572dd9fb93b)*انجام review*

حال صغحه اصلی سایت درست شد و در آدرس مدنظر deploy شد.

![image_2024-03-08_23-00-22](https://github.com/seftaz/seftaz.github.io/assets/79263953/ae0e9ebd-9841-4430-8257-50d801ca2fc7)*وضعیت فعلی سایت روی pages*


حال صفحه contact us را به عنوان یک فیچر جدید میخواهیم به این سایت اضافه کنیم. ابتدا یک برنچ feat/add-contact-us از روی main میسازیم و در فایل contact.html تغییرات مدنظر را اعمال میکنیم.


![feat](https://github.com/seftaz/seftaz.github.io/assets/79263953/2a7bfb2d-c497-4572-8bd3-ed01ac719dac)


پس از اعمال تغییرات موردنظر، پوش کرده و pull request ارسال میکنیم که توسط دولوپر دیگر تایید میشود.

![image_2024-03-08_22-37-32](https://github.com/seftaz/seftaz.github.io/assets/79263953/b0f4ff11-97d5-404e-a628-8bd2f06f05b7)
![image_2024-03-08_22-38-16](https://github.com/seftaz/seftaz.github.io/assets/79263953/c2ecc631-9077-4eb3-a00a-8d5cd89cad85)

حال یک تغییر در فایل index.html توسط توسعه‌دهنده اولیه روی برنچ dev ایجاد میشود تا لینک contact us را به صفحه اصلی اضافه کند. در این حین هنگام مرج کردن متوجه میشویم که در مرج قبلی یک غلط املایی وجود داشته که الان جلوی مرج را میگیرد.

![conflict](https://github.com/seftaz/seftaz.github.io/assets/79263953/676e3910-25eb-4bb4-89e4-bb33222656c5)
![typo](https://github.com/seftaz/seftaz.github.io/assets/79263953/d42825c2-df2e-479f-b4bf-4859a1dfcee7)

پس از resolve کردن این کانفلیکت، درخواست مرج اکسپت میشود و پروژه روی main مستقر میشود. حال سایت هم صفحه اصلی را دارد و هم فیچر contact us و روی github pages هم مستقر است.

![image](https://github.com/seftaz/seftaz.github.io/assets/79263953/ff8d57ba-6212-48c6-9c52-14f97f0d98e5)


<hr/>

## پاسخ سوالات

سوال 1) 

 در این پوشه تمامی اطلاعاتی که گیت نیاز دارد تا برای تغییرات مورد نظر را در کدبیس ما ببیند و آن ها را تشخیص دهد قرار دارد .در آن اطلاعاتی چون commit ها و کامنت‌های متناظر با ان همچنین branch و tag ها و نام و ایمیل نویسنده همچنین زمان تغیر در ان ذخیره می‌شود. برای ساختن این پوشه کافیست تا از دستور git init استفاده کنیم

 
سوال 2)

 منظور از atomic بودن کامیت این است که در هر کامیت تنها یک کار مجزا باید انجام شود. همچنین commit های مربوط به bugfix یا refactoring یا features باید از یکدگیر جدا شوند. باید از کامیت کردن تغییرات متعدد به صورت یکجا پرهیز گردد و هر کامیت باید تنها یک گام ما را به حالت مورد انتظار نزدیک کند. با توجه به اینکه هر کامیت ‌به‌معنی یک snapshot از پروژه می‌باشد؛ باید کد را در یک موقعیت valid نگه دارد. Atomic pull request بدین معنی است که حتی الامکان باید pull requestها به کارهای کوچکتر شکسته شوند و review کردن آن‌ها نباید چندین ساعت طول بکشد و به جای یک تسک بزرگ، کارها به تعداد بیشتری task یا issueی کوچک شکسته شوند که هر یک در یک PR قابل انجام باشند.
 
سوال 3)

fetch تغییرات شاخه‌های ریموت را به مخزن محلی شما دانلود می‌کند، اما آنها را ادغام نمی‌کند. این دستور به شما امکان می‌دهد تا تغییرات جدید را در شاخه‌های ریموت مشاهده کنید و آنها را در صورت نیاز ادغام کنید.

merge تغییرات یک شاخه را به شاخه دیگر ادغام می‌کند. این دستور یک commit جدید ایجاد می‌کند که تغییرات دو شاخه را ترکیب می‌کند.

rebase تغییرات یک شاخه را بر روی شاخه دیگر بازنویسی می‌کند. این دستور به شما امکان می‌دهد تا تغییرات یک شاخه را به صورت خطی و بدون ایجاد conflict ادغام کنید.

pull ترکیبی از fetch و merge است. pull تغییرات شاخه‌های ریموت را به مخزن محلی شما دانلود می‌کند و سپس آنها را به شاخه فعال ادغام می‌کند.

در نهایت cherry-pick برای انتقال کامیت ها بین برنچ است که میتوان یک کامیت خاص را منتقل کرد

سوال 4)

دستور revert
یک commit جدید ایجاد خواهد کرد که ما را به commit قبلی برمیگرداند و نکته اینجاست که به تاریخچه موجود ما تغییری اعمال نمی شود.

دستور checkout 
چند کار متفاوت انجام می دهد یکی از آنها جا به جا شدن بین Branch های مختلف است و دیگری Undo change کردن فایلی که هنوز بر روی stage نرفته و چند کاربرد دیگر که در ویدئو ها بررسی شده.

دستور reset 
این دستور برای این است که به یک نقطه خاص از تاریخچه ای که داریم بازگردیم که در ویدئو ها بررسی شده است.

دستور Git restore
این دستور تمامی تغییرات را تا آخرین کامیتی که انجام شده است عقب میبرد

Git switch
تنها برای جا به جایی بین برنچ ها انجام میشود.

سوال 5)

برای دیتا استراکچر روی گیت است که برای فایل ها و تغییرات کد شما و کامیت هایتان است.

به معنای اضافه کردن تغییرات فایل‌های ویرایش شده به index است .که با دستور git add میتوانیم تغیرات فایل را به stage اضافه کنیم وبعدا ان را commit کنیم.

دستور git stash تغییراتی را که در نسخه‌ی فعلی ایجاد کردیم را به طور موقت ذخیره می‌کند تا بتوانیم روی ویژگی دیگری کار کنیم. سپس در آینده هر موقع لازم شد، برگردیم و دوباره آن‌ها را اعمال کنیم.

سوال 6) 

مفهوم snapshot در یک پروژه گرفتن یک تصویر از وضعیت کلی پروژه در یک زمان خاص است.به طوری که به دایرکتوری‌ها، فایل‌ها و تاریخچه فایل‌ها دسترسی داشته‌باشیم. همچنین در git به عنوان یک commit ثبت می‌شود‌.

سوال 7) 

Local repository یک حالت مخزن است کهه روی دستگاه شما است و با دستورات کامیت میتوان آن را اپدیت کرد ولی وفتی میخواهیم با هم دیگه کد بزنیم باید این مخزن را روی سایت گیتهاب ببرم که میشود remote repository که این مخزن با دستور push از مخزن local اطلاعات میگیرد و با دستور pull به آن اطلاعات میدهد.





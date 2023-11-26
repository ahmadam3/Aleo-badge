# Aleo-badge
**در این repo نحوه شرکت در leo contributor badge آموزش میدم.
در این آموزش ما از طریق windows اقدام به نصب زبان برنامه نویسی leo میکنیم و توسط این زبان از طریق محیط ترمینال اقدام به برنامه نویسی میکنیم****

**ابتدا باید 2 پیش نیاز رو نصب کنیم**


1. Install (https://git-scm.com/downloads)
. مراحل نصب برای ویندوز را انجام دهید
2. Install https://visualstudio.microsof
3. t.com/vs/features/cplusplus/
   این مورد رو هم نصب کنبد


   حالا بریم سراغ کارهایی که باید انجام بدیم
   ----------------------------------------------------------------------------------------------------
   **ابتدا ترمینال ویندوز خودمون رو باز میکنیم. من از cmd استفاده کردم با استفاده از سرچ ویندوز میتونید اون رو پیدا کنید**

  1: دانلود و نصب leo

   1.1 نصب rust
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

   
بعد از اجرای این کد 1 و اینتر را بزنید

دوباره اینتر بزنید

1.2 دانلود سورس کد leo

git clone https://github.com/AleoHQ/leo

سپس 
cd leo

1.3 نصب leo

cargo install --path .

بعد از وارد کردن این دستور فرایند نصب شروع میشود و با توجه به سرعت اینترنت شما این فرایند بین 10 الی 20 دقیق طول میکشد

در نهایت بعد از اتمام نصب دستور leo help را وارد کنید و اگر با تصویر زیر روبرو شدید نصب شما موفق بوده است


**2.آموزش کار با leo**

2.1 ساخت ولت جدید
leo account new

یا ایمپورت ولت قدیمی 

leo account import YOUR_Private_Key

به جای YOUR_PRIVATE_KEY شما باید کلید خصوصی خودتون رو قرار بدید

2.2 با دستور زیر چند نمونه از مثالهای آماده رو میتونید مشاهده کنید و به دلخواه یکی رو انتخاب کنید
leo example

2.3 ما از تیک تاک استفاده میکنیم با دستور زیر
leo example tictactoe


2.4 حالا با دستورات زیر میتونید برنامه رو ران منید و مشاهده کنید
cd tictactoe

leo run new


**3. حالا این برنامرو به گیتهاب خودمون هم انتقال بدیم**

3.1 نصب git 

cd tictactoe

git init -b main

git add .

3.2 قبل از ساخت کامیت نیاز هست که شما ایمیل حساب کیتکوین خودتون رو داخل ترمینالتون ثبت کنید

git config --global user.email mail@.com

به جای mail@.com ایمیل خودتون رو قرار بدید 

git config --global user.name your_username

به جای your_username هم یوزرنیم گیتهاب خودتون رو قرار بدید


3.3 حالا کامیت بسازید 


git commit -m "any_name"

به جای عبارت any_name نام دلخواهتون رو قرار بدید

3.4 حالا برید داخل گیتهاب و repo جدید خودتون رو بسازید 
![photo_2023-11-26_19-33-56](https://github.com/ahmadam3/aleojon/assets/56671244/464b4aa7-fac0-4fac-b75a-80f8edeef826)

نام دلخواه خودتون رو قرار بدید و باقی موارد مانند تصویر باشه و در نهایت روی creat repositiry کلیک کنید

3.5 لینک repo خودتون رو در حالت https قرار بدید و کپی کنید
![photo_2023-11-26_19-52-50](https://github.com/ahmadam3/aleojon/assets/56671244/425ea37c-f66e-43d3-a48e-6bece01c4e70)

3.6 دستورات زیر رو در ترمینال خودتون وارد کنید

git branch -m main

git remote add origin YOUR_REPOSITORY_LINK

به جای عبارت YOUR_REPOSITORY_LINK شما باید لینک کپی شده از repo خودتون رو قرار بدید

git remote -v

git push -u origin main

بسیار عالی بعد اتمام این مراحل repo شما ساخته شد و حالا باید برید و اون رو در issue گیتهاب aleo ثبت کنید



باقی مراحل رو طبق تصاویر دنبال کنید
وارد لینک زیر بشید
https://github.com/AleoHQ/leo/issues

![photo_2023-11-26_19-52-58](https://github.com/ahmadam3/aleojon/assets/56671244/9a75cc3e-4df7-4a29-83a3-b7648e5c2028)


طبق تصویر زیر مواردی که به رنگ آبی هست پاک کنید

![photo_2023-11-26_19-53-03](https://github.com/ahmadam3/aleojon/assets/56671244/6f4b7e14-38c1-4d8b-bd93-cb30a68387a4)


تمام مارد مشخص شده در تصویر زیر را ادیت کنید


![photo_2023-11-26_19-53-07](https://github.com/ahmadam3/aleojon/assets/56671244/3cc56a00-3c2b-4567-8953-851e16ecc4a9)






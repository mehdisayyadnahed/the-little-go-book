## درباره کتاب ##
[کتاب کوچک گو](https://www.openmymind.net/The-Little-Go-Book/) کتابی رایگان جهت معرفی زبان برنامه‌نویسی گو (Go) است.

این کتاب توسط [کارل سگوین](https://openmymind.net) نوشته شده است؛ او نویسنده آثار زیر نیز هست:
* [یادگیری زیگ](https://www.openmymind.net/learning_zig/)
* [الیکسیر، کمی فراتر از اصول پایه](https://www.openmymind.net/Elixir-A-Little-Beyond-The-Basics/)
* [مقیاس‌پذیری ویکی](https://openmymind.net/scaling-viki/)
* [کتاب کوچک ردیس](https://openmymind.net/2012/1/23/The-Little-Redis-Book/)
* [کتاب کوچک مونگودی‌بی](https://openmymind.net/2011/3/28/The-Little-MongoDB-Book/)
* [اصول و پایه‌های برنامه‌نویسی](https://openmymind.net/FoundationsOfProgramming.pdf)

## مجوز ##
این کتاب به صورت رایگان تحت مجوز بین‌المللی [Attribution-NonCommercial-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-nc-sa/4.0/) توزیع می‌شود.

## ترجمه‌ها ##

* [فارسی](https://github.com/mehdisayyadnahed/the-little-go-book/tree/master/pe) توسط Mehdi Sayyadnahed
* [پرتغالی](https://github.com/igorverse/the-little-go-book/tree/master/pt-br) (در حال انجام) توسط Fabrício Soares و Igor
* [اسپانیایی](https://raulexposito.com/the-little-go-book-en-castellano.html) توسط Raúl Expósito
* [چینی](https://github.com/songleo/the-little-go-book_ZH_CN) توسط Songleo
* [چینی سنتی](https://github.com/kevingo/the-little-go-book) توسط KevinGo
* [ویتنامی](https://github.com/quangnh89/the-little-go-book/blob/master/vi/readme.md) توسط Quang Nguyễn
* [ایتالیایی](https://github.com/francescomalatesta/the-little-go-book-ita) توسط Francesco Malatesta
* [روسی](https://github.com/sefus/the-little-go-book/blob/master/ru/go.md) توسط Roman Dolgopolov
* [آلمانی](https://github.com/Aaronmacaron/the-little-go-book-de/blob/master/de/go.md) (۱۵٪ انجام شده) توسط Aaron
* [امهری](https://github.com/codeethiopia/the-little-go-book-amharic) توسط codeethiopia
* [کره‌ای](https://github.com/shoebillk/the-little-go-book/blob/master/ko/go.md) توسط Byounghoon Kim
* [برمه‌ای](https://github.com/nainglinaung/the-little-go-book/blob/master/mm/go.md) توسط Naing Lin Aung
* [ترکی](https://github.com/umutphp/the-little-go-book) توسط Umut Işık

## فرمت‌ها ##
این کتاب به فرمت [ماردکاون](https://daringfireball.net/projects/markdown/) نوشته شده و با استفاده از [پاندوک](https://pandoc.org) به PDF تبدیل شده است.

قالب TeX از ابزار برجسته‌سازی نحوی (highlighter) جاوااسکریپتِ Lena Herrmann استفاده می‌کند.

فرمت‌های کیندل (Mobi) و ای‌پاب (ePub) نیز با استفاده از [پاندوک](https://pandoc.org) تهیه شده‌اند.

## تولید فایل کتاب‌ها ##
پکیج‌های لیست‌شده در زیر برای سیستم‌عامل اوبونتو (Ubuntu) هستند. اگر از سیستم‌عامل یا توزیع دیگری استفاده می‌کنید، نام پکیج‌ها احتمالاً مشابه خواهند بود.

### PDF

#### وابستگی‌ها

پکیج‌ها:

* `pandoc`
* `texlive-xetex`
* `texlive-latex-extra`
* `texlive-latex-recommended`

همچنین باید [برخی فونت‌ها](https://github.com/karlseguin/the-little-redis-book/blob/master/common/pdf-template.tex#L11) را روی سیستم خود نصب داشته باشید. یا در صورت تمایل می‌توانید آن‌ها را به فونت‌های دیگر تغییر دهید. به این نکته توجه داشته باشید که فونت‌ها ممکن است باعث بروز [مشکلاتی در فرآیند ساخت کتاب](https://github.com/karlseguin/the-little-redis-book/issues/26) شوند.

#### ساخت

دستور `make en/go.pdf` را اجرا کنید.

### ePub

#### وابستگی‌ها

پکیج‌ها:

* `pandoc`

#### ساخت

دستور `make en/go.epub` را اجرا کنید.

### Mobi

#### وابستگی‌ها

پکیج‌ها:

* `pandoc`

همچنین باید نرم‌افزار [Kindle Previewer](https://www.amazon.com/Kindle-Previewer/b?node=21381691011) را روی سیستم خود نصب داشته باشید.

#### ساخت

دستور `make en/go.mobi` را اجرا کنید.

## تصویر عنوان ##
یک نسخه PSD از تصویر جلد (عنوان) کتاب نیز ضمیمه شده است. فونت استفاده‌شده در آن [Comfortaa](https://www.dafont.com/comfortaa.font) نام دارد.

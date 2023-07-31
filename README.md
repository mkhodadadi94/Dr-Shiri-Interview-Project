# پروژه تستی مصاحبه دکتر شیری

در این پروژه قابلیت محاسبه محیط و مساحت اشکال هندسی دایره، مربع، و مستطیل در زبان برنامه نویسی PHP نوشته شده است.

## 1. قابلیت افزودن اشکال دیگر

با توجه به نیاز به extend کردن کد و اضافه کردن اشکال دیگر، بنده برای هر شکل هندسی یک کلاس و فایل جداگانه ایجاد کردم که میتوان به راحتی اشکال دیگری نیز اضافه کرد.

## 2. رعایت اصول SOLID

**1. SRP:** هر کلاس فقط یک وظیفه دارد و آن هم محاسبه محیط و مساحت شکل مربوط به کلاس است.

**2. OCP:** به راحتی میتوان توسط ShapeFactory کد را extend کرد و نیازی به تغییر بقیه قسمت های کد نیست.

**3. LSP:** چون کد ما وراثت های پیچیده ای ندارد، این principal در اینجا کاربرد ندارد.

**4. ISP:** هیچ کلاسی مجبور به ایجاد توابعی که به کارش نمی آید نیست. در اینترفیس Shape فقط توابع محیط و مساحت که مورد نیاز همه ی کلاس هاست، قرار دارد.

**5. DIP:** هیچ ماژول سطح بالایی به ماژول سطح پایین تر خود وابسطه نیست.

## 3. Design Pattern دلخواه

بنده از Factory Design Pattern استفاده کردم که بتوان به راحتی اشکال دیگری را به کد اضافه کرد.
 

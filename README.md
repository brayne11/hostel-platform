<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>یافت خوابگاه و پانسیون</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">صفحه اصلی</a></li>
                <li><a href="#search">جستجوی خوابگاه</a></li>
                <li><a href="#about">درباره ما</a></li>
                <li><a href="#contact">تماس با ما</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>خوابگاه مورد نظر خود را به راحتی پیدا کنید</h1>
        <p>بهترین خوابگاه‌ها و پانسیون‌ها را در سراسر ایران جستجو کنید.</p>
        <a href="#search" class="btn">شروع جستجو</a>
    </section>

    <section id="search">
        <h2>جستجوی خوابگاه</h2>
        <form action="/search" method="GET">
            <label for="city">شهر:</label>
            <input type="text" id="city" name="city" placeholder="نام شهر را وارد کنید">

            <label for="price">محدوده قیمت:</label>
            <input type="number" id="price" name="price" placeholder="حداکثر قیمت">

            <label for="features">امکانات:</label>
            <select id="features" name="features">
                <option value="internet">اینترنت</option>
                <option value="private_room">اتاق خصوصی</option>
                <option value="shared_kitchen">آشپزخانه مشترک</option>
            </select>

            <button type="submit">جستجو</button>
        </form>
    </section>

    <section id="about">
        <h2>درباره ما</h2>
        <p>ما یک پلتفرم آنلاین برای یافتن خوابگاه‌ها و پانسیون‌های مطمئن و باکیفیت در سراسر ایران هستیم. هدف ما ارائه خدمات سریع و قابل اعتماد برای کاربران است.</p>
    </section>

    <section id="contact">
        <h2>تماس با ما</h2>
        <form action="/contact" method="POST">
            <label for="name">نام:</label>
            <input type="text" id="name" name="name" placeholder="نام شما">

            <label for="email">ایمیل:</label>
            <input type="email" id="email" name="email" placeholder="ایمیل شما">

            <label for="message">پیام:</label>
            <textarea id="message" name="message" placeholder="پیام خود را بنویسید"></textarea>

            <button type="submit">ارسال</button>
        </form>
    </section>

    <footer>
        <p>© 2025 پلتفرم خوابگاه. تمامی حقوق محفوظ است.</p>
    </footer>
</body>
</html>

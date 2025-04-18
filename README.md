<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>کافی‌نت نمونه</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      direction: rtl;
      background-color: #f5f5f5;
      color: #333;
    }
    header {
      background-color: #2c3e50;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1rem;
      background-color: #34495e;
      padding: 0.5rem;
    }
    nav a {
      color: white;
      text-decoration: none;
    }
    .container {
      padding: 2rem;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .service {
      background-color: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>کافی‌نت نمونه</h1>
    <p>ارائه خدمات اینترنتی، تایپ، پرینت و بیشتر</p>
  </header>

  <nav>
    <a href="#services">خدمات</a>
    <a href="#contact">تماس با ما</a>
    <a href="#about">درباره ما</a>
  </nav>

  <div class="container">
    <section id="services">
      <h2>خدمات ما</h2>
      <div class="services">
        <div class="service">تایپ و پرینت</div>
        <div class="service">اسکن و کپی</div>
        <div class="service">ثبت‌نام آزمون‌ها</div>
        <div class="service">طراحی رزومه</div>
        <div class="service">دسترسی به اینترنت</div>
      </div>
    </section>

    <section id="about">
      <h2>درباره کافی‌نت</h2>
      <p>کافی‌نت نمونه با بیش از ۵ سال سابقه در ارائه خدمات دیجیتال، تلاش دارد بهترین تجربه را به مشتریان خود ارائه دهد.</p>
    </section>

    <section id="contact">
      <h2>راه‌های ارتباطی</h2>
      <p>شماره تماس: ۰۹۱۲۱۲۳۴۵۶۷</p>
      <p>آدرس: تهران، خیابان آزادی، نبش کوچه اول</p>
      <p>
        شبکه‌های اجتماعی: 
        <a href="#">اینستاگرام</a> | 
        <a href="#">واتساپ</a>
      </p>
    </section>
  </div>

  <footer>
    &copy; ۲۰۲۵ کافی‌نت نمونه - تمامی حقوق محفوظ است.
  </footer>
</body>
</html>

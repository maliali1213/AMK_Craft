<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8" />
  <title>پرایم ایکس کرفت</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      font-family: Tahoma, sans-serif;
      direction: rtl;
      background: linear-gradient(#1e1e1e, #333);
      color: white;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #d32f2f;
      padding: 30px;
      text-align: center;
      font-size: 30px;
      font-weight: bold;
      border-bottom: 4px solid #ff5252;
      position: relative;
    }
    nav {
      position: absolute;
      top: 35px;
      left: 20px;
    }
    nav a {
      color: #ffd600;
      font-weight: bold;
      margin-left: 20px;
      text-decoration: none;
      font-size: 18px;
      cursor: pointer;
    }
    nav a:hover {
      color: #fff176;
    }
    .server-id {
      background-color: #ff7043;
      padding: 10px 20px;
      font-size: 18px;
      text-align: center;
      font-weight: bold;
    }
    section {
      padding: 20px;
      text-align: center;
    }
    h2 {
      color: #ffd600;
      margin-top: 40px;
      border-bottom: 2px solid #ffd600;
      display: inline-block;
      padding-bottom: 10px;
    }
    .rank {
      background-color: #222;
      padding: 15px;
      margin: 10px auto;
      max-width: 400px;
      border-radius: 10px;
      box-shadow: 0 0 10px #000;
    }
    .rank:nth-child(odd) {
      background-color: #2c2c2c;
    }
    a {
      color: #4fc3f7;
      text-decoration: none;
      font-weight: bold;
    }
    a:hover {
      color: #81d4fa;
    }
    footer {
      background-color: #111;
      padding: 20px;
      text-align: center;
      font-size: 16px;
      margin-top: 40px;
      border-top: 2px solid #444;
    }
    #registerFormContainer {
      display: none;
      position: fixed;
      top: 50%; left: 50%;
      transform: translate(-50%, -50%);
      background-color: #222;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 0 20px #000;
      max-width: 400px;
      width: 90%;
      z-index: 1000;
      text-align: right;
    }
    #registerFormContainer.active {
      display: block;
    }
    #registerFormContainer label {
      display: block;
      margin-bottom: 6px;
      font-weight: bold;
    }
    #registerFormContainer input, 
    #registerFormContainer select {
      width: 100%;
      padding: 8px;
      margin-bottom: 15px;
      border: none;
      border-radius: 5px;
      font-size: 16px;
    }
    #registerFormContainer button {
      background-color: #d32f2f;
      color: white;
      border: none;
      padding: 12px;
      width: 100%;
      border-radius: 8px;
      font-size: 18px;
      cursor: pointer;
      font-weight: bold;
    }
    #registerFormContainer button:hover {
      background-color: #ff5252;
    }
    #registerFormContainer .closeBtn {
      background-color: #555;
      margin-top: 10px;
    }
    #overlay {
      display: none;
      position: fixed;
      top:0; left:0;
      width: 100%; height: 100%;
      background: rgba(0,0,0,0.6);
      z-index: 900;
    }
    #overlay.active {
      display: block;
    }
  </style>
</head>
<body>

<header>
  پرایم ایکس کرفت 🌟
  <nav>
    <a id="showRegisterForm">ثبت نام</a>
    <a href="admin.html">مدیریت</a>
    <a href="#about">درباره ما</a>
  </nav>
</header>

<div class="server-id">
  🎮 آیدی سرور: <strong>primexcraft.aternos.me</strong>
</div>

<section>
  <h2>رنک می‌خوای؟</h2>

  <div class="rank">🎖 بهترین رنک: <strong>اسپانسر</strong></div>
  <div class="rank">🥇 ساپر</div>
  <div class="rank">🥈 امرالد</div>
  <div class="rank">🥉 دایمند</div>
  <div class="rank">🏅 گلد</div>
  <div class="rank">🔰 پایین‌ترین رنک: <strong>ایرون</strong></div>

  <h2>مدیرهای سرور</h2>
  <p>CD_19<br />Ali13246876</p>

  <h2>🛒 خرید داری؟</h2>
  <p>برای خرید داخل روبیکا به آیدی‌های زیر پیام بده و خرید خود را انجام بده ✅</p>
  <p>
    <a href="https://rubika.ir/@CD_19_player" target="_blank">@CD_19_player</a><br />
    <a href="https://rubika.ir/@DrGideon" target="_blank">@DrGideon</a>
  </p>
</section>

<section id="about" style="margin-top:40px; padding: 0 20px; max-width: 600px; margin-left:auto; margin-right:auto; text-align: justify;">
  <h2>درباره ما</h2>
  <p>
    این سرور یکی از سرورهای خیلی عالی است که به دست تیم سازنده و بیلدرها ساخته شده.  
    این سرور خیلی بزرگ است و با مدیریت <strong>CD_19</strong> و <strong>Ali13246876</strong> مدیریت می‌شود.  
    این سرور قابلیت‌های بزرگی مثل رنک و غیره دارد.  
    این سایت نیز توسط تیم <strong>علی ایکس گیمر</strong> طراحی و تولید شده است.
  </p>
</section>

<footer>
  © 2025 - Prime X Craft | طراحی شده توسط <strong>تیم علی ایکس گیمر</strong> 🎮
</footer>

<!-- فرم ثبت نام پاپ‌آپ -->
<div id="overlay"></div>
<div id="registerFormContainer">
  <h2>ثبت نام در پرایم ایکس کرفت</h2>
  <form id="registerForm">
    <label for="name">نام و نام خانوادگی:</label>
    <input type="text" id="name" name="name" required />

    <label for="phone">شماره تلفن:</label>
    <input type="tel" id="phone" name="phone" required pattern="^09\d{9}$" placeholder="مثال: 09123456789" />

    <label for="rank">رنک مورد نظر:</label>
    <select id="rank" name="rank" required>
      <option value="">انتخاب کنید</option>
      <option value="اسپانسر">اسپانسر</option>
      <option value="ساپر">ساپر</option>
      <option value="امرالد">امرالد</option>
      <option value="دایمند">دایمند</option>
      <option value="گلد">گلد</option>
      <option value="ایرون">ایرون</option>
    </select>

    <label for="xpKey">آیا ایکس پی کیلید می‌خوای؟</label>
    <select id="xpKey" name="xpKey" required>
      <option value="">انتخاب کنید</option>
      <option value="بله">بله</option>
      <option value="خیر">خیر</option>
    </select>

    <button type="submit">ثبت نام</button>
    <button type="button" class="closeBtn" id="closeRegisterForm">انصراف</button>
  </form>
</div>

<script>
  const showFormBtn = document.getElementById("showRegisterForm");
  const formContainer = document.getElementById("registerFormContainer");
  const overlay = document.getElementById("overlay");
  const closeFormBtn = document.getElementById("closeRegisterForm");

  showFormBtn.onclick = () => {
    formContainer.classList.add("active");
    overlay.classList.add("active");
  };
  closeFormBtn.onclick = () => {
    formContainer.classList.remove("active");
    overlay.classList.remove("active");
  };
  overlay.onclick = () => {
    formContainer.classList.remove("active");
    overlay.classList.remove("active");
  };

  // فرم ثبت‌نام بدون ارسال واقعی
  document.getElementById("registerForm").addEventListener("submit", function(e) {
    e.preventDefault();
    alert("ثبت نام انجام شد! (ارسال واقعی غیر فعال است)");
    formContainer.classList.remove("active");
    overlay.classList.remove("active");
    this.reset();
  });
</script>

</body>
</html>

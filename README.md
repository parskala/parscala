<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>درباره ما - پارس مدیا و پارس کالا</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: Arial, sans-serif; }
        body { background-color: #f8f9fa; color: #333; }
        
        header { display: flex; justify-content: space-between; align-items: center; padding: 15px 40px; background-color: #fff; border-bottom: 1px solid #eaeaea; position: sticky; top: 0; z-index: 100; box-shadow: 0 2px 10px rgba(0,0,0,0.03); }
        .logo-area { display: flex; align-items: center; gap: 14px; text-decoration: none; }
        .logo-img { width: 45px; height: 45px; border-radius: 50%; object-fit: cover; border: 2px solid #1a382b; }
        .logo-text { display: flex; flex-direction: column; }
        .logo-title { font-size: 20px; font-weight: bold; color: #1a382b; }
        .logo-subtitle { font-size: 11px; color: #777; letter-spacing: 0.5px; }

        .nav-links { display: flex; gap: 25px; font-size: 15px; align-items: center; }
        .nav-links a { color: #555; text-decoration: none; font-weight: 500; transition: color 0.2s; }
        .nav-links a:hover { color: #1a382b; }
        
        .container { max-width: 950px; margin: 50px auto; padding: 0 20px; }
        .about-hero { text-align: center; margin-bottom: 45px; }
        .about-hero h1 { font-size: 38px; color: #1a382b; margin-bottom: 15px; font-weight: 800; }
        .about-hero p { font-size: 17px; color: #666; line-height: 1.8; max-width: 700px; margin: 0 auto; }
        
        .section-box { background: #fff; padding: 35px; border-radius: 16px; box-shadow: 0 6px 20px rgba(0,0,0,0.04); margin-bottom: 30px; border: 1px solid #eaeaea; }
        .section-box h2 { font-size: 24px; color: #1a382b; margin-bottom: 20px; border-right: 5px solid #c85a32; padding-right: 12px; font-weight: 700; }
        .section-box p { font-size: 15px; color: #555; line-height: 1.9; margin-bottom: 15px; }
        
        .features-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 20px; margin-top: 25px; }
        .feature-card { background: #fafbfc; padding: 25px; border-radius: 12px; border-top: 3px solid #1a382b; border-left: 1px solid #eaeaea; border-right: 1px solid #eaeaea; border-bottom: 1px solid #eaeaea; }
        .feature-card h3 { font-size: 18px; color: #1a382b; margin-bottom: 10px; font-weight: bold; }
        .feature-card p { font-size: 14px; color: #666; line-height: 1.6; margin-bottom: 0; }

        footer { text-align: center; padding: 40px; color: #888; font-size: 14px; border-top: 1px solid #eaeaea; margin-top: 60px; background: #fff; }
    </style>
</head>
<body>

    <header>
        <a href="index.html" class="logo-area">
            <img src="logo.png" alt="پارس مدیا" class="logo-img">
            <div class="logo-text">
                <span class="logo-title">پارس کالا</span>
                <span class="logo-subtitle">پارس مدیا (Strategic Digital Partners)</span>
            </div>
        </a>
        <div class="nav-links">
            <a href="index.html">صفحه اصلی</a>
            <a href="about.html" style="font-weight: bold; color: #1a382b;">درباره ما</a>
        </div>
    </header>

    <div class="container">
        <div class="about-hero">
            <h1>درباره هلدینگ رسانه‌ای پارس مدیا</h1>
            <p>مجموعه‌ای پیشرو در زمینه تولید محتوا، رسانه، و تامین تجهیزات و کالاهای مدرن بدون مرز</p>
        </div>

        <div class="section-box">
            <h2>پارس مدیا؛ داستان و هویت ما</h2>
            <p>«پارس مدیا» یک مجموعه و شرکت رسانه‌ای پویا است که با هدف تولید محتوای تخصصی، ساخت ویدیوهای باکیفیت و پوشش حوزه‌های مختلف از جمله کسب‌وکار، تجارت و گردشگری بین‌المللی فعالیت می‌کند.</p>
            <p>ما در پارس مدیا تلاش می‌کنیم با خلق ایده‌های نوآورانه، ارتباط بدون واسطه با مخاطبان و استانداردهای حرفه‌ای، جایگاه ویژه‌ای در دنیای دیجیتال و رسانه خلق کنیم.</p>
        </div>

        <div class="section-box">
            <h2>پارس کالا؛ پل ارتباطی کالاهای خاص</h2>
            <p>فروشگاه «پارس کالا» به عنوان بخش تجاری و تامین کالای مجموعه پارس مدیا متولد شده است. فلسفه اصلی ما ارائه لوازم جانبی کاربردی، گجت‌های هوشمند و انتخاب‌های روزمره با بالاترین کیفیت است تا دسترسی به کالاهای خاص برای مخاطبان به ساده‌ترین شکل ممکن فراهم شود.</p>
            
            <div class="features-grid">
                <div class="feature-card">
                    <h3>کالاهای برگزیده</h3>
                    <p>گلچینی از کاربردی‌ترین محصولات، تجهیزات سفر و گجت‌های روز دنیا برای سلیقه‌های خاص.</p>
                </div>
                <div class="feature-card">
                    <h3>رویکرد مدرن</h3>
                    <p>فراهم کردن دسترسی به انتخاب‌های ارزشمند بر اساس استانداردهای بین‌المللی و دیجیتال.</p>
                </div>
                <div class="feature-card">
                    <h3>اصالت و پشتیبانی</h3>
                    <p>تضمین کیفیت و پشتیبانی مستقیم کالاها با نام و اعتبار هلدینگ رسانه‌ای پارس مدیا.</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        تمامی حقوق محفوظ است © 2026 - هلدینگ رسانه‌ای پارس مدیا / پارس کالا
    </footer>

</body>
</html>

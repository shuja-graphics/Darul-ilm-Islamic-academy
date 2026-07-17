/* Universal Settings */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    background: linear-gradient(180deg, #001f4d 0%, #00102a 100%);
    color: #ffffff;
    text-align: center;
}

/* Top Alert Bar */
.alert-bar {
    background-color: #ffd700;
    color: #000;
    font-weight: bold;
    padding: 10px;
    font-size: 0.9rem;
}

/* Navigation */
.navbar {
    padding: 20px;
}
.navbar a {
    color: #ffd700;
    text-decoration: none;
    margin: 0 10px;
    font-weight: bold;
    font-size: 0.85rem;
}

/* Hero Elements */
.logo-circle {
    width: 100px;
    height: 100px;
    background: #0044ff;
    border: 4px solid #ffd700;
    border-radius: 50%;
    margin: 30px auto;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: bold;
    font-size: 1.5rem;
    box-shadow: 0 0 20px #ffd700;
}

h1, h3 {
    color: #ffffff;
    letter-spacing: 1px;
    margin-bottom: 10px;
}

.location {
    color: #ffd700;
    font-weight: bold;
}

/* Call to Action Buttons */
.cta-buttons {
    margin: 25px 0;
}
.btn {
    display: block;
    width: 200px;
    margin: 15px auto;
    padding: 12px;
    border-radius: 25px;
    text-decoration: none;
    font-weight: bold;
    color: white;
    border: 2px solid #ffffff;
    background: transparent;
}
.btn:hover {
    background: rgba(255, 255, 255, 0.1);
}

/* Glowing Admission Box */
.glow-box {
    background: linear-gradient(135deg, #ff4500, #ff8c00);
    width: 85%;
    max-width: 400px;
    margin: 40px auto 20px auto;
    padding: 30px;
    border-radius: 20px;
    border: 3px solid #ffd700;
    box-shadow: 0 0 25px rgba(255, 215, 0, 0.5);
}
.glow-box h2 {
    color: white;
}
.glow-box span {
    color: #ffd700;
}

.pill-badge {
    border: 2px solid #0044ff;
    display: inline-block;
    padding: 10px 30px;
    border-radius: 20px;
    color: #ffd700;
    background: #001f4d;
}

/* Text Content blocks */
.about-section {
    padding: 40px 20px;
    max-width: 600px;
    margin: 0 auto;
}
.about-section h3 {
    color: #ffd700;
    margin-bottom: 20px;
}
.about-section p {
    line-height: 1.6;
    color: #e0e0e0;
}
<!-- Announcement Bar -->
<div class="announcement-bar">
    <span>📢 علم دین سیکھنے کی عمر نہیں ہوتی اور نہ ہی کوئی عذر۔ آج ہی اس مبارک سفر کا حصہ بنیں!</span>
</div>

<!-- Navigation Header -->
<header class="main-header" dir="ltr">
    <nav class="nav-menu">
        <a href="#home">HOME</a>
        <a href="#about">ABOUT US</a>
        <a href="#courses">COURSES</a>
        <a href="#contact">CONTACT</a>
    </nav>
</header>

<!-- Hero Section -->
<section id="home" class="hero-section">
    <!-- Circular Logo Wrapper -->
    <div class="logo-container">
        <div class="logo-placeholder">
            <i class="fa-solid fa-book-quran"></i>
        </div>
    </div>

    <h1 class="academy-title">DARUL ILM ACADEMY</h1>
    <h2 class="academy-subtitle">دارالعلوم اسلامک اکیڈمی</h2>
    
    <p class="hero-tagline">مستقبل کے معماروں کی دینی و اخلاقی تربیت</p>

    <!-- CTA Buttons -->
    <div class="cta-buttons">
        <a href="https://wa.me/923156821561" target="_blank" class="btn btn-apply">
            <i class="fa-brands fa-whatsapp"></i> ابھی رابطہ کریں (Apply Now)
        </a>
        <a href="tel:03156821561" class="btn btn-call">
            <i class="fa-solid fa-phone"></i> کال کریں (Call Now)
        </a>
    </div>
</section>

<!-- Admission Section -->
<section class="admission-highlight">
    <div class="admission-box">
        <h2>ADMISSION OPEN NOW</h2>
        <h3>ابھی داخلہ لیں!</h3>
    </div>
    <div class="sub-admission-badge">
        آن لائن کلاسز کی سہولت دستیاب ہے
    </div>
</section>

<!-- About Section -->
<section id="about" class="about-section">
    <h2 class="section-title">ABOUT DARUL ILM ACADEMY</h2>
    <div class="about-card">
        <p>
            دارالعلوم اسلامک اکیڈمی کا بنیادی مقصد طالبات کو بہترین دینی اور تعلیمی ماحول فراہم کرنا ہے۔ ہم روایتی اسلامی اقدار اور جدید تدریسی طریقوں کا ایک خوبصورت امتزاج پیش کرتے ہیں تاکہ ہماری طالبات علمِ دین کے زیور سے آراستہ ہو کر معاشرے کی فلاح و بہبود میں اپنا مثبت کردار ادا کر سکیں۔
        </p>
    </div>
</section>

<!-- Courses Section -->
<section id="courses" class="courses-section">
    <h2 class="section-title">ہمارے کورسز (Our Courses)</h2>
    
    <!-- Regular Courses Grid -->
    <h3 class="course-group-title">مکمل اور باقاعدہ کورسز</h3>
    <div class="courses-grid">
        <div class="course-card">
            <div class="course-icon"><i class="fa-solid fa-book-open"></i></div>
            <h3>تفسیر تعلیم قرآن کورس</h3>
            <span class="duration">دورانیہ: 1 سالہ کورس</span>
        </div>
        <div class="course-card">
            <div class="course-icon"><i class="fa-solid fa-star-and-crescent"></i></div>
            <h3>تفسیر صراط الجنان کورس</h3>
            <span class="duration">دورانیہ: 1 سالہ کورس</span>
        </div>
        <div class="course-card">
            <div class="course-icon"><i class="fa-solid fa-microphone"></i></div>
            <h3>تجوید کورس</h3>
            <span class="duration">اہلیت: طالبہ کی قابلیت پر</span>
        </div>
        <div class="course-card">
            <div class="course-icon"><i class="fa-solid fa-book-open-reader"></i></div>
            <h3>ناظرہ قرآن مجید کورس</h3>
            <span class="duration">اہلیت: طالبہ کی قابلیت پر</span>
        </div>
        <div class="course-card">
            <div class="course-icon"><i class="fa-solid fa-pen-clip"></i></div>
            <h3>حدر ٹیسٹ کی تیاری</h3>
            <span class="duration">اہلیت: طالبہ کی قابلیت پر</span>
        </div>
        <div class="course-card">
            <div class="course-icon"><i class="fa-solid fa-graduation-cap"></i></div>
            <h3>درس نظامی ٹیوشن کلاس</h3>
            <span class="duration">طالبات کے لیے مخصوص</span>
        </div>
        <div class="course-card">
            <div class="course-icon"><i class="fa-solid fa-scroll"></i></div>
            <h3>نحو و صرف ٹیوشن کلاس</h3>
            <span class="duration">بنیادی قواعد و ضوابط</span>
        </div>
    </div>

    <!-- Short Courses Grid -->
    <h3 class="course-group-title short-title">مختصر دورانیے اور خصوصی کورسز</h3>
    <div class="courses-grid">
        <div class="course-card special">
            <div class="course-icon"><i class="fa-solid fa-person-dress"></i></div>
            <h3>مسائل النساء کورس</h3>
            <span class="duration">دورانیہ: 1 ماہ کا کورس</span>
        </div>
        <div class="course-card special">
            <div class="course-icon"><i class="fa-solid fa-heart"></i></div>
            <h3>شمائل مصطفیٰ ﷺ کورس</h3>
            <span class="duration">دورانیہ: 1 ماہ کا کورس</span>
        </div>
        <div class="course-card special">
            <div class="course-icon"><i class="fa-solid fa-child"></i></div>
            <h3>مدنی قاعدہ کورس</h3>
            <span class="duration">دورانیہ: 1 ماہ کا کورس</span>
        </div>
        <div class="course-card special">
            <div class="course-icon"><i class="fa-solid fa-gem"></i></div>
            <h3>احکام زینت کورس</h3>
            <span class="duration">دورانیہ: 3 ماہ کا کورس</span>
        </div>
        <div class="course-card special">
            <div class="course-icon"><i class="fa-solid fa-clock-history"></i></div>
            <h3>واقعات قرآن کورس</h3>
            <span class="duration">اہلیت: حفظِ قرآن پر منحصر</span>
        </div>
        <div class="course-card special">
            <div class="course-icon"><i class="fa-solid fa-award"></i></div>
            <h3>تخصص کی ٹیوشن کلاس</h3>
            <span class="duration">ایڈوانس لیول کورسز</span>
        </div>
    </div>
</section>

<!-- Contact & Footer Section -->
<footer id="contact" class="main-footer" dir="ltr">
    <h2 class="section-title">CONTACT US</h2>
    <div class="contact-info">
        <div class="contact-item">
            <i class="fa-brands fa-whatsapp icon-wa"></i>
            <a href="https://wa.me/923156821561" target="_blank">03156821561</a>
        </div>
        <div class="contact-item">
            <i class="fa-solid fa-globe icon-web"></i>
            <a href="https://darulilm-islamic-acadmey.base44.app" target="_blank">darulilm-islamic-acadmey.base44.app</a>
        </div>
        <div class="contact-item">
            <i class="fa-solid fa-envelope icon-mail"></i>
            <a href="mailto:darul.ilmacademyy@gmail.com">darul.ilmacademyy@gmail.com</a>
        </div>
    </div>
    <div class="footer-credit">
        <p>&copy; 2026 Darul Ilm Academy. All Rights Reserved.</p>
    </div>
</footer><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Colorful World</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            /* Vibrant multi-color gradient */
            background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            color: white;
            text-align: center;
        }

        /* Smooth background color shift animation */
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .card {
            background: rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(10px);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
            border: 1px solid rgba(255, 255, 255, 0.18);
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Welcome to My Colorful Website! 🌈</h1>
        <p>Hosted entirely for free on GitHub Pages.</p>
    </div>
</body>
</html>


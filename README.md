<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nahar Landing Page</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;800&display=swap" rel="stylesheet">

    <style>
        :root {
            --primary: #0d1b2a;
            --secondary: #1b263b;
            --accent: #00b4d8;
            --white: #ffffff;
            --text: #333333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Tajawal', sans-serif;
            background: var(--white);
            color: var(--text);
        }

        header {
            background: var(--primary);
            color: var(--white);
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 28px;
            font-weight: 800;
        }

        section.hero {
            padding: 60px 20px;
            text-align: center;
            background: var(--secondary);
            color: var(--white);
        }

        section.hero h2 {
            font-size: 26px;
            margin-bottom: 15px;
        }

        section.hero p {
            font-size: 18px;
            margin-bottom: 25px;
        }

        .btn {
            display: inline-block;
            padding: 12px 25px;
            background: var(--accent);
            color: var(--white);
            text-decoration: none;
            border-radius: 6px;
            font-weight: 600;
            transition: 0.3s ease;
        }

        .btn:hover {
            opacity: 0.85;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #f5f5f5;
            font-size: 14px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Nahar</h1>
    </header>

    <section class="hero">
        <h2>مرحبا بك في صفحتنا</h2>
        <p>نسخة نظيفة وجاهزة للنشر مباشرة بدون أخطاء ترميز.</p>
        <a href="#" class="btn">ابدأ الآن</a>
    </section>

    <footer>
        © 2026 Nahar. All rights reserved.
    </footer>

</body>
</html>

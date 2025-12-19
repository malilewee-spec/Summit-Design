<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>القمة ديزاين | SUMMIT DESIGN</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        :root{
            --black:#0b0b0b;
            --gold:#c9a24d;
            --dark:#1a1a1a;
            --light:#f5f5f5;
            --white:#ffffff;
        }

        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family: "Segoe UI", Tahoma, sans-serif;
        }

        body{
            background:var(--light);
            color:#222;
        }

        /* ===== HEADER ===== */
        header{
           height: 70vh;
            max-height: 650px;
            min-height: 450px;
            background:
                linear-gradient(rgba(0,0,0,.7), rgba(0,0,0,.7)),
                url("header.jpg.jpeg") center/cover no-repeat;
            display:flex;
            flex-direction:column;
        }

        nav{
            display:flex;
            justify-content:space-between;
            align-items:center;
            padding:25px 40px;
        }

        nav img{
            height:70px;
        }

        nav ul{
            list-style:none;
            display:flex;
            gap:25px;
        }

        nav ul li a{
            color:var(--white);
            text-decoration:none;
            font-size:16px;
            transition:.3s;
        }

        nav ul li a:hover{
            color:var(--gold);
        }

        .hero{
            flex:1;
            display:flex;
            flex-direction:column;
            justify-content:center;
            align-items:center;
            text-align:center;
            padding:20px;
        }

        .hero h1{
            color:var(--gold);
            font-size:48px;
            margin-bottom:15px;
        }

        .hero p{
            color:var(--white);
            max-width:700px;
            font-size:18px;
        }

        /* ===== SECTIONS ===== */
        section{
            padding:80px 40px;
        }

        .title{
            text-align:center;
            margin-bottom:50px;
        }

        .title h2{
            color:var(--gold);
            font-size:36px;
        }

        /* ===== ABOUT ===== */
        .about{
            background:var(--white);
            text-align:center;
        }

        .about p{
            max-width:800px;
            margin:auto;
            font-size:18px;
        }

        /* ===== GALLERY ===== */
        .gallery{
            background:var(--dark);
        }

        .gallery h2{
            color:var(--gold);
        }

        .grid{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:20px;
        }

        .grid img{
            width:100%;
            height:250px;
            object-fit:cover;
            border-radius:10px;
            transition:.4s;
        }

        .grid img:hover{
            transform:scale(1.05);
        }

        /* ===== CONTACT ===== */
        .contact{
            background:var(--white);
        }

        .contact-box{
            max-width:800px;
            margin:auto;
            background:var(--black);
            color:var(--white);
            padding:40px;
            border-radius:15px;
            text-align:center;
        }

        .contact-box h2{
            color:var(--gold);
            margin-bottom:20px;
        }

        .contact-box a{
            display:block;
            color:var(--white);
            text-decoration:none;
            margin:10px 0;
            font-size:18px;
        }

        .contact-box a:hover{
            color:var(--gold);
        }

        /* ===== FOOTER ===== */
        footer{
            background:var(--black);
            color:#aaa;
            text-align:center;
            padding:20px;
            font-size:14px;
        }
    </style>
</head>
<body>

<header>
    <nav>
        <img src="logo.jpeg" alt="SUMMIT DESIGN Logo">
        <ul>
            <li><a href="#">الرئيسية</a></li>
            <li><a href="#">من نحن</a></li>
            <li><a href="#">أعمالنا</a></li>
            <li><a href="#">تواصل معنا</a></li>
        </ul>
    </nav>

    <div class="hero">
        <h1>القمة ديزاين</h1>
        <p>
            أصالة الماضي وحداثة الحاضر  
            حيث تتحول المساحات إلى أعمال فنية  
            تعكس ذوقك وهويتك
        </p>
    </div>
</header>

<section class="about">
    <div class="title">
        <h2>من نحن</h2>
    </div>
    <p>
        <strong>SUMMIT DESIGN – القمة ديزاين</strong>  
        شركة متخصصة في تصميم وتنفيذ الأثاث والديكورات الداخلية
        بجودة عالية ولمسات فاخرة تناسب جميع الأذواق.
    </p>
</section>

<section class="gallery">
    <div class="title">
        <h2>أعمالنا</h2>
    </div>
    <div class="grid">
        <img src="img1.jpg" alt="">
        <img src="img2.jpg" alt="">
        <img src="img3.jpg" alt="">
        <img src="img4.jpg" alt="">
        <img src="img5.jpg" alt="">
        <img src="img6.jpg" alt="">
    </div>
</section>

<section class="contact">
    <div class="contact-box">
        <h2>تواصل معنا</h2>
        <a href="mailto:bhaa9967@gmail.com">📧 bhaa9967@gmail.com</a>
        <a href="tel:+963932668141">📞 00963 932 668 141</a>
        <a href="https://facebook.com" target="_blank">📘 Facebook</a>
    </div>
</section>

<footer>
    © 2025 SUMMIT DESIGN | القمة ديزاين
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="tr">
<head>


    <meta charset="UTF-8">




    <meta name="viewport" 
    content="width=device-width,
     initial-scale=1.0">



     <title>Web Geliştirme ve Tasarım Sitesi</title>




        <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <h1>Web Geliştirme ve Tasarım Sitesi</h1>
        <nav>
            <ul>
                <li><a href="#home">Anasayfa</a></li>
                <li><a href="#services">Hizmetler</a></li>
                <li><a href="#portfolio">Portföy</a></li>
                <li><a href="#contact">İletişim</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Hoş Geldiniz!</h2>
        <p>Web geliştirme ve tasarım alanında profesyonel hizmetler sunuyoruz. Modern ve kullanıcı dostu web siteleri oluşturmak için buradayız.</p>
    </section>

    <section id="services">
        <h2>Hizmetlerimiz</h2>
        <ul>
            <li>Web Tasarımı</li>
            <li>Web Geliştirme</li>
            <li>E-ticaret Çözümleri</li>
            <li>SEO Optimizasyonu</li>
        </ul>
    </section>

    <section id="portfolio">
        <h2>Portföyümüz</h2>
        <p>Yaptığımız projelerden bazılarını görmek için aşağıdaki bağlantıya tıklayın.</p>
        <a href="#">Portföyü Görüntüle</a>
    </section>

    <section id="contact">
        <h2>İletişim</h2>
        <p>Bize ulaşmak için aşağıdaki formu doldurun:</p>
        <form action="#" method="post">
            <label for="name">Adınız:</label><br>
            <input type="text" id="name" name="name"><br><br>

            <label for="email">E-posta:</label><br>
            <input type="email" id="email" name="email"><br><br>

            <label for="message">Mesajınız:</label><br>
            <textarea id="message" name="message"></textarea><br><br>

            <input type="submit" value="Gönder">
        </form>
    </section>

    <footer>
      
    CSS



    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }



    section {
        background: white;
        padding: 20px;
        margin: 20px;
        border-radius: 10px;
    }



    h2 {
        color: #333;
    }

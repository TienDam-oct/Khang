<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FreshMart - Cửa Hàng Thực Phẩm</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>FreshMart</h1>
            <nav>
                <ul>
                    <li><a href="#home">Trang chủ</a></li>
                    <li><a href="#products">Sản phẩm</a></li>
                    <li><a href="#about">Giới thiệu</a></li>
                    <li><a href="#contact">Liên hệ</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Thực phẩm sạch, tươi mỗi ngày!</h2>
            <p>Mang đến bữa ăn ngon miệng và an toàn cho gia đình bạn.</p>
            <a href="#products" class="btn">Xem sản phẩm</a>
        </div>
    </section>

    <section id="products" class="products">
        <div class="container">
            <h2>Sản Phẩm Nổi Bật</h2>
            <div class="product-list">
                <div class="product-item">
                    <img src="images/vegetables.jpg" alt="Rau Củ">
                    <h3>Rau Củ Sạch</h3>
                    <p>Giá: 50,000 VND/kg</p>
                    <button class="btn">Mua ngay</button>
                </div>
                <div class="product-item">
                    <img src="images/meat.jpg" alt="Thịt Tươi">
                    <h3>Thịt Tươi</h3>
                    <p>Giá: 120,000 VND/kg</p>
                    <button class="btn">Mua ngay</button>
                </div>
                <div class="product-item">
                    <img src="images/fruit.jpg" alt="Trái Cây">
                    <h3>Trái Cây Tươi</h3>
                    <p>Giá: 70,000 VND/kg</p>
                    <button class="btn">Mua ngay</button>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>Giới Thiệu</h2>
            <p>FreshMart tự hào là cửa hàng thực phẩm sạch tại Ecopark, cung cấp những sản phẩm tươi ngon và đảm bảo an toàn vệ sinh thực phẩm. Chúng tôi cam kết đồng hành cùng sức khỏe gia đình bạn.</p>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Liên Hệ</h2>
            <form action="submit_form.php" method="POST">
                <label for="name">Họ và tên:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Tin nhắn:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit" class="btn">Gửi</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 FreshMart. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>

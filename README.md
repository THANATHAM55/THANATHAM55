<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ร้าน 2hour ไก่ทอดออนไลน์</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>ร้าน 2hour - ไก่ทอดออนไลน์</h1>
        <p>สั่งซื้อทางโทรศัพท์: <a href="tel:0648497153">064-849-7153</a></p>
        <nav>
            <a href="#menu">เมนู</a>
            <a href="#cart">ตะกร้าสินค้า</a>
        </nav>
    </header>

    <section id="menu">
        <h2>เมนูไก่ทอด</h2>
        <div class="menu-item">
            <img src="chicken1.jpg" alt="ไก่ทอดชุดเล็ก">
            <h3>ไก่ทอดชุดเล็ก</h3>
            <p>ราคา: 100 บาท</p>
            <button onclick="addToCart('ไก่ทอดชุดเล็ก', 100)">สั่งซื้อ</button>
        </div>
        <div class="menu-item">
            <img src="chicken2.jpg" alt="ไก่ทอดชุดใหญ่">
            <h3>ไก่ทอดชุดใหญ่</h3>
            <p>ราคา: 180 บาท</p>
            <button onclick="addToCart('ไก่ทอดชุดใหญ่', 180)">สั่งซื้อ</button>
        </div>
    </section>

    <section id="cart">
        <h2>ตะกร้าสินค้า</h2>
        <div id="cart-items"></div>
        <p>ยอดรวม: <span id="total">0</span> บาท</p>
        <button onclick="checkout()">ชำระเงิน</button>
    </section>

    <script src="scripts.js"></script>
</body>
</html>

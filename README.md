<!DOCTYPE html><html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASP Wood Products</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .content {
            padding: 20px;
        }
        .product {
            background: white;
            padding: 15px;
            margin: 15px 0;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .order-form {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin-top: 30px;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px;
        }
        label, input, textarea {
            display: block;
            width: 100%;
            margin-bottom: 10px;
            padding: 8px;
        }
    </style>
</head>
<body>
    <header>
        <h1>ASP কাঠের পণ্য</h1>
        <p>খাঁটি কাঠের খুন্তি, চামচ এবং আরও অনেক কিছু</p>
    </header><nav>
    <a href="#">হোম</a>
    <a href="#products">পণ্যসমূহ</a>
    <a href="#about">আমাদের সম্পর্কে</a>
    <a href="#contact">যোগাযোগ</a>
</nav>

<div class="content">
    <h2 id="products">আমাদের পণ্যসমূহ</h2>
    <div class="product">
        <h3>কাঠের খুন্তি</h3>
        <p>খুবই টেকসই এবং পরিবেশবান্ধব।</p>
        <p>মূল্য: ৳---</p>
    </div>

    <div class="product">
        <h3>কাঠের চামচ</h3>
        <p>খাবার পরিবেশনের জন্য আদর্শ।</p>
        <p>মূল্য: ৳---</p>
    </div>

    <div class="order-form">
        <h3>অর্ডার করুন</h3>
        <form action="#" method="post">
            <label for="name">আপনার নাম:</label>
            <input type="text" id="name" name="name" required>

            <label for="phone">মোবাইল নাম্বার:</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="address">ঠিকানা:</label>
            <textarea id="address" name="address" required></textarea>

            <label for="product">অর্ডারকৃত পণ্যের নাম:</label>
            <input type="text" id="product" name="product" required>

            <input type="submit" value="অর্ডার করুন">
        </form>
    </div>

    <h2 id="about">আমাদের সম্পর্কে</h2>
    <p>ASP একটি বিশ্বস্ত কাঠের পণ্যের প্রতিষ্ঠান যা খাঁটি এবং নিরাপদ রান্নার উপকরণ তৈরি করে। আমরা স্থানীয় কাঠ ব্যবহার করে হাতে তৈরি পণ্য বাজারজাত করি।</p>

    <h2 id="contact">যোগাযোগ করুন</h2>
    <p>ফোন: ---</p>
    <p>ইমেইল: ---</p>
    <p>ঠিকানা: ---</p>
</div>

<footer>
    <p>&copy; ২০২৫ ASP Wood Products | সমস্ত অধিকার সংরক্ষিত।</p>
</footer>

</body>
</html>

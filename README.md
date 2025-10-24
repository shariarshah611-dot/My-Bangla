<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>আমার প্রথম ওয়েবসাইট</title>
    <style>
        /* CSS স্টাইল এখানে যোগ করা হবে */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #0056b3;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>স্বাগতম আমার ওয়েবসাইটে! 🚀</h1>
        <nav>
            <ul>
                <li><a href="#home">হোম</a></li>
                <li><a href="#about">আমাদের সম্পর্কে</a></li>
                <li><a href="#services">পরিষেবা</a></li>
                <li><a href="#contact">যোগাযোগ</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <section id="home">
            <h2>হোম 🏠</h2>
            <p>এটা আমার ওয়েবসাইটের প্রধান পাতা। এখানে আপনি গুরুত্বপূর্ণ তথ্য বা আকর্ষণীয় কন্টেন্ট রাখতে পারেন।</p>
            <p>ওয়েবসাইটটি HTML এবং CSS ব্যবহার করে তৈরি করা হয়েছে।</p>
            <img src="https://via.placeholder.com/600x200?text=আপনার+ছবি+এখানে" alt="একটি উদাহরণ ছবি" style="max-width: 100%; height: auto;">
        </section>

        <hr>

        <section id="about">
            <h2>আমাদের সম্পর্কে 🧑‍💻</h2>
            <p>আমরা কে এবং আমরা কী করি? এই সেকশনে সেই তথ্যগুলি থাকবে। যেমন, আমাদের লক্ষ্য, উদ্দেশ্য এবং টিমের সদস্যদের পরিচিতি।</p>
            <ul>
                <li>লক্ষ্য ১</li>
                <li>লক্ষ্য ২</li>
                <li>লক্ষ্য ৩</li>
            </ul>
        </section>

        <hr>

        <section id="services">
            <h2>পরিষেবা 🛠️</h2>
            <p>আমরা যে সকল পরিষেবা প্রদান করি তার তালিকা:</p>
            <ol>
                <li>ওয়েব ডিজাইন</li>
                <li>সফটওয়্যার ডেভেলপমেন্ট</li>
                <li>কনসাল্টিং</li>
            </ol>
        </section>

        <hr>

        <section id="contact">
            <h2>যোগাযোগ 📞</h2>
            <p>আমাদের সাথে যোগাযোগ করতে নিচের ফর্মটি ব্যবহার করুন (এটি একটি উদাহরণ, এটি কাজ করবে না যতক্ষণ না আপনি একটি ব্যাকএন্ড যোগ করেন)।</p>
            <form action="#" method="POST">
                <label for="name">নাম:</label><br>
                <input type="text" id="name" name="name" required><br><br>

                <label for="email">ইমেল:</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="message">বার্তা:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>

                <input type="submit" value="জমা দিন">
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; ২০২৫ আমার ওয়েবসাইট। সর্বস্বত্ব সংরক্ষিত।</p>
    </footer>

</body>
</html>

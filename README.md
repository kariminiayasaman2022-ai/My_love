<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>دوست دختر برنامه نویس 😎</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Vazir', 'Tahoma', sans-serif;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .card {
            background: rgba(255, 255, 255, 0.07);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border-radius: 40px;
            padding: 40px 30px;
            max-width: 600px;
            width: 100%;
            border: 1px solid rgba(255, 255, 255, 0.12);
            box-shadow: 0 30px 60px rgba(0, 0, 0, 0.6);
            text-align: center;
            transition: all 0.3s ease;
        }

        .card:hover {
            transform: scale(1.01);
            border-color: rgba(255, 70, 200, 0.3);
        }

        .emoji-big {
            font-size: 80px;
            display: block;
            margin-bottom: 10px;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-12px); }
            100% { transform: translateY(0px); }
        }

        h1 {
            color: #fff;
            font-size: 28px;
            font-weight: 800;
            margin-bottom: 8px;
            background: linear-gradient(90deg, #f7971e, #ffd200);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .subtitle {
            color: #c8b6ff;
            font-size: 18px;
            margin-bottom: 30px;
            border-bottom: 1px dashed rgba(255, 255, 255, 0.15);
            padding-bottom: 20px;
        }

        .code-box {
            background: #1e1a2b;
            border-radius: 20px;
            padding: 20px;
            text-align: left;
            direction: ltr;
            font-family: 'Courier New', monospace;
            color: #b7f0b7;
            font-size: 15px;
            line-height: 1.8;
            border-left: 5px solid #ff6bcd;
            box-shadow: inset 0 0 20px rgba(0, 0, 0, 0.5);
            margin-bottom: 25px;
            overflow-x: auto;
            white-space: pre-wrap;
            word-break: break-word;
        }

        .code-box .comment {
            color: #7a7a9a;
        }
        .code-box .keyword {
            color: #ff79c6;
        }
        .code-box .string {
            color: #f1fa8c;
        }
        .code-box .func {
            color: #50fa7b;
        }

        .btn-group {
            display: flex;
            flex-direction: column;
            gap: 12px;
            margin-top: 10px;
        }

        .btn {
            background: rgba(255, 255, 255, 0.06);
            border: 1px solid rgba(255, 255, 255, 0.15);
            color: #fff;
            padding: 14px 20px;
            border-radius: 50px;
            font-size: 17px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.25s ease;
            backdrop-filter: blur(4px);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .btn:hover {
            background: #ff6bcd;
            border-color: #ff6bcd;
            transform: translateY(-3px);
            box-shadow: 0 12px 30px rgba(255, 107, 205, 0.35);
            color: #0f0c29;
        }

        .btn-secondary {
            background: rgba(255, 215, 0, 0.08);
            border-color: #ffd70055;
        }

        .btn-secondary:hover {
            background: #ffd700;
            border-color: #ffd700;
            box-shadow: 0 12px 30px rgba(255, 215, 0, 0.35);
            color: #0f0c29;
        }

        .footer-note {
            margin-top: 25px;
            color: #7a7a9a;
            font-size: 14px;
            border-top: 1px solid rgba(255, 255, 255, 0.06);
            padding-top: 20px;
        }

        .footer-note span {
            color: #ff6bcd;
            font-weight: 700;
        }

        /* واکنش‌گرایی */
        @media (max-width: 480px) {
            .card { padding: 25px 15px; }
            h1 { font-size: 22px; }
            .code-box { font-size: 13px; padding: 15px; }
        }
    </style>
</head>
<body>

<div class="card">

    <span class="emoji-big">👩🏻‍💻</span>
    <h1>دوست‌دختر برنامه‌نویس</h1>
    <div class="subtitle">حالا دیگه باگ‌ها عاشقتم می‌کنن 😂</div>

    <!-- بخش کد (طنز) -->
    <div class="code-box">
        <span class="comment">// وقتی دوست‌دخترت برنامه‌نویسه</span>
        <br>
        <span class="keyword">function</span> <span class="func">loveYou</span>() {
        <br>
        &nbsp;&nbsp;<span class="keyword">while</span> (true) {
        <br>
        &nbsp;&nbsp;&nbsp;&nbsp;console.log(<span class="string">"❤️ دوستت دارم بی‌نهایت"</span>);
        <br>
        &nbsp;&nbsp;&nbsp;&nbsp;<span class="keyword">if</span> (you.happy) <span class="keyword">break</span>;
        <br>
        &nbsp;&nbsp;}
        <br>
        &nbsp;&nbsp;<span class="keyword">return</span> <span class="string">"💖 تا آخرین commit"</span>;
        <br>
        }
        <br><br>
        <span class="comment">// خروجی: همیشه عشق ❤️</span>
    </div>

    <!-- دکمه‌ها -->
    <div class="btn-group">
        <button class="btn" onclick="showLove()">
            ❤️ درخواست کد عشق
        </button>
        <button class="btn btn-secondary" onclick="shareForFriends()">
            📤 برای دوستات بفرست
        </button>
    </div>

    <div class="footer-note">
        🧡 <span id="loveMessage">روی دکمه بزن تا عشق رو ببینی</span>
    </div>

</div>

<script>
    function showLove() {
        const msg = document.getElementById('loveMessage');
        const messages = [
            'کد عشق: printf("دوستت دارم ❤️");',
            '✅ کد ارسال شد! (البته فقط به دل تو)',
            '💕 خطای ۴۰۴ نشد! عشق پیدا شد.',
            '😎 این کد رو فقط به برنامه‌نویس‌های واقعی بده.',
            '🌸 return "I love you 3000";'
        ];
        const random = Math.floor(Math.random() * messages.length);
        msg.textContent = messages[random];
        msg.style.color = '#ff79c6';
    }

    function shareForFriends() {
        const msg = document.getElementById('loveMessage');
        msg.textContent = '📲 لینک کپی شد! (البته توی ذهنت)';
        msg.style.color = '#ffd700';
        // شبیه‌سازی کپی
        navigator.clipboard?.writeText('👩🏻‍💻 دوست دختر برنامه‌نویس دارم! 😎');
    }
</script>

</body>
</html>

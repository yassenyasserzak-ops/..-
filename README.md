<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>كل سنة وأنتِ طيبة يا ملوكة 🌹</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body, html {
            height: 100%;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* فيديو الخلفية */
        #bg-video {
            position: fixed;
            right: 0;
            bottom: 0;
            min-width: 100%;
            min-height: 100%;
            z-index: -1;
            object-fit: cover;
        }

        /* طبقة التظليل */
        .overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.4); /* تظليل أغمق قليلاً لتوضيح الكلام العربي */
            z-index: 0;
        }

        /* البطاقة الزجاجية */
        .glass-card {
            position: relative;
            z-index: 1;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 20px;
            padding: 25px;
            width: 90%;
            max-width: 450px;
            text-align: center;
            color: white;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.5);
        }

        .profile-pic img {
            width: 90px;
            height: 90px;
            border-radius: 50%;
            border: 2px solid #fff;
            margin-bottom: 15px;
        }

        h2 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: #ffb6c1;
        }

        .message {
            line-height: 1.6;
            font-size: 1.15rem;
            margin-bottom: 20px;
            font-weight: 400;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
        }

        .emojis {
            font-size: 1.4rem;
            letter-spacing: 5px;
        }

        /* أنيميشن بسيط لظهور النص */
        .glass-card {
            animation: fadeIn 2s ease-in;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

    <video autoplay muted loop id="bg-video">
        <source src="1000129029.mp4" type="video/mp4">
    </video>

    <div class="overlay"></div>

    <div class="glass-card">
        <div class="profile-pic">
            <img src="https://i.pinimg.com/originals/2b/6e/6e/2b6e6e2b6e6e2b6e6e2b6e6e2b6e6e2b.png" alt="ملوكة">
        </div>
        
        <h2>إلى أجمل ملوكة ❤️</h2>
        
        <div class="message">
            كل سنة وأنتِ معايا.. <br>
            كل سنة وأنتِ أحن وأطيب قلب عليا.. <br>
            كل سنة وأنا مليش غيرك.. <br>
            بحبك يا ست الكل وكل سنة وأنتِ منورة حياتي.. <br>
            كل سنة وأنتِ أحلى وأجمل ملوكة في الدنيا.. <br>
            ربنا يخليكي ليا يارب وميحرمنيش منك أبداً.. <br>
            يارب ماشوف فيكي حاجة وحشة أبداً.. <br>
            كل سنة وأنتِ روحي.. بحبك يا كتكوتي.. <br>
            ودي حاجة بسيطة من اللي أنتِ بتعمليه معايا.
        </div>
        
        <div class="emojis">
            🎂🐥💖🌹🫶🏻
        </div>
    </div>

</body>
</html>
# ..-
sjdj

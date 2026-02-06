<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For Prashna ❤️</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Playfair+Display:ital,wght@0,400;1,700&family=Lora:ital,wght@0,400;1,400&display=swap');

        body {
            margin: 0; padding: 0;
            /* Deep Rose/Velvet Background */
            background: linear-gradient(135deg, #1a0000 0%, #4d0000 50%, #1a0000 100%);
            color: #f8f8f8;
            font-family: 'Lora', serif;
            line-height: 1.8;
            overflow-x: hidden;
        }

        /* Rose & Petal Animation */
        .rose-petal {
            position: fixed; top: -50px; z-index: 0;
            pointer-events: none; animation: fall linear infinite;
            font-size: 25px;
        }

        @keyframes fall {
            0% { transform: translateY(0) rotate(0deg); opacity: 1; }
            100% { transform: translateY(110vh) rotate(360deg); opacity: 0; }
        }

        .container {
            max-width: 750px;
            margin: 0 auto;
            padding: 100px 20px;
            position: relative; z-index: 1;
        }

        .section {
            margin-bottom: 150px;
            opacity: 0; transform: translateY(40px);
            transition: all 2s ease;
            background: rgba(0, 0, 0, 0.4);
            padding: 50px;
            border-radius: 20px;
            border: 1px solid rgba(255, 182, 193, 0.2);
            backdrop-filter: blur(10px);
        }

        .section.visible { opacity: 1; transform: translateY(0); }

        h1 { font-family: 'Dancing Script', cursive; font-weight: 700; color: #ff4d6d; font-size: 3.5rem; margin-bottom: 30px; }
        
        .photo {
            width: 100%; max-width: 450px;
            border: 10px solid #fff; box-shadow: 0 20px 50px rgba(0,0,0,0.6);
            margin: 40px auto; display: block;
            border-radius: 2px;
        }

        p { font-size: 1.25rem; color: #f1f1f1; margin-bottom: 30px; }

        .highlight { color: #ffb3c1; font-weight: 600; font-style: italic; }

        .divider { width: 150px; height: 1px; background: #ff4d6d; margin: 80px auto; opacity: 0.5; }

        .apology-box {
            border-left: 4px solid #ff4d6d; padding-left: 30px; margin: 50px 0; 
            font-style: italic; color: #ffb3c1; font-size: 1.3rem;
        }

        .proposal-btn {
            background: #ff4d6d; color: #fff; border: none;
            padding: 22px 60px; font-family: 'Dancing Script', cursive; font-size: 2.2rem;
            cursor: pointer; margin-top: 50px; border-radius: 60px;
            transition: 0.5s; box-shadow: 0 0 30px rgba(255, 77, 109, 0.5);
        }

        .proposal-btn:hover { transform: scale(1.1); background: #ff1a40; box-shadow: 0 0 50px #ff4d6d; }

        #finalContent { display: none; margin-top: 80px; text-align: center; border-top: 1px dashed #ff4d6d; padding-top: 50px; }

        footer { text-align: center; font-size: 0.9rem; color: rgba(255, 255, 255, 0.3); margin-top: 120px; font-style: italic; }
    </style>
</head>
<body>

    <audio id="bgMusic" loop><source src="music.mp3" type="audio/mpeg"></audio>

    <div class="container">
        
        <div class="section">
            <h1>Dearest Prashna,</h1>
            <p>I built this garden of words for you because I wanted to speak from my heart without any more drama. You have always been the person who brought peace to my life, and I am truly sorry for the stress I have caused lately.</p>
            <img src="IMG_1265.jpeg" class="photo" alt="Prashna">
            <p>This is a place for us to remember the beautiful moments we shared, before the mistakes and the noise got in the way.</p>
        </div>

        <div class="divider"></div>

        <div class="section">
            <p>Our story began in <span class="highlight">April 2022 at Bupa</span>. From those first shifts to the home we built in <span class="highlight">Flemington and Homebush West</span>, you were my world. I cherish the memories of our <span class="highlight">Malatang dates</span> and those winter nights sharing <span class="highlight">hot chocolate</span>. I miss that quiet happiness every single day.</p>
            <img src="6006.jpg" class="photo" style="max-width: 380px;">
        </div>

        <div class="section">
            <p>I look at this photo from <span class="highlight">August 4th</span> and I see the light in your eyes that I was supposed to protect. I failed that responsibility.</p>
            <img src="6005.jpg" class="photo">
            <div class="apology-box">
                "I let other things become my priority. I didn't stand for you when you needed a partner you could count on. I am sorry for not being the man you deserved in those moments."
            </div>
            <p>I miss our drives to <span class="highlight">Ulladulla, Jervis Bay, Wollongong, Port Macquarie, Coffs Harbour, and Armidale</span>. Those long roads with you were the happiest I’ve ever been.</p>
        </div>

        <div class="section">
            <h1>To Your Mom, Dad & Family</h1>
            <p>I want to offer my deepest and most sincere apologies to your Mom and Dad. I failed the trust of your family and I am sorry for the pain I brought to your home. I have nothing but respect for all of you.</p>
            <div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin-top: 30px;">
                <img src="6003.png" style="width: 250px; border: 5px solid #fff; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
                <img src="6004.jpg" style="width: 250px; border: 5px solid #fff; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
            </div>
        </div>

        <div class="section">
            <h1>My Hope for You</h1>
            <p>Prashna, I want you to be the most successful Registered Nurse. I want you to have the beautiful future and the daughter you've always dreamed of. You deserve a life full of love and success.</p>
            <p>If you can find it in your heart to forgive me, I am ready to make you my only priority from this day forward.</p>
            
            <button class="proposal-btn" onclick="showFinal()">Will you marry me?</button>

            <div id="finalContent">
                <p style="font-family: 'Dancing Script'; font-size: 3rem; color: #ffb6c1;">Prashna, let us start again.</p>
                <p>I will never forget you. ❤️</p>
                <p style="font-size: 1.5rem; color: #ff4d6d;">— Always Yours, Pratham</p>
            </div>
        </div>

        <footer>
            Forever in my heart, Prashna Kumari Aryal
        </footer>

    </div>

    <script>
        // Rose and Petal generator
        function createPetal() {
            const symbols = ['🌹', '🥀', '🌸', '❤️'];
            const petal = document.createElement('div');
            petal.innerHTML = symbols[Math.floor(Math.random() * symbols.length)];
            petal.className = 'rose-petal';
            petal.style.left = Math.random() * 100 + 'vw';
            petal.style.animationDuration = Math.random() * 4 + 4 + 's';
            petal.style.opacity = Math.random() * 0.7 + 0.3;
            document.body.appendChild(petal);
            setTimeout(() => petal.remove(), 8000);
        }
        setInterval(createPetal, 400);

        // Scroll reveal
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                    document.getElementById('bgMusic').play().catch(()=>{});
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.section').forEach(s => observer.observe(s));

        function showFinal() {
            document.getElementById('finalContent').style.display = 'block';
            window.scrollTo({ top: document.body.scrollHeight, behavior: 'smooth' });
        }
    </script>
</body>
</html>

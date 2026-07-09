<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الملاذ السري المطور 🌌</title>
    <!-- استيراد مكتبة Firebase الأساسية -->
    <script src="https://www.gstatic.com/firebasejs/10.8.0/firebase-app-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/10.8.0/firebase-database-compat.js"></script>
    
    <style>
        :root {
            --bg-color: #050811;
            --panel-bg: rgba(10, 25, 47, 0.7);
            --accent-blue: #00f2fe;
            --royal-blue: #4facfe;
            --text-color: #e2e8f0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: radial-gradient(circle at center, #0a192f 0%, var(--bg-color) 100%);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }

        /* جدار الحماية السرّي */
        #auth-overlay {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: var(--bg-color);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: 1000;
            transition: all 0.5s ease;
        }

        .auth-box {
            background: var(--panel-bg);
            padding: 40px;
            border-radius: 16px;
            border: 1px solid var(--accent-blue);
            box-shadow: 0 0 25px rgba(0, 242, 254, 0.2);
            text-align: center;
            backdrop-filter: blur(10px);
        }

        /* الحاوية الرئيسية للموقع */
        .container {
            max-width: 900px;
            width: 100%;
            display: none; /* مخفي حتى إدخال الرمز */
            animation: fadeIn 1s ease forwards;
        }

        .panel {
            background: var(--panel-bg);
            border: 1px solid rgba(79, 172, 254, 0.3);
            border-radius: 16px;
            padding: 25px;
            margin-bottom: 25px;
            backdrop-filter: blur(12px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }

        .panel:hover {
            transform: translateY(-5px);
            border-color: var(--accent-blue);
        }

        h1, h2 {
            color: var(--accent-blue);
            text-shadow: 0 0 10px rgba(0, 242, 254, 0.5);
            margin-top: 0;
        }

        input, textarea {
            width: 100%;
            padding: 12px;
            background: rgba(5, 8, 17, 0.8);
            border: 1px solid rgba(79, 172, 254, 0.5);
            border-radius: 8px;
            color: #fff;
            box-sizing: border-box;
            margin-bottom: 15px;
            font-size: 16px;
        }

        input:focus, textarea:focus {
            outline: none;
            border-color: var(--accent-blue);
            box-shadow: 0 0 10px rgba(0, 242, 254, 0.3);
        }

        button {
            background: linear-gradient(45deg, var(--royal-blue), var(--accent-blue));
            border: none;
            color: #050811;
            padding: 12px 25px;
            font-weight: bold;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 16px;
        }

        button:hover {
            box-shadow: 0 0 15px var(--accent-blue);
            transform: scale(1.02);
        }

        /* نظام الفيديوهات */
        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .video-card {
            background: rgba(5, 8, 17, 0.6);
            border-radius: 12px;
            overflow: hidden;
            border: 1px solid rgba(255,255,255,0.1);
        }

        .video-container {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
        }

        .video-container iframe {
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            border: none;
        }

        /* نظام التعليقات الحية */
        .comments-section {
            max-height: 300px;
            overflow-y: auto;
            margin-top: 20px;
            padding-left: 10px;
        }

        .comment-bubble {
            background: rgba(255, 255, 255, 0.05);
            padding: 12px 18px;
            border-radius: 12px;
            margin-bottom: 10px;
            border-right: 4px solid var(--royal-blue);
            animation: slideIn 0.3s ease;
        }

        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        @keyframes slideIn { from { transform: translateX(20px); opacity: 0; } to { transform: translateX(0); opacity: 1; } }
    </style>
</head>
<body>

    <!-- جدار الحماية -->
    <div id="auth-overlay">
        <div class="auth-box">
            <h2>🔒 بوابة الملاذ السري</h2>
            <p>أدخلي شفرة الدخول السرية لتفعيل المنصة:</p>
            <input type="password" id="secret-key" placeholder="••••">
            <button onclick="checkPassword()">دخول</button>
        </div>
    </div>

    <!-- المحتوى الرئيسي للموقع -->
    <div class="container" id="main-content">
        <header class="panel" style="text-align: center;">
            <h1>🌌 WORLDWIDE HUB 🌌</h1>
            <p>مرحباً بكِ في النسخة المطورة السحابية الحية</p>
        </header>

        <!-- قسم إضافة الفيديوهات -->
        <div class="panel">
            <h2>🎬 إضافة فيديو سري للمنصة</h2>
            <input type="text" id="video-id-input" placeholder="ضعي كود فيديو اليوتيوب فقط (مثال: dQw4w9WgXcQ)">
            <button onclick="uploadVideo()">نشر الفيديو للجميع 🚀</button>
            
            <div class="video-grid" id="videos-display">
                <!-- الفيديوهات ستظهر هنا تلقائياً من السحاب -->
            </div>
        </div>

        <!-- قسم التعليقات الحية المحفوظة -->
        <div class="panel">
            <h2>💬 جدار الذكريات والدردشة الحية</h2>
            <textarea id="comment-text-input" rows="3" placeholder="اكتبي رسالتكِ السحرية هنا..."></textarea>
            <button onclick="uploadComment()">إرسال الرسالة ✍️</button>
            
            <div class="comments-section" id="comments-display">
                <!-- التعليقات ستظهر هنا وتُحفظ للأبد -->
            </div>
        </div>
    </div>

    <script>
        // 1. التحقق من كلمة السر
        function checkPassword() {
            const pass = document.getElementById('secret-key').value;
            if(pass === '1234') { // شفرتكِ المفضلة
                document.getElementById('auth-overlay').style.opacity = '0';
                setTimeout(() => {
                    document.getElementById('auth-overlay').style.display = 'none';
                    document.getElementById('main-content').style.display = 'block';
                }, 500);
            } else {
                alert('الشفرة خاطئة! المحاولة مسجلة 🕵️‍♀️');
            }
        }

        // ==========================================
        // ⚠️ ضعي إعدادات FIREBASE الخاصة بكِ هنا ⚠️
        // ==========================================
        const firebaseConfig = {
            apiKey: "ضعي_هنا_API_KEY",
            authDomain: "ضعي_هنا_AUTH_DOMAIN",
            databaseURL: "ضعي_هنا_DATABASE_URL",
            projectId: "ضعي_هنا_PROJECT_ID",
            storageBucket: "ضعي_هنا_STORAGE_BUCKET",
            messagingSenderId: "ضعي_هنا_MESSAGING_SENDER_ID",
            appId: "ضعي_هنا_APP_ID"
        };

        // تشغيل الفايربيس
        firebase.initializeApp(firebaseConfig);
        const database = firebase.database();

        // 2. تفعيل جلب البيانات الحية للتعليقات
        database.ref('comments').on('value', (snapshot) => {
            const commentsDisplay = document.getElementById('comments-display');
            commentsDisplay.innerHTML = '';
            const data = snapshot.val();
            if(data) {
                Object.values(data).reverse().forEach(c => {
                    commentsDisplay.innerHTML += `<div class="comment-bubble">${c.text}</div>`;
                });
            }
        });

        // 3. تفعيل جلب البيانات الحية للفيديوهات
        database.ref('videos').on('value', (snapshot) => {
            const videosDisplay = document.getElementById('videos-display');
            videosDisplay.innerHTML = '';
            const data = snapshot.val();
            if(data) {
                Object.values(data).forEach(v => {
                    videosDisplay.innerHTML += `
                        <div class="video-card">
                            <div class="video-container">
                                <iframe src="https://www.youtube.com/embed/${v.id}" allowfullscreen></iframe>
                            </div>
                        </div>`;
                });
            }
        });

        // 4. دالة إرسال التعليق للسحاب
        function uploadComment() {
            const txt = document.getElementById('comment-text-input').value;
            if(txt.trim() !== "") {
                database.ref('comments').push({ text: txt });
                document.getElementById('comment-text-input').value = '';
            }
        }

        // 5. دالة إرسال كود الفيديو للسحاب
        function uploadVideo() {
            const vid = document.getElementById('video-id-input').value;
            if(vid.trim() !== "") {
                database.ref('videos').push({ id: vid });
                document.getElementById('video-id-input').value = '';
            }
        }
    </script>
</body>
</html>
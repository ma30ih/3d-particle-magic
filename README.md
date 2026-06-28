# ✨ 3D Particle Magic

![Magic Particle Fingers Demo](Demo.gif)

An interactive 3D WebGL particle system driven by AI hand-tracking, featuring smooth scaling, custom physics boundaries, and gesture-controlled explosions.
*(توضیحات فارسی در پایین صفحه)*

## 🌟 Try the Live Demo
👉 **[Click Here to Experience It Live!](https://ma30ih.github.io/3d-particle-magic/)** 👈
*(Note: Requires camera access to track your hand gestures. All AI processing runs locally on your device.)*

## 🎮 How It Works & Gestures
After choosing your custom background and magic color from the UI menu, hold your hand in front of the camera:
* **Two Hands Distance:** Dynamically scales the particle sphere (`↔️ Smooth Scaling`).
* **One Finger Pointing (Index Up):** Rotates the 3D particle system based on your finger movement (`☝🏻 Rotation Control`).
* **Fist (All Fingers Down):** Triggers a cosmic Big Bang! The particles explode, obeying boundary physics and bouncing off the screen walls (`💥 Particle Explosion`).
* **Open Hand (All Fingers Up):** Recovers the scattered matter, bringing particles back to their original 3D sphere shape (`🔄 Quantum Reset`).

## 🇮🇷 توضیحات فارسی
این پروژه یک شبیه‌ساز فیزیک ذرات سه‌بعدی در محیط WebGL است که با کتابخانه Three.js توسعه یافته است. کاربر ابتدا در یک منوی تعاملی جذاب، نوع پس‌زمینه (دوربین یا مشکی) و رنگ جادوی خود را انتخاب می‌کند و سپس با حرکات دست، کنترل این جهان سه‌بعدی را به دست می‌گیرد.

* **تغییر سایز دو دستی:** با دور و نزدیک کردن دو دست، کل سیستم ذرات بزرگ و کوچک می‌شود.
* **چرخش ماتریکسی:** با اشاره انگشت سبابه، می‌توانید کره ذرات را در فضا بچرخانید.
* **انفجار و فیزیک برخورد:** با مشت کردن دست، ذرات با سرعت منفجر شده و پس از برخورد به دیواره‌های فرضی صفحه سه‌بعدی، به زیبایی کمانه می‌کنند (Wall Bounce). با باز کردن مجدد دست، ذرات به فرم کروی خود بازمی‌گردند.
* **حریم خصوصی:** تمام پردازش‌های هوش مصنوعی مستقیماً روی مرورگر (لوکال) انجام می‌شود و هیچ ویدیویی ذخیره یا به سروری ارسال نمی‌گردد.

## 🛠️ Tech Stack
* HTML5 / CSS3 & Modern UI Architecture
* Vanilla JavaScript (ES6+)
* [Three.js](https://threejs.org/) (WebGL 3D Core Engine)
* [Google MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands)

## 💻 Local Installation
To run this project locally, use a local server due to browser security restrictions regarding camera access:
* **VS Code:** Install "Live Server" extension and click "Go Live".
* **Python:** Run `python -m http.server` in your terminal.

## 📫 Get In Touch
* **Email:** msyhan85@gmail.com

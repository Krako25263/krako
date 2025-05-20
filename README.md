<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>กล่อง 💝</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom, #ffe4ec, #fff);
      text-align: center;
      padding: 50px;
    }

    h1 {
      color: #d6336c;
      font-size: 2.5em;
    }

    .gift-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 40px;
    }

    .gift-box {
      background: #fff0f6;
      border: 2px dashed #ff99c8;
      border-radius: 20px;
      padding: 30px;
      width: 150px;
      height: 150px;
      cursor: pointer;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.2s ease;
      font-size: 1.5em;
    }

    .gift-box:hover {
      transform: scale(1.05);
    }

    .popup {
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0, 0, 0, 0.6);
      display: none;
      align-items: center;
      justify-content: center;
    }

    .popup-content {
      background: white;
      padding: 30px;
      border-radius: 20px;
      max-width: 90%;
      font-size: 1.2em;
      color: #333;
    }

    .close-btn {
      margin-top: 15px;
      background: #ff99c8;
      border: none;
      padding: 10px 20px;
      border-radius: 10px;
      color: white;
      cursor: pointer;
    }

    .close-btn:hover {
      background: #d6336c;
    }
  </style>
</head>
<body>

  <h1>เลือกกล่องที่อยากเปิดวันนี้ 🎁</h1>

  <div class="gift-container">
    <div class="gift-box" onclick="openPopup('โคนันสนุกไหมมมมมวันนี้ 😊')">🎁</div>
    <div class="gift-box" onclick="openPopup('ถ้าได้เจอกัน จะซื้อไอติมให้เธอทันที 🍦')">🎁</div>
    <div class="gift-box" onclick="openPopup('ขอส่งความคิดถึงผ่านหน้าจอไปหานะ 💌')">🎁</div>
    <div class="gift-box" onclick="openPopup('ได้ไรกินยังค้าบบบบบบบบบ 🧸')">🎁</div>
    <div class="gift-box" onclick="openPopup('ทำไรอยู่ค้าบบบบบบบบบ 🫶')">🎁</div>
  </div>

  <div class="popup" id="popup">
    <div class="popup-content" id="popup-message">
      <!-- ข้อความจะแสดงที่นี่ -->
    </div>
    <button class="close-btn" onclick="closePopup()">ปิด</button>
  </div>

  <script>
    function openPopup(message) {
      document.getElementById('popup-message').innerText = message;
      document.getElementById('popup').style.display = 'flex';
    }

    function closePopup() {
      document.getElementById('popup').style.display = 'none';
    }
  </script>

</body>
</html>
<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <title>กล่อง 💝</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <h1>เลือกกล่องที่อยากเปิดวันนี้ 🎁</h1>

  <div class="gift-container">
    <div class="gift-box" onclick="openPopup('โคนันสนุกไหมมมมมวันนี้ 😊')">🎁</div>
    <div class="gift-box" onclick="openPopup('ถ้าได้เจอกัน จะซื้อไอติมให้เธอทันที 🍦')">🎁</div>
    <div class="gift-box" onclick="openPopup('ขอส่งความคิดถึงผ่านหน้าจอไปหานะ 💌')">🎁</div>
    <div class="gift-box" onclick="openPopup('ได้ไรกินยังค้าบบบบบบบบบ 🧸')">🎁</div>
    <div class="gift-box" onclick="openPopup('ทำไรอยู่ค้าบบบบบบบบบ 🫶')">🎁</div>
  </div>

  <div class="popup" id="popup">
    <div class="popup-content" id="popup-message">
      <!-- ข้อความจะแสดงที่นี่ -->
    </div>
    <button class="close-btn" onclick="closePopup()">ปิด</button>
  </div>

  <script src="script.js"></script>
</body>
</html>

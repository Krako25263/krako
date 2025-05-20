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

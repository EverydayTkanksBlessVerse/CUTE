<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>나의 미니홈</title>

<style>
  body {
    margin:0;
    font-family: 'Pretendard', sans-serif;
    background: linear-gradient(to bottom, #ffe0ea, #dff1ff);
    display:flex; flex-direction:column;
    align-items:center; text-align:center;
    padding:40px 20px;
  }

  .card {
    width:min(90vw,420px);
    background:white;
    border-radius:18px;
    padding:24px;
    box-shadow:0 6px 26px rgba(0,0,0,.15);
  }

  .profile-img {
    width:110px; height:110px;
    border-radius:50%;
    overflow:hidden;
    margin:auto;
    border:4px solid #ffc2d4;
  }

  .profile-img img {
    width:100%; height:100%; object-fit:cover;
  }

  h1 { font-size:22px; margin:14px 0 6px; }
  .desc { font-size:14px; color:#666; margin-bottom:18px; }

  .link-box {
    display:flex; flex-direction:column; gap:10px;
    margin-top:20px;
  }

  .link {
    padding:14px; border-radius:12px;
    background:#fff7fa;
    border:1px solid #ffd1e2;
    font-weight:600; cursor:pointer;
  }
</style>

</head>
<body>

<div class="card">
  <div class="profile-img">
    <!-- 여기 이미지 바꾸면 캐릭터 변경됨 -->
    <img src="https://i.imgur.com/PElZ08D.png">
  </div>

  <h1>🐹 햄스터 도하</h1>
  <div class="desc">따뜻하게 자라는 중… ✨</div>

  <div class="link-box">
    <div class="link" onclick="location.href='https://instagram.com'">📷 Instagram</div>
    <div class="link" onclick="location.href='https://open.kakao.com'">💬 오픈카톡</div>
    <div class="link" onclick="location.href='https://youtube.com'">🎬 YouTube</div>
    <div class="link" onclick="location.href='mailto:example@email.com'">✉️ Email</div>
  </div>
</div>

</body>
</html>

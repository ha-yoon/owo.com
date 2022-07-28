<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="utf-8">
  <title>LOGIN</title>
  <title>Hello~ ha-yooni Repository 에 오신 것을 환영합니다~♥</title>
</head>
<body>
  <form method="post" action="check_login.php" class="loginForm">
    <h2>Login</h2>
    <div class="idForm">
      <input type="text" name="id" class="id" placeholder="Username">
    </div>
    <div class="passForm">
      <input type="password" name="pw" class="pw" placeholder="Password">
    </div>
    <button type="submit" class="btn" onclick="button()">
      LOGIN
    </button>
    <div class="bottomText">
      <a href="/member/member.php">회원가입 하시겠습니까?</a>
      <a href="#">Sign up</a>
    </div>
  </form>
</body>
</html>

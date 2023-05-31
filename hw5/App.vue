<template>

  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>蝦皮購物 - 登入</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
  <main>
    <!-- 中間部分，包括表單和其他內容 -->
    <img src="未命名設計.png" alt="image" border="0">
    <div class="container">
      <div class="form-container">
        <form action="" method="POST">
          <div id="enter">登入</div>
          <div class="form-group">
            <label for="email"></label>
            <input type="email" id="email" name="email" placeholder="  電話號碼/使用者名稱/Email" required>
          </div>
          <div class="form-group">
            <label for="password"></label>
            <input type="password" id="password" name="password" placeholder="  密碼"required>
          </div>
          <div class="form-group">
            <button type="submit">登入</button>
          </div>
          <div class="form-group">
            <a  href="https://shopee.tw/buyer/reset">忘記密碼</a>
            <a  href="https://165.npa.gov.tw/#/" class="sms-login">使用簡訊登入</a>
          </div>
          <img src = "螢幕擷取畫面 2023-04-25 153005.png">
        </form>
      </div>
    </div>
  </main>

  </body>
  </html>

</template>

<script>
export default {
  name: "App"
}
</script>

  <style scoped>
  main {
    position: relative;
  }
  main img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .container {
    position: absolute;
    top: 8%;
    left: 55%;

  }
  form {
    border-radius: 5px;
    background-color: #fff;
    padding: 30px;
    width: 300px;
    height: 350px;
    margin: 10px;
    border: 1px solid #fff;
  }
  label {
    font-size: 20px;
    width: 400px;
    height: 60px;
  }

  input {
    font-size: 15px;
    padding:3px;
    width: 270px;
    height: 30px;
    margin:10px;
    border: 1px solid rgba(0, 0, 0, 0.2); /* 將邊框改為透明灰色 */
  }
  input::placeholder {
    color: rgba(0, 0, 0, 0.3); /* 將顏色設置為透明灰色 */
  }
  button {
    background-color: #f2816c;
    color: white;
    padding:10px;
    margin:10px;
    width:270px;
    height:50px;
    font-size: 15px;
    border-color: white;
    border-radius: 5px;
  }
  #enter{
    font-size: 20px;
  }
  .form-group a {
    text-decoration: none; /* 取消下劃線 */
    color: #0055a9; /* 修改文字顏色 */
    font-size: 13px;
  }
  .form-container img {
    margin:15px;
    width: 270px;
    height: auto;
    object-position: center;
  }
  .sms-login {
    position: absolute;
    top: 253px;
    right: 40px; /* 修改右側距離 */
  }


</style>
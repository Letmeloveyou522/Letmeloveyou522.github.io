<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link href="https://hangeul.pstatic.net/hangeul_static/css/maru-buri.css" rel="stylesheet">

<title>보안 - 로그인</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #00462A;
    }
    .container {
        width: 400px;
        margin: 100px auto;
        background-color: rgba(255, 255, 255, 0.8); /* 반투명한 회색 배경 */
        padding: 20px;
        border-radius: 5px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  	font-family: 'MaruBuri';
    }
    h1 {
        text-align: center;
    }
    .input-group {
        margin: 30px auto;
    }
    .input-group label {
        display: block;
        margin-left: 15px;
        margin-bottom: 15px;

    }
    .input-group input {
        width: 90%;
        padding: 10px;
        border-radius: 20px;
        border: 1px solid #ccc;
   font-family: 'MaruBuri';
    }
    .input-group input[type="submit"] {
        background-color: #4caf50;
        color: #fff;
        cursor: pointer;
        border: none;
   font-family: 'MaruBuri';
    }
    .input-group input[type="submit"]:hover {
        background-color: #45a049;
    }
</style>
</head>
<body>

<div class="container">
    <h1>보안 - 로그인</h1>
    <form action="#" method="post">
        <div class="input-group">
            <label for="username">아이디:</label>
            <input type="text" id="username" name="username" required>
        </div>
        <div class="input-group">
            <label for="password">비밀번호:</label>
            <input type="password" id="password" name="password" required>
        </div>
        <div class="input-group">
            <input type="submit" value="로그인">
        </div>
    </form>
</div>

</body>
</html>

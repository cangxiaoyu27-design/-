# -
特別育成対象者、記録ファイル
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>ACCESS RESTRICTED</title>
</head>
<body style="background:black; color:white; text-align:center; margin-top:20vh;">

<h2>PUBLIC SAFETY INTERNAL DATABASE</h2>
<p>ACCESS RESTRICTED</p>

<input type="password" id="pw" placeholder="認証コード">
<br><br>
<button onclick="check()">認証</button>

<p id="msg"></p>

<script>
function check() {
  const password = "BESTAGENT"; // 
  const input = document.getElementById("pw").value;

  if (input === password) {
    window.location.href = "[https://ここに飛ばしたいURL](https://www.notion.so/2c9e9cb506cf8094aee8dcd6a197bab5?source=copy_link)";
  } else {
    document.getElementById("msg").innerText = "ACCESS DENIED";
  }
}
</script>

</body>
</html>

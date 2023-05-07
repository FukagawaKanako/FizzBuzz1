# FizzBuzz1
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>FizzBuzz問題</title>
</head>

<body>
<p>
この下にJavaScriptを使った回答を表示
</p>

<script>
for (var i = 1; i <= 20; i++) {
  if (i % 3 == 0 && i % 5 == 0)
    console.log("Fizz,Buzz");
  else if (i % 3 == 0)
    console.log("Fizz");
  else if (i % 5 == 0)
    console.log("Buzz");
  else  // iが3の倍数でも5の倍数でもない
    console.log(i);
}
</script>

</body>
</html>

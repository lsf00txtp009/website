##将按下的按键显示在页面上
```
<html>
<head>
<title>将按下的按键显示在页面上</title>
<script language="javascript">
<!--
  str = "";
  function showkey(){
    asc = event.keyCode;
    key = String.fromCharCode(asc);
    str += key;
    txt.innerHTML = str;
  }
  document.onkeypress=showkey;
-->
</script>
</head>
<body>
将按下的按键显示在页面上
<div id="txt"></div>
</body>
</html>
```

##javascript中的<!--// -->作用
```
这个问题我之前也遇到过，这是为了兼容不识别javascript的旧浏览器。
因为如果浏览器能不识别javascript，就会把javascript代码直接输出到页面中，
加了<!-- //-->可以防止这种情况，浏览器就会将其当作注释。
```

##扩充，输入制定字符执行命令
···
<html>
<head>
<title>将按下的按键显示在页面上</title>
<script language="javascript">
<!--
  str = "";
  function showkey(){
    asc = event.keyCode;
    key = String.fromCharCode(asc);
    str += key;
    txt.innerHTML = str;

    if (str=="qweqwe"){
    alert("you got me!");
    window.open("http://www.w3schools.com");
    }
    if (str.length==10){
    str="";
    }
  }
  document.onkeypress=showkey;
-->
</script>
</head>
<body>
将按下的按键显示在页面上
<div id="txt"></div>
</body>
</html>
···

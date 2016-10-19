JavaScript basic – Exercises and Solutions
=====
### Simple Javascript Exercises

**Exercise #1**

Suppose you need to go to school every day except Saturday and Sunday. Write a
code, where you will input today’s date number and the web page will show you
whether you need to go to school or not.

**Solution**
```<html>
<head>
<title>test</title>
</head>
<body>
<script type="text/javascript">
switch (new Date().getDay()) {
    case 0:
        day = "Sunday";
		document.write ("You don't need to go to school");
        break;
    case 1:
        day = "Monday";
		document.write ("You need to go to school");
        break;
    case 2:
        day = "Tuesday";
		document.write ("You need to go to school");
        break;
    case 3:
        day = "Wednesday";
		document.write ("You need to go to school");
        break;
    case 4:
        day = "Thursday";
		document.write ("You need to go to school");
        break;
    case 5:
        day = "Friday";
		document.write ("You need to go to school");
        break;
    case 6:	
        day = "Saturday";
		document.write ("You don't need to go to school");
}
</script>
</body>
</html>
```

**Exercise #2**

Consider that you have a garden and you water all the plants on even days of the
month. Write a code that will show you whether you will water your plants on that
day.

**Solution**
```<html>
<html>
<head>
<title>test</title>
</head>
<body>
<script type="text/javascript">
 var d = new (Date);
 if (d%2) {
 alert("You need to water plants");
 } else {
 alert ("You don't need to water plants");
 }
 </script>
</body>
</html>
```

**Exercise #3**

Write a code that will print all the even numbers from 2 to 500.

**Solution**
```<html>
<head>
<title>test</title>
</head>
<body>
<script type="text/javascript">
 var num;
 for (num=2; num<=500; num++){
 if ((num%2)==1) {
 document.write (num+ "<br>")
 }
 }
 </script>
</body>
</html>
```

**Exercise #4**

Write a code that will print all the odd values from 1 to 600 using the while loop.

**Solution**
```<html>
<head>
<title>test</title>
</head>
<body>
<script type="text/javascript">
var num = 1;
while (num <= 600) {
if (num%2==0) {
document.write(num + "<br>");
num++;
}
}
 </script>
</body>
</html>
```

**Exercise #5**

Write a code that will print the following output:

5 x 1 = 5

5 x 2 = 10

5 x 3 = 15

5 x 4 = 20

5 x 5 = 25

5 x 6 = 30

5 x 7 = 35

5 x 8 = 40

5 x 9 = 45

5 x 10 = 50

**Solution**
```<html>
<head>
<title>test</title>
</head>
<body>
<script type="text/javascript">
var x = 5,
    y = 1;
while (y <= 10) {
  z = x * y;
  document.write(x + "x" + y + "=" + z + "<br>");
  y++;
}
</script>
</body>
</html>
```


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

# To-print-Happy-Birthday-many-times-as-the-age-of-the-person
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
        
    <script>
        function fun1()
{ 
    var value= prompt("Enter the marks:");
    for (let i = 1; i <=value; i++) 
    {
        document.write(+i+"Happy birthday to you");
        document.write("<br>");
    }
}
    </script>
    <input type="button" name="Button" id="B1" value="Button" onclick="fun1()">
</body>
</html>

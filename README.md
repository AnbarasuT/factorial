# factorial
sam
<!DOCTYPE html>

<html>
<head>
    <title>Page Title</title>
    <script>
        function ready() {
            var n=1;
            var f = 1;
            for(var i=n;i>1;i--){
                f = f*i;
            }
            document.write(n+" "+"factorial is"+" "+f);
            
        }
    </script>
</head>

<body onload="ready()">



</body>
</html>

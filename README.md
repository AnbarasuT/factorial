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



Fibonacci:
===============



<!DOCTYPE html>

<html>
<head>
    <title>Page Title</title>
    <script>
        function ready() {
            var a=0,b=1,c;
            for(var i=3;i<=5;i++){
                c= a+b;
                a =b;
                b=c;
                document.write(c,"<br/>");
            }
            
        }
    </script>
</head>

<body onload="ready()">



</body>
</html>



palindrome
==============


<!DOCTYPE html>

<html>
<head>
    <title>Page Title</title>
    <script>
        function ready() {
          var revstr = "";
          var str = "madam";
          for(var i=str.length; i>=0;i--){
            revstr = revstr + str.charAt(i);  
          }
          if (revstr == str) {
            document.write('palindrome');
          }
          else{
            document.write('not palindrome')
          }
        }
    </script>
</head>

<body onload="ready()">



</body>
</html>




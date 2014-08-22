.contxt
=======
<!doctype html>  
<html lang="en">  
<head>  
  <meta charset="utf-8">  
  <title>context demo</title>  
  <script src="//code.jquery.com/jquery-1.10.2.js"></script>  
</head>  
<body>  
   
Context: <ul></ul>  
   
<script>  
$( "ul" )  
  .append( "<li>" + $( "ul" ).context + "</li>" )  
  .append( "<li>" + $( "ul", document.body ).context.nodeName + "</li>" );  
</script>  
   
</body>  
</html>  

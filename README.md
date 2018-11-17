<!doctype html>
<html>
<head>
	<meta charset="utf-8">
    
    <!-- Poner un título para el sitio en la etiqueta siguiente: -->
	<title></title>
    
    <link href="main.css" rel="stylesheet" type="text/css">

    <!-- Dejar las siguientes 6 etiquetas como están son las que se encargan de hacer el desplazamiento en el sitio -->
	<script type="text/javascript" src="http://code.jquery.com/jquery-1.9.1.js"></script>
    
    <script type="text/javascript" src="jquery.onepage-scroll.js"></script>
    
    <link href='onepage-scroll.css' rel='stylesheet' type='text/css'>
    
    
    
    <meta name="viewport" content="initial-scale=1, width=device-width, maximum-scale=1, minimum-scale=1, user-scalable=no">
    
	<script>
	  $(document).ready(function(){
      $(".main").onepage_scroll({
        sectionContainer: "section",
        responsiveFallback: 600,
        loop: true
      });
		});
		
	</script>
    
    
</head>
    
    
<body>
  <div class="wrapper">
	  <div class="main">
          
          
	  <!-- Pueden empezar a editar desde este punto. En medio de las etiquetas "section" pueden poner la información que quieran y se vera como un pantallazo en el sitio con desplzamiento vertical. Pueden duplicar cada una de estas páginas si desean un desplazamiento vertical más extenso. -->
          
      <section class="page1">
          <h1>Hola Mamá</h1>
      </section>
	    
	    <section class="page2">
      </section>
	    
	    <section class="page3">
      </section>
          
          <section class="page4">
      </section>
    </div>
  </div>
</body>
</html>

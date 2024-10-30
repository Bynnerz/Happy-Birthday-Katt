
<html>
<head>
	<title>Happy Birthday/title>

	<style type="text/css">
		.particula {
			width: 8px;
			height: 8px;
			background: black;
			border-radius: 50%;
			position: absolute;
		}

		.particula[data-padre="false"] {
			width: 5px;
			height: 5px;
		}

		body, html {
			overflow-y: hidden;
			overflow-x: hidden;

			background: black;
		}

		#fondo {
			position: absolute;
		    bottom: -100px;
		    opacity: .4;
		}
	</style>
	<link rel="stylesheet" href="style.css"
</head>
<body>
	<!--div class="particula" data-velocidad-y="0" data-velocidad-x="0" data-padre="true" /-->

	<div class="galeria">

	
	 	<img src="imagenes/rosas.jpg" id="rosas" alt="" class="img-1"/>

		<img src="imagenes/foto.jpg" id="foto" alt="" class="img-3"/>
	
		<img src="imagenes/felizcumpleaños.jpg" id="felizcumpleaños" alt="" class="img-2" />
		
	    

</div>

<div class="Reproductor">		
	
	
	<iframe style="border-radius:52px" src="https://open.spotify.com/embed/track/5FgPwJ7Nh2FVmIXviKl2VF?utm_source=generator&theme=0" width="50%" height="152" frameBorder="20" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
</div>
	
<script src="index.js"></script>
.galeria{

    display: flex;
    justify-content: center;

    .img-1 {

        height: 580px;
        margin-top: 1px;
        margin: 0 10px;
      
    }
    
    .img-2 {

       height: 240px;
       margin-top: 270px;
       margin: 30 10px;
       
    }
    
    .img-3 {

        height: 300px;
        margin-top: 150px;
        margin: 30 10 px;
        border-radius: 25px;
        
    }
}

.Reproductor {

    margin-left: 500px;
    
}
			


</body>
</html>

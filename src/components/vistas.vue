<!DOCTYPE html>
<html>
<head>
  <title>Slider con valores modificables</title>
  <style>
    /* Estilos para el slider */
    #slider {
      width: 300px;
    }
  </style>
</head>
<body>
	<label> industrial 34 </label>
  <input type="range" min="0" max="200" value="" id="slider"><br>

  <label> Electro 134 </label>
  <input type="range" min="0" max="200" value="" id="slider"><br>

<label> isc 150 </label>
  <input type="range" min="0" max="200" value="" id="slider">
  


  <script>
    // Función para mostrar el valor seleccionado
    document.getElementById('slider').addEventListener('input', function() {
    document.getElementById('valor').textContent = this.value;
    });
  </script>
</body>
</html>
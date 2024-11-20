<!DOCTYPE html> 
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ADSO</title>
</head>
 <h1>FORMULARIO</h1>
    
   </p>
  <a href="#"></a>
</html>
<form>
<body>
<html>
<label for="nombre">nombre</label>
<input type="text"name="ingrese su nombre"id=nombre required parttern="[A-Z a-z]+" title="ingrese solo letras">
<br><br>
<label for="apellido">apellido</label>
<input type="text"name="ingrese su apellido"id=nombre required parttern="[A-Z a-z]+" title="ingrese solo letras">
<br><br>


<label for="color">color</label>
<input type="color"name="ingrese un color"id=color  title="ingrese un color">
<br><br>



<label for="edad">edad</label>
<input type="text"id="numero"  required title="ingrese un numero">
<br><br>



<label for="numero">numero</label>
<input type="text" id="numero" required title="ingrese un numero">

<br><br>

<label for="numero">positivo</label>
<input type="text"name="positivo"id=numero  required parttern="[0-9]+" title="ingrese un numero positivo">
<br><br>
<label for="maximo-minimo">maximo-minimo</label>
<input type="number"name="maximo-minimo" step="0.5"  min="10" max="20" value="10">
<br><br>



<label for="fecha nacimiento">fecha nacimiento</label>
<input type="date" name="fecha de nacimiento" >
<br><br>

<label for="hora">hora</label>
<input type="time" name="hora" >
<br><br>

<label for="ciudad">ciudad</label>
<select name="ciudad" id="ciudad">
<option value="ciudad1">caqueta</option>
<option value="ciudad2">bucaramanga</option>
<option value="ciudad3">estambul</option>
<option value="ciudad4">londres</option>
</select>
<br><br>

<label for="genero">genero</label>
<select name="genero" id="genero">
<option value="genero1">masculino</option>
<option value="genero2">femenino</option>
<option value="genero3">otro</option>
<option value="genero4">genero fluido</option>
</select>
<br><br>

<label for="materias">materias</label>
<select name="materias" id="materias">
<option value="materia1">HTML</option>
<option value="materia2">CSS</option>
<option value="materia3">JS</option>
<option value="materia4">JAVA</option>
<option value="materia5">PYTHON</option>
<option value="materia6">PHP</option>
</select>
<br><br>
<label for="archivos">archivo(.jpg y png):</label>
<input type="file" name="archivos" accept=".jpg-png" multiple>
<br><br>
<label for="contraseña">contraseña</label>
<input type="contraseña" name="contraseña" id="contraseña" required >
<br><br>
<input type="text" name="nombre" id="nombre" value="santiago carrillo rivera" required>
<br><br>
<button type="submit">enviar</button>
</body>
</html>
</form>

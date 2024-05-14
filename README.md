<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primer Formulario</title>
</head>
<body>
<form>
<table border="0" width="100%">
<tr>
    <th colspan="10">DATOS PERSONALES</th>
</tr>
<tr>

    <td width="25"></td>
    <td width="25"><label for="name">Nombre Completo</label></td>
    <td width="25"><input type="text" name="name" id="name"></td>
    <td width="25"></td>

</tr>

<tr>
    <td width="25"></td>
    <td width="25"><label for="name">Genero</label></td>
    
    <td width="25"></td>

</tr>
<tr>
    <td width="25"></td>
    <td colspan="2">
        <input type="radio" id="Hombre" name="Hombre"><label for="Genero">Hombre</label>
        <input type="radio" id="Hombre" name="Hombre"><label for="Genero">Mujer</label>
        <input type="radio" id="Hombre" name="Hombre"><label for="Genero">Otro</label>

        <td width="25"></td>

</tr>
<tr>
    <td width="25"></td>
    <td width="25"><label for="name">DNI</label></td>
    <td width="25"><input type="text" name="name" id="name"></td>
    <td width="25"></td>

</tr>
<tr>
    <td width="25"></td>
    <td width="25"><label for="name">Idioma</label></td>
    <td width="25"><select name="Idioma" id="Idioma" name="Lenguajes">
        <option value="Spanish">Español</option>
        <option value="English">Ingles</option>
        <option value="French">Frances</option>
    </select></td>
    <td width="25"></td>
</tr>
</table>
</form> 
</body>
</html>

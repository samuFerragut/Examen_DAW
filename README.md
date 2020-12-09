# Examen DEWS

## Samu Ferragut

4)En el código del  CRUD orientado a objetos, modifica lo necesario para que figure el símbolo del dólar a la izquierda del precio, en el listado del productos y en el detalle (read_one). Explica los cambios realizados.
`En index.php linea 114 echo "<td>{$dolar}{$price}</td>";` `En read_one linea 40 $dolar = "$"; y linea 47 $dolar = $row["$dolar"];`

5)Explica cómo se guarda la imagen de un producto en la base de datos: tipo de formato del campo, comprobaciones realizadas antes de aceptar una imágen, qué se guarda en la B.D., dónde  está la imágen, cómo recuperarla,etc.

# Examen DEWS

## Samu Ferragut

**4) En el código del  CRUD orientado a objetos, modifica lo necesario para que figure el símbolo del dólar a la izquierda del precio, en el listado del productos y en el detalle (read_one). Explica los cambios realizados.**
`En index.php linea 114 echo "<td>{$dolar}{$price}</td>";` `En read_one linea 40 $dolar = "$"; y linea 47 $dolar = $row["$dolar"];`

**5) Explica cómo se guarda la imagen de un producto en la base de datos: tipo de formato del campo, comprobaciones realizadas antes de aceptar una imágen, qué se guarda en la B.D., dónde  está la imágen, cómo recuperarla,etc.**
Al cargar la imágen lo primero que se comprueba es si es una imagen, es decir, que tenga los formatos *(png,jpg o gif)*, lo siguiente es que no exista ninguna imagen con el mismo nombre, también comprueba que no se pase de tamaño y además comprueba también que la carpeta existe
La podemos recuperar en la carpeta uploads, que es donde se guardan las imágenes al subirlas, ya que en la base de datos solo tenemos guardado el nombre de la imágen a la que se le hace referencia.

**6) En el código del CRUD orientado a objetos, el script para crear productos permite incluir una imágen del producto, pero una vez insertado, no se puede actualizar. Modifica el código para que también se pueda actualizar la imágen de un producto. Explica los cambios realizados.**

### Nombre del Servidor

<http://samu.hopto.org/html/>
O
<http://samu.hopto.org/html/ejercicios/Examen_DAW/>

### Localización del repo

<https://github.com/samuFerragut/Examen_DAW>

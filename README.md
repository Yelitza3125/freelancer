# Proyecto: Freelancer


![Freelancer ](docs/fullpage.png "Freelancer")

## Descripción del Proyecto:

El siguiente repositorio contiene la maquetación de la pagina web Bootstrap, sus secciones y contenidos. Se utilizó para su elaboración, una estructura semántica de HTML y la implementación de estilo y diseño de CCS.

## Herramientas utilizadas:

1. HTML5

2. CSS3


## Procedimiento:

### Estructura de index.html:

1. Creación de la estructura básica de HTML

2. Enlazando las fuentes tipográficas a utilizar en head.

3. Enlazando el link de fontAwesome de donde se seleccionarán los íconos.

4. Enlazando el archivo css, con la etiqueta link.

5. Inicio de la etiqueta body

6. Creación de la etiqueta header, e implementando la clase "text-uppercase", para que todo su contenido textual sea en mayúsculas y la clase "wrapper".

7. Creación de del contenedor div, con clase "nav-principal". Contiene al elemento span con clase logo, que hace referencia al logotipo "Bootstrap".

8. Creación de una lista desordenada, con clase "menu", dentro de la misma hay tres items: portfolio, about y contact.

9. Fin de header

10. Creación de la primera sección: Start y el contenedor principal con clase "container".

11. Etiqueta figure, con clase "profile" que contiene la imagen profile.

12. Creación de un contenedor div, que contiene al título h1.

13. Elemento hr con clase "line-profile", para generar una línea horizontal.

14. Creación de un contenedor con clase "star-title", conteniendo al ícono.

15. Elemento hr con clase "line-profile", para generar una línea horizontal.

16. Creación de un contenedor div, que contiene al subtítulo h3.

17. Fin de la primera sección.

18. Creación de la segunda sección: "Portfolio"

19. Creación de un contenedor div, con clase "second-title", que contiene el subtitulo h2, con el nombre de la sección.

20. Creación de una línea horizontal a través de la etiqueta hr.

21. Creación de un contenedor div, que contiene al ícono.

22. Creación de una segunda línea horizontal, con hr.

23. Creación de un contenedor div, con clase "images-container", que contiene a las 6 imágenes.

24. Creación de 6 div, uno para cada imagen, que contienen un elemento ancla y contenedor div, con el ícono zoom. Cada div principal tiene el nombre de clase correspondiente a la imagen que contienen.

25. Fin de la segunda sección.

26. Creación de la tercera sección: about.

27. Creación de un contenedor div, que contiene el subtítulo h2, con el nombre de la sección.

28. Creación de una línea horizontal a través de la etiqueta hr.

29. Creación de un contenedor div, que contiene al ícono.

30. Creación de una segunda línea horizontal, con la etiqueta hr.

31.  Creación de un contenedor div con clase "text-columns", que contiene el texto a través de la etiqueta p.

32. Creación de un botón con clase "dowload", que tiene un contenedor div, donde está la etiqueta ancla y el ícono de descarga.

33. Fin de la tercera sección.

34. Inicio de la cuarta sección: contact.

35.  Creación de un contenedor div, que contiene un subtítulo h3, con el nombre de la sección.

36.  Creación de una línea horizontal a través de la etiqueta hr.

37. Creación de un contenedor div, que contiene al ícono.

38. Creación de una segunda línea horizontal, con la etiqueta hr.

39. Creación de la etiqueta formulario, a través de la etiqueta form, que contiene en su interior  cuatro div con los elementos input y label, correspondientes a los datos solicitados al usuario.

40. Creación de la etiqueta botón del tipo "submit".

41. Cierre del elemento formulario.

42. Fin de la cuarta sección.

43. Inicio de footer.

44. Creación de un contenedor div con la clase "content", que mantiene en su interior los sub siguientes divs y sus elementos.

45. Dentro del div con clase "content", se crea un contenedor div con clase "location", que contiene un subtítulo h3 y un párrafo.

46. Dentro del div con clase "content", se crea un contenedor div con clase "around", que contiene un subtítulo h3 y 5 div que contienen los íconos de las redes sociales facebook, google, twitter, linkedin y drible.

47. Dentro del div con clase "content", se crea un contenedor div con clase "about-freelancer", que contiene un subtítulo h3 y un párrafo.

48. Dentro del div con clase "content", se crea un contenedor div con clase "copyright", que contiene un párrafo.

49. Cierre del contenedot con clase "content".

50. Fin de footer.

51. Cierre de la etiqueta body.

52. Cierre de la etiqueta html.



### Implementación de la hoja de estilo en el archivo main.css

1. Reseteando los valores por defecto del archivo, con la propiedad box-sizing border box, y el margin y padding a 0.

2. A través del selector de clase, se establece la clase text-uppercase, con la propiedad text-transform a uppercase, para que cada elemento que contenga esa clase, cambie el texto a mayúsculas.

3. Mediante un selector de clase, se establece "wrapper", a un ancho de 90%, un ancho máximo de 1000px, un margin auto para centrarlo y un overflow hidden, para que contenga a los elementos flotados.

4. Estilo a la etiqueta header: color de fondo, posición fixed, y un ancho al 100% del body. Se le da la propiedad overflow auto para que contenga a los elemtos flotados; un z-index de 1000, para que no ocurra superposición de elementos y un top 0, para que inicie desde el inicio de la pantalla del navegador.

5. Estilo al navegador principal, con la propiedad float left, para que se ubique al lado izquierdo de la pantalla.

6. Estilo al elemento con clase "logo", como es un texto se establce su tipo y tamaño de fuente. Se aplica un margin-left, para separarlo del borde de la pantalla.

7. Estilo al elemento con clase "menu", con la propiedad float right, para que situen a la derecha de la página. Se establecen los márgenes y el line-height del mismo alto que el contenedor para centrar los elementos.

8. Estilo a la etiqueta ancla que está dentro de header y se cambia su estilo por defecto.

9. Estilo a cada item del menu de header, mediante la propiedad display inline y un margen de 10px, para separar cada item. Se establece la fuente tipográfica Montserrat.

10. Estilo al pseudoclase hover de los elementos ancla, para que cambien el color al pasar el cursor.

11. Fin de header.

12. Inicio de la primera sección start.

13. Al contenedor principal con clase "star", se le aplica un color de fondo, un margin superior y un ancho de 100%.

14. Creación del estilo container por medio de un selector de clase, con un margin auto que centra el contenido, un ancho de 100% y la propiedad overflow, cuando se use la porpiedad float.

15. Estilo al contenedor de la imagen profile. Centrado de la imagen.

16. Estilo al título h1, con el color del texto en blanco, el tipo de fuente Montserrat y un tamaño de 70px.

17. Estilo a hr, para generar una línea que va debajo del título. Se le da un ancho del 7% del elemento más cercano, en este caso de h1.

18. Estilo al icono star con la propiedad position relative, es desplazada al centro. Se cambia su color a blanco.

19. Con el selector id, se da estilo al subtítulo h3. Se determina la tipografía "Lato" y un tamaño de fuente de 30px.

20. Fin de la primera sección.

21. Inicio de la segunda sección: portfolio.

22. Estilo al subtítulo h2, a través de la implementación de la fuente Montserrat, color y tamaño a 50px. Se establece un espacio entre el contenido y el borde para separar el elemento de la sección anterior.

23. Mediante la implementación de estilo al elemento hr, se crean las dos líneas que van debajo del subtítulo. Se aplica la propiedad display inline-block, para que puedan alinearse.

24. Estilo al ícono star y mediante la propiedad position relative, se coloca entre las dos líneas generadas anteriormente.

25. Se aplica estilo al contenedor de la imágenes, mediante el selector de clase "images-container". Se determina un ancho del 70% de la sección. Se divide en 3 columnas, separadas por un margen del 15%.

26. Estilo a cada contenedor de la imágenes de la sección. Se establece un ancho del 100% y un alto de 250px. La imagen se posiciona por medio de la propiedad background-image de tipo cover, para que la imagen se muestre completa. 

27. Las imágenes son separadas entre sí, aplicando un margin-bottom de 25px.

28. Estilo al contenedor del ícono zoom, que se ve al poner el cursor sobre cada imagen. Se le da un tamaño igual al de las imágenes. Se establece la propiedad visibility hidden, para que solo se vea al aplicar hover.

29. Estilo al ícono zoom. Es centrando mediante un interlineado del mismo tamaño que la altura de su contenedor.

30. Estilo de hover de las imágenes, se cambia el valor la propiedad de visibility de hidden a visible.

31. Fin de la segunda sección.

32. Inicio de la tercera sección about

33. Estilo al contenedor principal, aplicando un color de fondo.

34. Estilo al subtítulo h2, cambio de color a blanco, tipografía Montserrat y un tamaño de 50px. Se aplica un padding-top, para separarlo del final de la primera sección.

35. Mediante la implementación de estilo al elemento hr, se crean las dos líneas que van debajo del subtítulo. Se aplica la propiedad display inline-block, para que puedan alinearse.

36. Estilo al ícono star y mediante la propiedad position relative, se coloca entre las dos líneas generadas anteriormente.

37. División del contenedor de la sección, en dos columnas con un 45% del ancho de la sección. Se establece una separación entre las columnas de 15%. Para centrar el contenedor, se aplica margin auto.

38. Estilo a los párrafos contenidos dentro de cada columna. Se utiliza la fuente Lato, un tamaño de 20px y el texto es alineado a la izquierda. Se aplica text-transform con el valor de none, para cambiar el estilo anterior que cambiaba las letras a mayúsculas.

39. Estilo al botón con clase "dowload", se quitan los valores por defecto y se determina un color de fondo y border-radius para curvar los lados. El padding aplicado, separa el contenido de los bordes.

40. Estilo al ícono del botón dowload. Se cambian el color y se le da un tamaño de 20px y un padding de 2px, para separarlo del texto.

41. Se da estilo al elemento ancla, cambiando los valores por defecto, se quita el subrayado y se determina una nueva fuente tipográfica: Lato.

42. Se establece la pseudo clase hover, para que cambie el color de fondo del botón al pasar el cursor.

43. Se establece la pseudo clase hover al ícono, para que cambie el color al pasar el cursor.

44. Se establece la pseudo clase hover, para que cambie el color del texto del elemento ancla, al pasar el cursor.

45. Fin de la tercera sección.

46. Inicio de la cuarta sección: contact.

47. Estilo al subtítulo h2, tipo de fuente Montserrat y un tamaño de 50px, se establece un padding-top, para separarlo del final de la tercera sección.

48. Se establece el mismo estilo de líneas y el ícono estrella de la sección dos y tres.

49. Estilo al elemento form. Un ancho del 50% de la sección, con un margin auto para centrarlo y el texto desplazado a la izquierda. Con la propiedad padding y margin se establace la separación de los otros elementos.

50. Estilo al contenedor del elemento form, solo se da color al borde inferior del contenedor.

51. Se establece la altura del contenedor message, ya que contiene varias líneas. 

52. Se aplica estilo a la etiqueta input, se quitan los valores por defecto con la propiedad outline con valor none. Se hacen cambios de tipografía a Lato y se cambia el color.

53. Estilo al botón send (envío), del formulario. Se establece un color de fondo y de tipografía, cambiando los valores por defecto. El borde es redondeado mediante la propiedad border-radius.

54. Mediante la pseudo clase hover, se cambia el color de fondo del botón cuando pasa el cursor.

55. Fin de la cuarta sección

56. Inicio de footer

57. Estilo al contenedor footer, estableciendo el color de fondo de la tipografía y un padding-top, para separar su contenido de la anterior sección.

58. Se establece el ancho del contenedor "content", al 90% del footer. Se centra  con la propiedad margin auto y se aplica overflow para contener a las etiquetas p, con propiedad float left.

59. Estilo al subtítulo h3. Se aplica la tipografía Montserrat, se aumenta su tamaño a 25px y un margin-bottom para separarlo de los elementos que seguirán.

60. Estilo a la etiqueta párrafo. Se aplica la tipografía Lato y un tamaño para las letras de 20px. Se quita la propiedad que cambia el texto a mayúsculas.

61. Se aplica el estilo a los contenedor con clase "location y "around". Se determina la propiedad float left, un ancho del 22% del contenedor y una separción entre cada contenedor de 50px.

62. El contenedor location, aumenta su margin-left, para centrar el contenido del footer.

63. Se cambia el color del suntítulo h3, dentro del div con clase "around".

64. Cada contenedor con clase "link" que está dentro de un div con clase "around", tiene una propiedad de display inline-block, para todos los íconos de las redes sociales en una sola línea. Se establece border-radius al 100% para generar un cículo.

65. Se establece el estilo a los elementos ancla dentro del div con clase "link" , cambiando el color a blanco y quitando el estilo por defecto.

66. Por medio de la pseudo clase hover, se camba el color de fondo de cada ícono y el color de fuente.

67. Mediante la pseudo clase hover, se cambia el color de fondo del contenedor con clase "link", cada vez que pase el cursor.

68. Mediante la pseudo clase hover, se cambia el color a los elementos ancla, que estén contenedor con clase "link", cada vez que pase el cursor.

69. Se aplica estilo al div con clase "about-freelancer", a un ancho de 27%. La propiedad float left y un text-align center para centrar el texto.

70. Se establece el estilo a los elemetos ancla dentro del contenedor "about-freelancer", cambiando los valores por defecto.

71. Por medio de la pseudo clase hover, se establace un subrayado sobre lo elementos ancla, que estén dentro del contenedor con clase "about-freelancer".

72.  Estilo al elemento con id "copyright". Se aplica la propiedad clear both, para separarlo de los elementos flotantes y se ubique en la parte inferior. Se centra el contenido mediante la propiedad position relative. 

73. Se determina un tamaño de fuente de 15px, para el elemento párrafo ubicado dentro del contenedor con id copyright.



### Estructura de los archivo html de las imágenes de la sección portfolio:

1. Estructura básica de html.

2. Enlazando el url de la fontAwesome mediante la etiqueta link.

3. Enlazando las fuentes tipográficas mediante la etiqueta link.

4. Enlazando el archivo portfolio.css, mediante la etiqueta link.

5. Inicio de la etiqueta body.

6. Creación de un contenedor div con clase "cross" que contiene un elemento ancla que redirecciona a la página principal y que además contiene el ícono de una cruz.

7. Creación de un contenedor div que contiene un elemento h1.

8. Creación de un elemento hr, para generar una línea horizontal debajo de h1.

9. Creación de un contenedor div con clase "star-cabin", que contiene el ícono estrella.

10. Creación de un elemento hr, para generar una línea horizontal debajo de h1.

11. Craeción del contenedor figure, que contiene la etiqueta img, con cada imagen de portfolio. El destino de referencia de la etiqueta cambian según la imagen.

12. Fin del contenedor figure.

13. Creación de un div con clase "text", que contiene un elemento párrafo.

14. Creación de un div con class "details", que contiene tres párrafos. Cada uno a su vez, contiene un elemento ancla.

15. Creación de un botón con clase "portfolio"; contiene un alemento ancla, que redirecciona a la página principal.

16. Fin de body.

17. Cierre de la etiqueta html.



### Implementación de la hoja de estilo en el archivo portfolio.css

1. Reseteando la hoja de estilo, a través de la propiedad box-sizing border-box y estableciendo el padding y el margin a 0.

2. Se aplica al contenedor del ícono cross, la propiedad overflow auto, para contener al elemento flotado.

3. Al ícono croos, se le aplica la propiedad float left, para que se ubique al lado izquierdo superior de la página. Se cambia su color y el tamaño a 50px.

4. Se aplica estilo al elmento h1, su estilo de fuente es MOntserrat y se alinea al centro mediante la propiedad text-align, con el valor center.

5. A los elementos hr y al ícono star, se les cambia de posición con la propidad position relative.

6. Al alemento hr, se le da un ancho del 7% de su contenedor, y se le da un color igual al del título h1.

7. Al ícono star, se le aplica la propiedad display inline-block para que se mantenga en línea con los elementos hr. Se le da un z-index 20, para prevenir la superposición. El color se cambia para que sea el mismo que el del título h1.

8. Se aplica el estilo al contenedor figure, determinando su ancho y alto. Con la propiedad position relative, es centrado.

9. Se establece el ancho de la imagen al 100% de su contenedor, figure.

10. Se establece el tipo de fuente "Lato" para los textos.

11. A cada elemento con la clase "text", se establece un tamaño de 20px, un margin auto para centrarlo y un ancho del 45% de su contenedor.

12. Al contenedor con clase "details", se le determina un ancho del 25% y también un margin auto para centrarlo. La propiedad text-align, centrará el texto.

13. Se establecen los estilos comunes de los elementos ancla. Se quitan los valores por defecto.

14. Se da estilo al botón, cambiando sus valores por defecto. Se le da un borde redondeado con border-radius. Un padding de 10px, para agrandar el contenido y se cambia el color de fondo.

15. Se da estilo a los elementos ancla y al ícono contenidos dentro del botón. Se cambia el estilo por defecto del elemento ancla y establece un color blanco para el ícono y un tamaño de 15px.
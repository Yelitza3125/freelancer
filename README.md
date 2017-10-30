# Proyecto: Freelancer


![Freelancer ](assets/docs/fullpage.png "Freelancer")

## Descripción del Proyecto:

El siguiente repositorio contiene la maquetación de la pagina web Bootstrap, sus secciones y contenidos. Se utilizó para su elaboración, una estructura semántica de HTML y la implementación de estilo y diseño de CCS.

## Procedimiento:

### Estructura de index.html:

1. Creación de la estructura básica de HTML

2. Enlazando las fuentes tipográficas a utilizar en head.

3. Enlazando el link de fontAwesome de donde se seleccionarán los íconos.

4. Enlazando el archivo css, con la etiqueta link.

5. Inicio de la etiqueta body

6. Creación de la etiqueta header, e implementando la clase "text-uppercase", para que todo su contenido textual sea en mayúsculas.

7. Creación de del contenedor div, con clase nav-principal. Contiene al elemento span con clase logo, que hace referencia al logotipo "Bootstrap".

8. Creación de una lista desordenada, con clase "menu", dentro de la misma hay tres items: portfolio, about y contact.

9. Fin de header

10. Creación de la primera sección: Start y el contenedor principal con clase container.

11. Etiqueta figure, que contiene la imagen profile principal.

12. Creación de un contenedor div, que contiene al título h1.

13. Creación de un contenedor con clase "star-title", conteniendo al ícono.

14. Creación de un contenedor div, que contiene al subtítulo h3.

15. Fin de la primera sección.

16. Creación de la segunda sección: "Portfolio"

17. Creación de un contenedor div, con clase "second-title", que contiene el subtitulo h2, con el nombre de la sección.

18. Creación de una línea horizontal a través de la etiqueta hr.

19. Creación de un contenedor div, que contiene al ícono.

20. Creación de una segunda línea horizontal.

21. Creación de un contenedor div, con clase "images-container", que contiene a las 6 imágenes.

22. Creación de 6 div, uno para cada imagen, que contienen un elemento ancla y contenedor div, con el ícono zoom. Cada div principal tiene el nombre de clase correspondiente a la imagen que contienen.

23. Fin de la segunda sección.

24. Creación de la tercera sección: about.

25. Creación de un contenedor div, que contiene el subtítulo h2, con el nombre de la sección.

26. Creación de una línea horizontal a través de la etiqueta hr.

27. Creación de un contenedor div, que contiene al ícono.

28. Creación de una segunda línea horizontal.

29.  Creación de un contenedor div con clase "text-columns", que contiene el texto a través de la etiqueta p.

30. Creación de un botón con clase "dowload", que tiene un contenedor div, donde está la etiqueta ancla y el ícono de descarga.

31. Fin de la tercera sección.

32. Inicio de la cuarta sección: contact.

33.  Creación de un contenedor div, que contiene un subtítulo h3, con el nombre de la sección.

34.  Creación de una línea horizontal a través de la etiqueta hr.

35. Creación de un contenedor div, que contiene al ícono.

36. Creación de una segunda línea horizontal.

37. Creación de la etiqueta formulario, a través de la etiqueta form, que contiene en su interior  cuatro div con los elementos input y label, correspondientes a los datos solicitados al usuario.

38. Creación de la etiqueta botón del tipo "submit".

39. Cierre del elemento formulario.

40. Fin de la cuarta sección.

41. Inicio de footer.

42. Creación de un contenedor div con la clase "content", que mantiene en su interior los sub siguientes divs y sus elementos.

43. Dentro del div con clase "content", se crea un contenedor div con clase "location", que contiene un subtítulo h3 y un párrafo.

44. Dentro del div con clase "content", se crea un contenedor div con clase "around", que contiene un subtítulo h3 y 5 div que contienen los íconos de las redes sociales facebook, google, twitter, linkedin y drible.

45. Dentro del div con clase "content", se crea un contenedor div con clase "about-freelancer", que contiene un subtítulo h3 y un párrafo.

46. Dentro del div con clase "content", se crea un contenedor div con clase "copyright", que contiene un párrafo.

47. Cierre del contenedot con clase "content".

48. Fin de footer.

49. Cierre de la etiqueta body.

50. Cierre de la etiqueta html.


### Implementación de la hoja de estilo en el archivo main.css

1. Reseteando los valores por defecto del archivo, con la propiedad box-sizing border box, y el margin y padding a 0.

2. A través del selector de clase, se establece la clase text-uppercase, con la propiedad text-transform a uppercase, para que cada elemento que contenga esa clase, cambie el texto a mayúsculas.

3. Estilo a la etiqueta header: color de fondo, posición fixed, y un ancho al 100% del body. Se le da la propiedad overflow auto para que contenga a los elemtos flotados; un z-index de 1000, para que no ocurra superposición de elementos y un top 0, para que inicie desde el inicio de la pantalla del navegador.

4. Estilo al navegador principal, con la propiedad display inline-block.

5. Estilo al elemento con clase "menu", con la propiedad float right, para que situen a la derecha de la página. Se establecen los márgenes y el line-height del mismo alto que el contenedor para centrar los elementos.

6. Estilo a la etiqueta a que está dentro de header y cambiando su estilo por defecto.

7. Estilo al elemento con clase "logo", como es un texto se establce su tipo y tamaño de fuente. 

8. Estilo a cada item del menu de header, mediante la propiedad display inline y un margen de 10px, para separar cada item. Se establece la fuente tipográfica Montserrat.

9. Estilo al pseudoclase hover de los elementos ancla.

10. Fin de header.

11. Inicio de la primera sección start.

12. Al contenedor principal con clase "star", se le aplica un color de fondo, un margin superior y un ancho de 100%.

13. Creación del estilo container, con un margin auto que centra el contenido, un ancho de 100% y la propiedad overflow, cuando se use la porpiedad float.

14. Estilo al contenedor de la imagen profile. Centrado de la imagen.

15. Estilo al título h1, con el color del texto en blanco, el tipo de fuente Montserrat y un tamaño de 70px.

16. Estilo al pseudo elemeto after, que va después de h1; para generar una línea.

17. Estilo al icono star con la propiedad position relative, es desplazada al centro.

18. Estilo al pseudo elemeto after, que va después del ícono star; para generar una línea.

19. Fin de la primera sección.

20. Inicio de la segunda sección: portfolio.

21. Estilo al subtítulo h2, a través de la implementación de la fuente Montserrat, color y tamaño a 50px. Se establece un espacio entre el contenido y el borde para separar el elemento de la sección anterior.

22. Mediante la implementación de estilo al elemeto hr, se crean las dos líneas que van debajo del subtítulo. Se aplica la propiedad display inline-block, para que puedan alinearse.

23. Estilo al ícono star y mediante la propiedad position relative, se coloca entre las dos líneas generadas anteriormente.

24. Estilo a cada contenedor de la imágenes de la sección. Se establece un ancho de 350px y un alto de 250px. La imagen se posiciona por medio de la propiedad background-image, del tipo cover, para que la imagen se muestre completa. 

25. Las imágenes son separadas aplicando un margin-bottom de 25px.

26. Estilo al contenedor del ícono zoom, que se ve al poner el cursor sobre cada imagen. Se le da un tamaño igual al de las imágenes. Se establece la propiedad visibility hidden, para que solo se vea al aplicar hover.

27. Estilo al ícono zoom. Es centrando mediante un interlineado del mismo tamaño que la altura de su contenedor.

28. Estilo de hover de las imágenes, se cambia el valor la propiedad de visibility a visible.

29. Fin de la segunda sección.

30.
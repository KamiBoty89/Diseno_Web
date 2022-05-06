## 5. LENGUAJE CSS

Objetivo: Verificar el dominio de implementación de estilos (CSS) sobre el código html de
una página web.

Indicaciones: Pedir subrayar, encerrar en un círculo, o escribir la respuesta que
consideren correcta.

Preguntas:

1. ¿Qué significa CSS? (valor 0.25)

          a) Cascading Style Sheets
          
2. ¿Cuál es el HTML correcto para hacer referencia a una hoja de estilo externa?
(valor 0.25)

          b) <link rel="stylesheet" type="text/css" href="style.css">
          
3. ¿En qué parte de un documento HTML es el lugar correcto para hacer referencia a
una hoja de estilo externa? (valor 0.25)

          a) En la sección <head>
          
 4. ¿Qué etiqueta HTML se utiliza para definir una hoja de estilo interna? (valor 0.25)
 
          c) <style>
          
 5. ¿Qué atributo HTML se usa para definir estilos en línea? (valor 0.25)

          a) font
          b) styles
          c) class
          
 6. ¿Cuál es la sintaxis CSS correcta? (valor 0.25)

          b) body {color: black;}
          
 7. ¿Cómo se inserta un comentario en un archivo CSS? (valor 0.25)

          a) /* esto es un comentario */
          
8. ¿Qué propiedad se utiliza para cambiar el color de fondo? (valor 0.25)

          b) background-color
          
9. ¿Cómo se agrega un color de fondo para todos los elementos h1 (valor 0.25)
  
          b) h1 {background-color:#FFFFFF;}
  
10. ¿Qué propiedad CSS se usa para cambiar el color del texto de un elemento? (valor 0.25)
  
          c) color
  
 11. ¿Qué propiedad CSS controla el tamaño del texto? (valor 0.25
  
          c) font-size
  
 12. ¿Cuál es la sintaxis CSS correcta para poner en negrita todos los elementos p?(valor 0.25)
  
          c) p {font-weight:bold;}
  
13. ¿Cómo hacer que cada palabra en un texto comience con una letra mayúscula? (valor 0.25)
  
          b) text-transform:capitalize
  
14. ¿Qué propiedad se utiliza para cambiar la fuente de un elemento? (valor 0.25)
  
          b) font-family
  
15. ¿Cómo pones el texto en negrita? (valor 0.25)
  
          c) font-weight:bold;
  
16. ¿Cómo se muestra un borde como este? (valor 0.25)

El borde superior = 10 píxeles

El borde inferior = 5 píxeles

El borde izquierdo = 20 píxeles

El borde derecho = 1 píxel
  
          d) border-width:10px 5px 20px 1px; (valor 0.25)
          
17. ¿Qué propiedad se usa para cambiar el margen izquierdo de un elemento? (valor 0.25)

          b) margin-left
          
18. Al usar la propiedad de relleno (padding); ¿Está permitido usar valores negativos? (valor 0.25)

            a) No
            b) Sí
            c) indent
            
 19. ¿Cómo se selecciona un elemento con id 'demo'? (valor 0.25)
 
            b) #demo

20.¿Cómo se seleccionan elementos con el nombre de clase 'test'? (valor 0.25)

            b) .test
         
            
21. ¿Cómo se seleccionan todos los elementos p dentro de un elemento div? (valor 0.25)

            b) div p
           
            
22.¿Cómo se agrupan los selectores? (valor 0.25)

            c) Separe cada selector con una coma
            
23. ¿Cuál es el valor predeterminado de la propiedad posición? (valor 0.25)

            a) absolute
            
 24.¿Cómo se hace una lista que enumere sus elementos con cuadrados? (valor 0.25)
 
            c) list-style-type: square;
            
Realiza la maquetación del siguiente ejemplo de página: (se aplica la rúbrica de la
maquetación en código html y css, valor 36)

![image](https://user-images.githubusercontent.com/91554777/166742177-b3cc2bfc-7768-42e4-b4f0-dcc2a1473935.png)

● Este ejercicio lo deberás realizar con las etiquetas de HTML5, haciendo uso de los elementos semánticos de HTML5.

● Deberás, en un bloc de notas, colocar todo el código html5 y guárdalo con extensión .html

● Lo mismo harás con el código CSS3, deberás guardar en un bloc de notas el código css3 con extensión .css.

● Guardar ambos archivos, el código html5 y css3, en una misma carpeta.

● Recuerda usar el elemento link para llamar dentro del código html5 los estilos guardados en el archivo con extensión .css.

-Hay tres imágenes que utilizarás para realizar esta actividad:
Imagen del logo institucional.
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg

Imagen del vector blanco que se encuentra antes del texto “Aprende a programar”. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero-vector.svg

Imagen paisaje de la Ciudad de México
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg

-El texto alternativo para la primer imagen imagen debe ser “Gobierno de la Ciudad de México”


          INGRESA AQUI EL CÓDIGO HTML
          
                              <!DOCTYPE html>
                    <html lang="en">
                    <head>
                        <meta charset="UTF-8">
                        <meta http-equiv="X-UA-Compatible" content="IE=edge">
                        <meta name="viewport" content="width=device-width, initial-scale=1.0">
                        <title>Evaluación Final</title>
                        <link rel="stylesheet" href="css/estilos.css">
                    </head>
                    <body>
                        <header>
                            <img src="img/logo.svg" alt="64px">
                            <hr>
                            <div id="menu">
                                <nav>
                                    <ul>
                                        <li>Residentes</li>
                                        <li>Negocios</li>
                                        <li>Visitantes</li>
                                        <li>Gobierno</li>
                                    </ul>
                                </nav>

                            </div>

                        </header>
                        <main>

                            <div id="texto">

                                <p id="prin"><img src="img/hero-vector.svg" alt="">APRENDE A PROGRAMAR EN LAS ESCUELAS DE CÓDIGO  DE LA CDMX</p>
                            </div>

                        </main>
                        <footer>
                            <h3>¿Quién se puede inscribir?</h3>
                            <div id="fo"> 
                                <p id="uno"> <b>Cualquier persona que aprenda a programar código y cuente con 4 a 8 horas disponibles a la semana</b> </p> 
                                <p id="dos">"Menores de edad deberán entrar a las instalaciones acompañados de un adulto</p>
                            </div><p> 

                        </footer>
                    </body>
                    </html>
          
          
          INGRESA AQUI EL CSS
          
                    *{
                      margin: 0;
                      padding: 0;
                      font-family: Arial, Helvetica, sans-serif;
                      list-style-type: none;
                      text-decoration: none;
                    }

                    nav{
                        width: 15%;

                    }

                    #menu{
                        display: flex;
                        justify-content: end;

                    }
                    ul{width: 100%;
                        font-size: 10px;
                        color: rgb(36, 133, 36);
                        height: 30px;
                        margin: 5px;
                        padding: 5px;
                        display: flex ;
                        justify-content: space-around;
                    }

                    main{
                        padding: 200px;
                        background-image: url(../img/hero.jpg);
                        background-repeat: no-repeat;
                        background-position: center;
                        background-size: cover;
                    }
                    span{
                        font-weight: bold;
                    }
                    #texto{
                        display: flex;
                        justify-content: flex-start;
                    }

                    #prin{
                        width: 40%;
                        color: white;
                        font-size: 40px;
                        display: flex;
                        text-align: right;
                    }

                    footer{
                        padding: 20px;
                    }
                    h3{
                        color: rgb(231, 149, 73);
                        display: flex;
                        justify-content: center;
                    }
                    #uno{
                        display: flex;
                        justify-content: center;
                    }
                    #dos{
                        display: flex;
                        justify-content: center;
                    }
        
         
          
 Ingresa el link a tu página del proyecto final
 
 https://kamiboty89.github.io/proyectofinaldise-o/
 

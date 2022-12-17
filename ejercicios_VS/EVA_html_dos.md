![image](https://user-images.githubusercontent.com/114317702/208269752-3966e432-838d-4ec9-b739-b468ae1a73ff.png)
HTML

      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Evaluación</title>
          <link rel="stylesheet" href="css/estilos.css">
      </head>
      <body>
          <header>
      <h1>ENCABEZADO NIVEL 1</h1>
      <nav>
          <uL>
          <li>ENLACE 1</li>
          <li>ENLACE 2</li>
          <li>ENLACE 3</li>
          <li>ENLACE 4</li>
          </uL>
      </nav>

          </header>
          <main>
            <div class="contenedor">
                  <section>
                      <h2>Encabezado nivel 2</h2>
                      <p>Aqui va texto del primer párrafo</p>
                      <p>Aqui va texto del segundo párrafo</p>

                  </section>
                  <aside>
                      <h2>Apartado</h2>
                      <p>Elige una opción</p>
                      <form action="">
                          <input type="radio" value="opcion 1" name="Opcion 1"> Opción 1<br>
                          <input type="radio" value="opcion 2" name="Opcion 1"> Opción 2<br>
                          <input type="radio" value="opcion 3" name="Opcion 1"> Opción 3 <br>
                          <br>
                          <input type="submit" value="Enviar">
                      </form>


                  </aside>
              </div>

          </main>
          <footer>
              <p>Sección de informacion de contacto, derechos de autor, etc.</p>

          </footer>

      </body>
      </html>
      
      ![image](https://user-images.githubusercontent.com/114317702/208269798-e544fe7c-5150-4e20-8437-7d965a20813c.png)
![image](https://user-images.githubusercontent.com/114317702/208269799-5b6fbc2d-bd4b-4f4e-8055-6b7ed62c7078.png)
![image](https://user-images.githubusercontent.com/114317702/208269805-1a2d3d0a-5608-465f-9a86-e4c1e89f10eb.png)

CSS

    *{
        margin: 0;
        padding: 0;
    }
    body{
        font-family: "Bungee Spice", cursive;
        font-family: "Roboto",sans-serif;
    }
    header{
        background-color: black;
        padding: 30px;
    }
    h1{
        color: aquamarine;
        text-align: center;
        font-size: 3cm;
        letter-spacing: 3px;

    }
    nav{
        background-color: aquamarine;
        padding: 25px 0;
        margin-top: 30px;

    }
    nav ul{
        display: flex;
        justify-content: space-around;

    }
    nav li{
        list-style: none;

    }
    section{
        background-color: blue;
        width: 80%;
    }
    aside{
        background-color: crimson;
        width: 20%;

    }
    footer{
        background-color: yellow;
        height: 20vh;

    }
    .contenedor {
        display: flex;
        width: 100%;
        height: 40vh;
    }

    section{
        text-align: center;
    }
    
    ![image](https://user-images.githubusercontent.com/114317702/208269817-159c1532-efcc-43c8-94b3-1b1fd9478cc1.png)
![image](https://user-images.githubusercontent.com/114317702/208269818-6963d52e-05e2-4195-8ba8-2fb77821e392.png)

![image](https://user-images.githubusercontent.com/114317702/208269827-2a99f405-fd3c-4f7d-877f-771edaca0d51.png)


![image](https://user-images.githubusercontent.com/114317702/208270027-df696bc3-a14d-4c0c-9004-f07a9d536df5.png)

HTML

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>formato texto</title>
        <link rel="stylesheet" href="css/estilos.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap" rel="stylesheet">

    </head>
    <body>
        <h1>Estilos para texto</h1>
        <H2 id="subtitulo" class="rojo">Selector de elementos</H2>
        <p>Un selector de elementos selecciona el elemento html por su nombre</p>
        <h2 class="rojo">Selector de ID</h2>
        <p>El selector de ID selecciona el atributo por su identificador, en html con el atributo ID y en CSS con el hash (#) </p>
        <h2 class="rojo">Selector de clase</h2>
        <p>Permite agrupar varios elementos en una clase, en html lo establecemos con el atributo clases y en css lo mandamos llamar con el punto</p>
        <h2>Selector uiversal</h2>
        <p>El asterisco es el selector universal que aplica a todos los elementos de la paginas</p>
    </body>
    </html>
    ![image](https://user-images.githubusercontent.com/114317702/208270037-4496a368-b967-4b1c-b47a-65d25a02451a.png)
![image](https://user-images.githubusercontent.com/114317702/208270038-5f4769b8-5436-4344-b278-676f09159287.png)

CSS

    h1{
        color: rgb(68, 110, 248);
        background-color: rgba(149, 212, 188, 0.829);
        /* font-size: 50px;COMENTARIOS */ text-decoration: underline; text-decoration-color: blueviolet;
        letter-spacing: 20px;
        word-spacing: 30px;
        text-transform: uppercase;
        text-align: center;
    }

    #subtitulo{
        color: rgb(44, 77, 224);
    }
    .rojo{
        color: red;
    }
    *{
        font-size: 30px;
    }
    body{
        background-color: rgb(188, 153, 228);
        font-family: 'Roboto', sans-serif;
    }
    
    ![image](https://user-images.githubusercontent.com/114317702/208270055-f4297191-65c1-4cf4-ab5c-cf8d462d0a75.png)
![image](https://user-images.githubusercontent.com/114317702/208270056-9d4df337-dc0e-4b01-baa7-5419dfd01fc2.png)

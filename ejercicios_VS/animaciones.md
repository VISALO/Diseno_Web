    !DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Animaciones 😎</title>
        <link rel="stylesheet" href="css/estilos.css">

    </head>
    <body>
        <header>
            <nav> 
                <p>Logo</p>
                <ul>
                    <li>Inicio</li>
                    <li>Animacion 1</li>
                    <li>Animacion 2</li>
                    <li>Animacion 3</li>
                    <li>Animacion 4</li>
                    <li>Animacion 5</li>
                </ul>
            </nav>
            <h1>EFECTOS Y ANIMACIONES</h1>



        </header>
        <main>
            <section class="animacion1">
                <h2>ANIMACION 1 ROTAR</h2>
                <img class="img1" src="https://img.freepik.com/vector-gratis/linda-chica-da-su-corazon-su-novio-feliz-dia-san-valentin-ilustracion-personaje-dibujos-animados_56104-375.jpg?w=826&t=st=1673735247~exp=1673735847~hmac=2ae454849203498fad1f32fd48e380c55ccb183478b4fe9c2cd82ba494d39990" alt="dibujo1" >


            </section>
            <section class="animacion2">
                <h2>ANIMACION 2</h2><br>
                <p class="animacion"> VIOLETA SANCHEZ LOPEZ</p>

            </section>
            <section class="animacion3">
                <h2>ANIMACION 3 </h2>

            </section>
            <section class="animacion4">
                <h2 class="olivetti">ANIMACION 4</h2>

            </section>
            <section class="animacion5">
                <h2>ANIMACION 5</h2>
                <img class="img2" src="https://img.freepik.com/vector-gratis/mejilla-chico-lindo-pellizcando-su-novia-feliz-san-valentin-ilustracion-personaje-dibujos-animados_56104-367.jpg?w=826&t=st=1673742099~exp=1673742699~hmac=bdbd701e9837a696e2ed131c941c38f1c71d82963b8cf37bf0353c5209a9b4ba" alt="dibujo2">


            </section>

        </main>
        <footer>

        </footer>

    </body>
    </html>
    
  ![imagen](https://user-images.githubusercontent.com/114317702/212503335-fb3584ca-cad6-423e-83a3-5ee189570263.png)

![imagen](https://user-images.githubusercontent.com/114317702/212503339-a6f35802-6ba8-45c7-93c3-01ce577d9022.png)

![imagen](https://user-images.githubusercontent.com/114317702/212503360-a7bb106f-af09-46f5-90cc-c9630f58ea23.png)

![imagen](https://user-images.githubusercontent.com/114317702/212503365-f9eab8a0-fce4-42f6-92d6-39f40b8dbd91.png)
![imagen](https://user-images.githubusercontent.com/114317702/212503369-57c262ed-23f8-44e7-bac0-6065cdb35d0b.png)
![imagen](https://user-images.githubusercontent.com/114317702/212503374-ab6ab61a-5c45-4d5e-816c-ca37932fc9a4.png)
![imagen](https://user-images.githubusercontent.com/114317702/212503385-88273dab-dec2-46d9-96f6-71bac3ccbbf4.png)
![imagen](https://user-images.githubusercontent.com/114317702/212503397-e7cb9ec8-813c-4ca3-b835-b928ccc60e21.png)

    *{
        margin: 0;
        padding: 0;
    }
    /* GENERAL */
    section{
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    /* BARRA DE NAVEGADOR */
    ::-webkit-scrollbar-thumb{
        background-color: rgb(233, 14, 142);
        border-radius: 10px;

    }
    ::-webkit-scrollbar-track{
        background-color: aqua;
        border-radius: 10px;
    }
    ::-webkit-scrollbar{
        width: 20px;
    }
    /* Header */
    header{
        height: 100vh;
        background: url(https://img.freepik.com/vector-gratis/pareja-amantes-sosteniendo-corazon-leido-juntos-feliz-dia-san-valentin-ilustracion-personaje-dibujos-animados_56104-389.jpg?w=826&t=st=1673732337~exp=1673732937~hmac=a7dbd4e23b4fb144929d3fa210a0946410ba3a1af3c947b7eba7c8518dff06aa);
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
    }
    nav{
        display: flex;
        justify-content: space-around;

    }
    ul{
        display: flex;
    }
    li{
        list-style: none;
        margin-right: 20px;
        background-color: rgb(231, 47, 108);
        border-radius: 10px;
        color: rgb(255, 255, 255);
        padding: 20px;


    }
    li:hover{
        color: rgb(251, 255, 0);
        background-color: rgba(255, 0, 34, 0.171);
    }
    /* Animacion 1 */
    .animacion1{
        background-color: brown;
    }
    .animacion1 img{
        width: 30%;

    }
    .img1:hover{
        border-radius: 50%;
        box-shadow: 0 0 15px 15px yellow;
        transform: rotate(360deg);
        transition: all .5s ease-in-out;

    }




    /* Animacion 2 */
    .animacion2{
        background-color: rgb(247, 6, 6);
    }
    @keyframes movimiento-lateral{from{left: -500px;}to {left: 500px;}}
    .animacion{animation-name: movimiento-lateral;
        animation-duration: 5s;
        animation-iteration-count: infinite;
        animation-direction: alternate;
        width: 200px;
        background-color: aqua;
        color: blue;
        position: relative;
        padding: 3px;


    }
    /* Animacion 3 */
    .animacion3{
        background-color: rgb(168, 108, 224);
    }
    @keyframes fadein{ to{transform: translateX(0px); opacity: 2;}}
    .animacion3{
        animation:fadein 2s linear forwards;
        transform: translateX(1500px);

    }


    /* Animacion 4 */
    .animacion4{
        background-color: rgb(221, 83, 187);
    }
    @keyframes olivetti{from{width: 0;}}
    @keyframes pampagulla{50% {borderd-color: trasnparent;}}
    .olivetti{
        font-size: 2em;
        font-family: monospace;
        color: pink;
        width:30%;
        animation:olivetti 5s steps(30),panpagulla .5s step-end infinite alternate;
        white-space: nowrap;
        overflow:hidden;
        border-right: 2px solid pink;


    }
    /* Animacion 5 */
    .animacion5{
        background-color: rgb(185, 146, 221);
    }

    .img2{
        width: 30%;
        max-height: 40vh;
        -webkit-box-reflect:
        below -1px
        linear-gradient(to bottom,transparent,
        rgba(0,0,0,0.8));
    }
    /* Footer */
    
    
![imagen](https://user-images.githubusercontent.com/114317702/212503424-d352ebc8-572f-42fb-b009-01e858f8fdd3.png)
![imagen](https://user-images.githubusercontent.com/114317702/212503436-c4805fe0-7fea-4836-8086-c8644319e290.png)
![imagen](https://user-images.githubusercontent.com/114317702/212503449-c0a4ac38-b676-40f8-ad5e-6029847fd29b.png)
![imagen](https://user-images.githubusercontent.com/114317702/212503454-cc05dd65-01a8-4fe3-96b5-b48652df5944.png)





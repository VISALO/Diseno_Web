    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Diseño Responsivo</title>
        <link rel="stylesheet" href="css/estilos.css">
    </head>
    <body>
        <header>
            <h1>DISEÑO RESPONSIVE</h1>

        </header>
        <main>
            <div>
                <img src="https://w1.pngwing.com/pngs/457/348/png-transparent-cartoon-computer-computer-monitors-line-angle-technology-text-black-and-white-area.png" alt="escritorio">
                <h2>De 1024 pixeles en adelante</h2>


            </div>
            <div>
                <img src="https://thumbs.dreamstime.com/b/esquema-de-la-tecnolog%C3%ADa-digital-de-la-pluma-de-la-tableta-82206914.jpg" alt="tablet">
                <h2>De 1023 pixeles a 768 pixeles</h2>


            </div>
            <div>

                <img src="https://us.123rf.com/450wm/arkadivna/arkadivna1903/arkadivna190300428/arkadivna190300428.jpg?ver=6" alt="celular">
                <h2>De 767 pixeles a 320 pixeles</h2>

            </div>

        </main>
        <footer>

            <img class="img1" src="https://png.pngtree.com/png-clipart/20210310/original/pngtree-time-computer-clipart-black-and-white-png-image_5952951.png" alt="computadora">
            <img class="img2" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTym0FOTwXNgM9qYbSWJxacXGLylI9olcredpDBE0sD10wPTlUEP_wZ7Kd5QSCndK1zEHg&usqp=CAU" alt="celular">

        </footer>
    </body>
    </html>
    
  ccs
  
![imagen](https://user-images.githubusercontent.com/114317702/213890698-8b93e9b9-7ec3-42ce-be4a-24ee1361a7b7.png)

      *{
          padding: 0;
          margin: 0;
      }
      header{
          width: 90%;
          margin:auto;
          height: 30vh;
          background-color: grey;
          display: flex;
          align-items: center;
          justify-content: center;
      }
      h1{
          color: gray;
          -webkit-text-stroke: 2px black;
          font-size: 3em;
          letter-spacing: 10px;
          text-shadow: 0 0 5px rgb(243, 240, 60);
      }
      main{
          height: 60vh;
          display: flex;
          align-items: center;
          justify-content: space-around;
      }
      div{
          background-color: gray;
          border-radius: 20px;
          width: 30%;
          height: 25vh;
          text-align: center;
          transition: height 1s;

      }
      div:hover{
          height: 20em;

      } 
      img{
          width: 100%;
          margin-top: -80px;
          height: 200px;

      }
      footer .img1{
          width: 10%;
          display: block;
      }

      footer .img2{
          width: 10%;
          display: none;
      }

      /* comienza el diseño responsivo, adaptacion a celular, lo de arriba es para computadora */

      @media(max-width:767px){
          body{
              background: url(data:image/jpeg;base64,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);
              background-repeat: no-repeat;
              background-size: cover;
              background-position: center;
          }
          header{
              width: 100%;
              height: 20vh;
              background-color: rgba(127, 255, 212, 0.541);

          }
          h1{
              font-size: 2em;
              letter-spacing: 5px;

          }
          main{
              flex-direction: column;
              height: 150vh;
          }
          footer .img1{
              display: none;
          }
          footer .img2{
              display: block;
          }
![imagen](https://user-images.githubusercontent.com/114317702/213891099-442480dc-2735-4ef9-bdad-63c9a6803e2a.png)

![imagen](https://user-images.githubusercontent.com/114317702/213891232-80820619-fec9-451a-ada3-9c612e853f03.png)




}
![imagen](https://user-images.githubusercontent.com/114317702/213891599-c2dbc146-2c9f-4a73-ac4c-c3f1e545fd64.png)

![imagen](https://user-images.githubusercontent.com/114317702/213891691-62ed1bb1-b894-4ddf-bf38-062c722cd361.png)


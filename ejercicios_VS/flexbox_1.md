    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>FLEXBOX</title>
        <link rel="stylesheet" href="css/estilos.css">
    </head>

    <body>
        <H1>FLEXBOX</H1>
        <h2>space beetwen y centrado</h2>
        <div class="caja">
            <div class="cajita">

            </div>
            <div class="cajita">

            </div>
            <div class="cajita">

            </div>
        </div>
        <h2>space round y abajo</h2>
        <div class="caja1">
            <div class="cajita1">

            </div>
            <div class="cajita1">

            </div>
            <div class="cajita">

            </div>
        </div>
            <h2>center</h2>
        <div class="caja">
            <div class="cajita2">

            </div>
            <div class="cajita2">

            </div>
            <div class="cajita2">

            </div>
        </div>


    </body>
    </html>
    
    *{
    padding: 0;
    margin: 0;
    }
    h1{
        text-align: center;
    }
    .cajita{ 
        background-color: aqua;
        width: 10%;
        height: 10vh;
    }
    .caja{
        display: flex;
        justify-content: space-between;
        background-color: blue;
        align-items: center;
    }

    .cajita1{ 
        background-color: aqua;
        width: 10%;
        height: 10vh;
    }
    .caja1{
        display: flex;
        justify-content: space-around;
        height: 10vh;
        align-items: flex-end;
        background-color: blueviolet;
    }
    .cajita2{ 
        background-color: aqua;
        width: 10%;
        height: 10vh;
        margin-right: 15 px;
    }
    .caja2{
        display: flex;
        justify-content: center;

    }
    .cajita3{ 
        background-color: aqua;
        width: 10%;
        height: 10vh;
        margin-right: 15px;
    }
    .caja3{
        display: flex;
        justify-content: center;

    }
    ![imagen](https://user-images.githubusercontent.com/114317702/206881378-ec263ee6-b3ed-40f6-9719-7f99d6edf6dd.png)
![imagen](https://user-images.githubusercontent.com/114317702/206881380-994e7bb6-5c63-4125-9914-844c20bd9aa0.png)

![imagen](https://user-images.githubusercontent.com/114317702/206881386-43dcad24-0945-4153-9f91-d31b43565bda.png)

![imagen](https://user-images.githubusercontent.com/114317702/206881395-180bb37a-abb6-49de-9434-2de30a764b93.png)

![imagen](https://user-images.githubusercontent.com/114317702/206881397-cbe42d4e-4e83-4951-bb36-c4c703a54484.png)

                  Index
                  <!DOCTYPE html>
                  <html lang="en">
                  <head>
                      <meta charset="UTF-8">
                      <meta http-equiv="X-UA-Compatible" content="IE=edge">
                      <meta name="viewport" content="width=device-width, initial-scale=1.0">
                      <title>Formularios</title>
                  </head>
                  <body>
                      <h1> Formulario de taqueria</h1>
                      <h2>Menú</h2>
                      <h3>Tacos</h3>
                      <ul>
                         <li>Bistec............ $25</li>
                         <li>Birria.............$20</li>
                         <li>Barbacoa.......$40</li>
                         <li>Suadero.........$22</li>
                         <li>Guisado.........$25</li>
                         <li>Longaniza......$15</li>

                      </ul>
                  <dl>
                      <dt> Especial_1..........$60</dt>
                      <dd>--Barbacoa con queso y dorada al comal, acompañado de un refresco</dd>
                      <dt>Especial_2............$65</dt>
                      <dd>--Arrachera, con cebollas doradas y papas a la francesa</dd>
                      <dt>Especial_3.............$70</dt>
                      <dd>--bisteck con nopales asados, papas cebollitas y papas a la francesa</dd>

                      <h2>Haz tu pedido</h2>
                      <form action="" method="">
                          NOMBRE <input type="text" maxlength="30" minlength="3" required placeholder="nombres y apellidos"> <br>
                          TELEFONO <input type="tel" minlength ="10" maxlength ="10" value="+52"required placeholder="SOLO 10 NUMEROS"> <br>
                          CORREO <input type="email" required placeholder="XXXXXX@gmail.com"> <br>
                          <p>ES PARA COMER EN LOCAL O PARA LLEVAR</p>
                          <input type="radio" value="LLEVAR" name="llevar"> Para llevar 
                          <input type="radio" value="LOCAL" name="llevar"> Para comer en el local <br>
                          <br>

                          <textarea id ="direccion" required placeholder="ingresa tu direccion"></textarea> <br>

                          <p> Para cuando es tu orden</p>
                          <input type="date" value="fecha" minlength="19/11/2022" maxlength="31/12/2022">

                        <p>ELIGE TUS TACOS</p> 
                          <select name="orden1" >
                              <option value="Bistec">Bistec</option>
                              <option value="Birria">Birria</option>
                              <option value="Barbacoa">Barbacoa</option>
                              <option value="Suadero">Suadero</option>
                              <option value="Guisado">Guisado</option>

                          </select>   
                              <p>Cuantos?</p>
                              <input type="number" min="5" max="20"> <br>

                              <input type="checkbox" value="salsa roja" name="salsa roja"> Salsa roja
                              <input type="checkbox" value="salsa verde" name="salsa verde"> Salsa verde
                              <input type="checkbox" value="Refresco cola" name="Refresco cola"> refresco cola
                              <input type="checkbox" value="Papas a la fracesa" name="sPapas a la fracesa"> Papas a la fracesa
                              <input type="checkbox" value="Queso extra" name="Queso extra"> Queso extra <br>

                              <select name="orden2" >
                                  <option value="Bistec">Bistec</option>
                                  <option value="Birria">Birria</option>
                                  <option value="Barbacoa">Barbacoa</option>
                                  <option value="Suadero">Suadero</option>
                                  <option value="Guisado">Guisado</option>

                              </select>   
                                  <p>Cuantos?</p>
                                  <input type="number" min="5" max="20"> <br>

                                  <input type="checkbox" value="salsa roja" name="salsa roja"> Salsa roja
                                  <input type="checkbox" value="salsa verde" name="salsa verde"> Salsa verde
                                  <input type="checkbox" value="Refresco cola" name="Refresco cola"> refresco cola
                                  <input type="checkbox" value="Papas a la fracesa" name="sPapas a la fracesa"> Papas a la fracesa
                                  <input type="checkbox" value="Queso extra" name="Queso extra"> Queso extra <br>
                                  <br>


                                  <input type="submit" value="Listo! 👌">
                                  <input type="reset" name="borrar" id="">











                      </form>


                  <form>
                  <input type="color"> ESCOGE UN COLOR <br>

                  PASWORD <input type="password"> <br>

                  AGREGA UN ARCHIVO <input type="file"> <br>


                  </form>



                  </dl>


                  </body>
                  </html>

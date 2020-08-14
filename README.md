<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ReservasdeZamorano</title>
    <link rel="stylesheet" href="estilo.css"/>
    <link rel="shortcut icon" href="img/iconmonstr-marketing-5-16.png" type="image/x-icon">
  <style>
     body{
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        
        }
        .proyectos{
            background: rgb(230, 230, 230);
                    width: 70%;
                    height: 180px;
                    overflow-y: auto;
                    overflow-x: hidden;
                    margin: 20px 0px 10px 6px;
        }
        .contenedor{
            padding: 60px;
            width: 90%;
            max-width: 1000px;
            margin: auto;
            overflow: hidden;
           
        }
        .titulo{
            color: darkorange;
            font-size: 30px ;
            text-align: center;
            margin-bottom: 60px;
        }
        /* Header */
        header{
            width: 100%;
            height: 600px;
            background: #FDC830;
              /* fallback for old browsers */
        background: linear-gradient(to right, hsla(20, 89%, 58%, 0.527), hsla(44, 98%, 59%, 0.76)), url();
          /* Chrome 10-25, Safari 5.1-6 */
        background: linear-gradient(to right, hsla(20, 89%, 58%, 0.527), hsla(44, 98%, 59%, 0.76)), url(); 
        /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
        background-size: cover;
        background-attachment: fixed;
        position: relative;
        
        } 
        nav{
            text-align: right;
            padding: 30px 50px 0 0;
        }
        nav > a {
        color: #ffffff;
        font-weight: 300;
        text-decoration: none;
        margin-right: 10px;
        }
        nav > a:hover{
        text-decoration: underline;
        }
        
        .encabezados{
            display: flex;
            height: 430px;
            width: 100%;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            text-align: center;
        }
        .encabezados h1{
            font-size: 50px;
            color: #fff;
        }
        .encabezados h2{
            font-size: 30px;
            font-weight: 300;
            color: #fff;
        }
        .ola{
            position: absolute;
            bottom: 0px;
            width: 100%;}
        
            /* abaut us */
            .contenedor-sobre-nosotros{
                display: flex;
                justify-content: space-evenly;
            }
            .imagen-abaut-us{
                width: 700px;
            }
            .sobre-nosotros .contenido-texto{
                width: 50px;
            }
            .contenidos-textos h3{
                margin-bottom: 15px;
            }
            .contenidos-textos h3 span{
                background: peru ;
                color: #fff;
                border-radius: 50%;
                display: inline-block;
                text-align: center;
                width: 30px;
                height: 30px;
                padding: 5px;
                box-shadow: 0 0 6px 0 rgba(0, 0, 0, 1);
                margin-right: 5px;
            }
            .contenido-texto{
                padding: 0px 0px 40px 15px;
                font-weight: 400;
                text-align: justify;
            }
        
            /* Galeria */
        
            .preyectos {
                background: rgb(230, 230, 230);
            }
            .galeria-port {
                display: flex;
                justify-content: space-evenly;
                flex-wrap: wrap;
            }
            .imagen-port{
                width: 24%;
                margin-bottom: 10px;
                height: 200px;
                overflow: hidden;
                position: relative;
                cursor: pointer;
                box-shadow: 0 0 6px 0 rgba(0, 0,0, .5);
            }
            .imagen-port > img{
                width: 100%;
                height: 100%;
                object-fit: cover;
                display: block;
        
            }
            .hover-galeria {
                position: absolute;
                width: 100%;
                height: 100%;
                top: 0px;
               transform: scale(0); 
                background: hsla(44, 98%, 59%, 0.76);
                transition: transform 01s;
                display: flex;
                justify-content: center;
                align-items: center;
                flex-direction: column;
            }
            .hover-galeria img{
                width: 50px;
            }
            .hover-galeria p {
                color: #fff;
            }
            .imagen-port:hover .hover-galeria{
                transform: scale(1);
            }
         /* clientes */
         .card{
             display: flex;
             justify-content: space-evenly;
         }
         .cards .card{
             background: tan;
             display: flex;
             width: 46%;
             height: 200px;
             align-items: center;
             justify-content: space-evenly;
             border-radius: 5px;
             box-shadow: 0 0 6 0 rgba(0, 0, 0, 0.6);
         }
         .cards  .card img {
             width: 100px;
             height: 100px;
             object-fit: cover;
             border: 3px solid #fff;
             border-radius: 50%;
             display: block;
         }
         .cards .card >.contenido-texto-card{
             width: 60%;
             color: #fff;
         }
         .cards .card >  .contenido-texto-card p{
             font-weight: 300;
             padding-top: 5px;
         }
        /* over team */
        .abaut-services{ 
            background: #f2f2f2;
            padding-bottom: 30px;
        }
        .servicio-cont{
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .servicio-ind{
            width: 50%;
            text-align: center;
        }
        .servicio-ind img{
            width: 90%;
        }
        .servicio-ind p{
            font-weight: 300px;
            text-align: justify;
        }
        
        
        /*footer*/
        footer{
            background: #414141;
            padding: 60px 0 30px 0;
            margin: auto;
            overflow: hidden;
        }
        .contenedor-footer{
            display: flex;
            width: 90%;
            justify-content: space-evenly;
            margin: auto;
            padding-bottom: 50px;
            border-bottom: 1px solid #ccc;
        }
        .content-foo{
            text-align: center;
        }
        .content-foo h4 {
           color: #fff;
           border-bottom: 3px solid #EF7F1A ;
           padding-bottom: 5px;
           margin-bottom: 10px;
        }
        .content-foo p {
           color: #fff;
        }
        .titulo-final{
            text-align: center;
            font-size: 24px;
            margin: 20px 0 0 0;
            color: dimgray;
        }
           
  </style>
    
</head>
<body>
    <header>
        <nav>
            <a href="#">Inicio</a>
            <a href="#">Acerca de</a> 
             <a href="#">Contactanos</a>
             <a href="#">Ubicanos</a>

        </nav>


       <SEction class="encabezados">
           <h1>Aqui toda la informacion</h1>
           <h2>Sobre Reservas de Zamorano</h2>
       </SEction>

       <div class="ola" style="height: 150px; overflow: hidden;" ><svg viewBox="0 0 500 150" preserveAspectRatio="none" style="height: 100%; width: 100%;"><path d="M0.00,49.98 C223.75,146.53 349.20,-49.98 500.00,49.98 L500.00,150.00 L0.00,150.00 Z" style="stroke: none; fill: #fff;"></path></svg></div>
        <main>


         <section class="contenedor sobre-nosotros">
         <h2 class="titulo">Quienes somos</h2>
         <div class="contenedor-sobre-nosotros">
             <img src="img/ilustracion quienes somos.png" alt="Es una ilustracion que contiene una imagen de una niña y tiene por defecto el color naranja" class="imagen-abaut-us">
             <div class="contenidos-textos">
                 <h3><span>1</span>¿Quienes somos?</h3>
                 <P>Somos el el centro comunal del barrio reservas de zamorano, aqui es donde se hacen las respectivas actividades del barrio.</P>
                 <h3><span>2</span>¿Para que estamos?</h3>
                 <P>Estamos para velar por la seguridad, recracion y diferentes aspectos u necesidades de nuestra comunidad.</P>
            </div>   
         </div>
         </section>


         <div class="proyectos">
             <div class="contenedor">
                 <h2 class="titulo">Actividades</h2>
                  <div class="galeria-port">
                      <div class="imagen-port"> 
                          <img src="img/img1.jpg" alt="" width="500">
                          <div class="hover-galeria">
                              <img src="img/icono.png" alt="">
                              <p>Nuestro trabajo</p>
                          </div>
                      </div>

                      <div class="imagen-port"> 
                        <img src="img/img2.jpg" alt="">
                        <div class="hover-galeria">
                            <img src="img/icono.png" alt="">
                            <p>Nuestro trabajo</p>
                        </div>
                    </div>

                    <div class="imagen-port"> 
                        <img src="img/img3.jpg" alt="">
                        <div class="hover-galeria">
                            <img src="img/icono.png" alt="">
                            <p>Nuestro trabajo</p>
                        </div>
                    </div>

                    <div class="imagen-port"> 
                        <img src="img/img4.jpg" alt="">
                        <div class="hover-galeria">
                            <img src="img/icono.png" alt="">
                            <p>Nuestro trabajo</p>
                        </div>
                    </div>

                  </div>  
                 
                                                              
                         </div>
                     </div>
                 </div>


             </div>
            </div>
         

        <div class="clientes7">
        <h2 class="titulo">Que dicen nuestros propietarios</h2>

        <div class="cards">
           <div class="card">
               <img src="img/fot3.jpg" alt="">
               <div class="contenido-texto-card">
                <h4>Jonnier</h4>
                <p>El barrio tiene unas increibles vistas como las que son el parque y me encanta su estilo envegecido</p>
                </div>     
            </div>
        </div>

        <div class="cards">
            <div class="card">
                <img src="img/foto1.jpg" alt="">
                <div class="contenido-texto-card">
                 <h4>Alejandro</h4>
                 <p>El sistema de seguridad de este año fue muy efectivo/p>
                 </div>     
             </div>
         </div>
        </div>


        <section class="abaut-services">
            <div class="contenedor">
                <h2 class="titulo">nuerstro servicio</h2>
                <div class="servicio-cont">
                    <div class="servicio-ind">
                        <img src="img/foto2.png" alt="" >
                        <h3>Don Martin Sanchez</h3>
                        <p>mi labor es velar por la comunicación, orden e integridad de los habitantes de este sector 
                        </p>
                    </div>
                </div>
            </div>
        </section>

        
        </main>
        <footer>
         <div class="contenedor-footer">
             <div class="content-foo">
                 <h4>Numero de celular</h4>
                 <h2>5456423156745567</h2>
             </div>
             <div class="content-foo">
                <h4>Email</h4>
                <h2>Misparitas.com</h2>
            </div> <div class="content-foo">
                <h4>localizacion</h4>
                <h2>Reservas de Zamorano,Palmira,Colombia</h2>
            </div>
         </div>
         <h2 class="titulo-final">&copy; Alejandro Sanchez </h2>
        </footer>

    </header>
    
</body>
</html>

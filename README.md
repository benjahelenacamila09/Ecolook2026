[codigonuevo.html](https://github.com/user-attachments/files/32236976/codigonuevo.html)
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inicio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #bac8b1;
            color: white;
            text-align: center;
            padding: 30px 20px;
        }

        header h1 {
            font-size: 2rem;
            margin-bottom: 8px;
        }

        header p {
            font-size: 1rem;
        }

        main {
            max-width: 1200px;
            margin: 0 auto;
            padding: 30px 20px;
        }

        .grid-productos {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .producto {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.15);
            display: flex;
            flex-direction: column;
            width: 250px;
        }

        .producto img {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }

        .producto-info {
            padding: 15px;
            display: flex;
            flex-direction: column;
            flex-grow: 1;
        }

        .producto-info h2 {
            font-size: 1.1rem;
            margin-bottom: 6px;
        }

        .producto-info p {
            font-size: 0.9rem;
            color: #666;
            flex-grow: 1;
            margin-bottom: 10px;
        }

        .precio {
            font-size: 1.2rem;
            font-weight: bold;
            background-color: #CCB499;
            margin-bottom: 10px;
        }

        .boton-comprar {
            background-color: #CCB499;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 6px;
            font-size: 0.95rem;
            cursor: pointer;
        }

        .boton-comprar:hover {
            background-color: #CCB499;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            margin-top: 40px;
        }

        .whatsapp {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            margin: 15px 0;
            gap: 10px;
        }

        .whatsapp img {
            width: 30px;
        }

        .whatsapp a {
            text-decoration: none;
            padding: 5px;
            background-color: #3cc24e;
            border-radius: 8px;
            color: white;
        }

        .mercadopago {
            display: flex;
            gap: 10px;
            justify-content: center;
            flex-direction: column;
            align-items: center;
            margin: 15px 0;
        }

        .mercadopago a {
            text-decoration: none;
            padding: 5px;
            background-color: #2abdff;
            border-radius: 8px;
            color: white;
        }

        .mercadopago img {
            width: 30px;
            border-radius: 8px;
        }

        .instagran {
            display: flex;
            flex-direction: column;
            gap: 10px;
            justify-content: center;
            align-items: center;
            margin: 15px 0;
        }

        .instagran img {
            width: 30px;
            border-radius: 8px;
        }

        .instagran a {
            text-decoration: none;
            padding: 5px;
            background-color: #e23352;
            border-radius: 8px;
            color: white;
        }

        .contenedor2 {
            display: flex;
            gap: 5px;
            align-items: center;
            justify-content: flex-end;



        }

        .contenedor2 a {
            text-decoration: none;
            background-color: #CCB499;
            color: white;
            padding: 10px;
            border-radius: 10px;


        }

        .contenedor2 a.activo {
            background-color: rgb(45, 192, 45);
            color: white;
        }

        .brand {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .arriba {
            display: flex;
            justify-content: space-between;


        }

        .arriba img {

            width: 130px;
        }
        @media (max-width : 500px){
            .arriba{
                display: flex;
                flex-direction: column;
            }

        }
        .abajo{
            display: flex;
            justify-content: space-between;
        }
        .abajo img{
            width: 30px;
        }

          .abajo img {

            width: 30px;
        }
        @media (max-width : 500px){
            .abajo{
                display: flex;
                flex-direction: column;
            }

        }

    

    </style>
</head>

<body>

    <header>
        <div class="arriba">
            <div>
                <img src="logo2.png" alt="">
            </div>
            <div class="brand">
                <h1> Ecolook </h1>
                <p>"Todo tiene su lado bello pero no todos lo ven"</p>

            </div>
            <div class="contenedor2">

                <a href="codigonuevo.html" class="activo">Inicio</a>
         
            </div>
        </div>

        <div class="abajo">
            <div class="whatsapp">
                <img src="wsp.avif" alt="">
                <a href="https://wa.me/5493517658746?text=Hola%2C%20quiero%20hacer%20una%20consulta">Mandanos un
                    Whatsapp
                </a>
            </div>

            <div class="mercadopago">
                <img src="mercadopt.png" alt="">
                <a href="https://link.mercadopago.com.ar/laconsolini.mp" target="_blank" class="enlaces">Link de Mercado
                    Pago
                </a>
            </div>
            <div class="instagran">
                <img src="ig.png" alt="Instagram">
                <a href="https://www.instagram.com/eco.look2026" target="_blank" rel="noopener noreferrer"
                    class="ig-link">
                    Seguinos en Instagram
                </a>
            </div>
        </div>
    </header>

    <main>

        <div class="grid-productos">

            <div class="producto">
                <img src="imagenes/peluche01.webp" alt="Peluche Osito Clásico">
                <div class="producto-info">
                    <h2>Osito Clásico</h2>
                    <p>Osito de peluche suave, ideal para abrazar y decorar la habitación.</p>
                    <span class="precio">$8.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche02.webp" alt="Peluche Conejo Orejón">
                <div class="producto-info">
                    <h2>Conejo Orejón</h2>
                    <p>Conejo de orejas largas, tela afelpada y relleno hipoalergénico.</p>
                    <span class="precio">$7.900</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche03.jpg" alt="Peluche Perrito Dormilón">
                <div class="producto-info">
                    <h2>Perrito Dormilón</h2>
                    <p>Perrito con expresión tierna, perfecto para dormir acompañado.</p>
                    <span class="precio">$9.200</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche04.webp" alt="Peluche Gatito Curioso">
                <div class="producto-info">
                    <h2>Gatito Curioso</h2>
                    <p>Gatito de peluche con ojos brillantes y colita esponjosa.</p>
                    <span class="precio">$8.100</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche05.webp" alt="Peluche Panda Bebé">
                <div class="producto-info">
                    <h2>Panda Bebé</h2>
                    <p>Panda tierno en blanco y negro, tamaño mediano.</p>
                    <span class="precio">$10.400</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche06.jpg" alt="Peluche Elefante Chiquito">
                <div class="producto-info">
                    <h2>Elefante Chiquito</h2>
                    <p>Elefante gris de trompa larga, ideal para bebés.</p>
                    <span class="precio">$7.300</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche07.jpg" alt="Peluche León Melenudo">
                <div class="producto-info">
                    <h2>León Melenudo</h2>
                    <p>León con melena esponjosa y expresión amigable.</p>
                    <span class="precio">$9.800</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche08.webp" alt="Peluche Jirafa Alta">
                <div class="producto-info">
                    <h2>Jirafa Alta</h2>
                    <p>Jirafa de cuello largo y manchas cosidas a mano.</p>
                    <span class="precio">$11.000</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche09.jpg" alt="Peluche Zorro Astuto">
                <div class="producto-info">
                    <h2>Zorro Astuto</h2>
                    <p>Zorro de colores cálidos, cola grande y suave.</p>
                    <span class="precio">$8.700</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche10.avif" alt="Peluche Koala Tierno">
                <div class="producto-info">
                    <h2>Koala Tierno</h2>
                    <p>Koala abrazado a una rama, textura ultra suave.</p>
                    <span class="precio">$9.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche11.jpg" alt="Peluche Pingüino Polar">
                <div class="producto-info">
                    <h2>Pingüino Polar</h2>
                    <p>Pingüino blanco y negro con bufanda tejida.</p>
                    <span class="precio">$8.300</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche12.webp" alt="Peluche Unicornio Mágico">
                <div class="producto-info">
                    <h2>Unicornio Mágico</h2>
                    <p>Unicornio con crin de colores y cuerno bordado.</p>
                    <span class="precio">$10.900</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche13.jpg" alt="Peluche Tigre Rayado">
                <div class="producto-info">
                    <h2>Tigre Rayado</h2>
                    <p>Tigre de rayas suaves y mirada juguetona.</p>
                    <span class="precio">$9.100</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche14.webp" alt="Peluche Oveja Lanuda">
                <div class="producto-info">
                    <h2>Oveja Lanuda</h2>
                    <p>Oveja blanca de lana simulada, muy esponjosa.</p>
                    <span class="precio">$7.600</span>

                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche15.jpg" alt="Peluche Rana Saltarina">
                <div class="producto-info">
                    <h2>Rana Saltarina</h2>
                    <p>Rana verde de ojos grandes y sonrisa simpática.</p>
                    <span class="precio">$6.900</span>
                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche16.webp" alt="Peluche Pulpo Multicolor">
                <div class="producto-info">
                    <h2>Pulpo Multicolor</h2>
                    <p>Pulpo de ocho tentáculos con textura acolchada.</p>
                    <span class="precio">$9.900</span>
                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche17.webp" alt="Peluche Búho Nocturno">
                <div class="producto-info">
                    <h2>Búho Nocturno</h2>
                    <p>Búho de plumas bordadas y ojos grandes redondos.</p>
                    <span class="precio">$8.400</span>
                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluuche18.webp" alt="Peluche Dinosaurio Amigable">
                <div class="producto-info">
                    <h2>Dinosaurio Amigable</h2>
                    <p>Dinosaurio verde con espinas suaves en el lomo.</p>
                    <span class="precio">$10.200</span>
                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche19.webp" alt="Peluche Ballena Azul">
                <div class="producto-info">
                    <h2>Ballena Azul</h2>
                    <p>Ballena grande y liviana, ideal como almohadón.</p>
                    <span class="precio">$12.300</span>
                </div>
            </div>

            <div class="producto">
                <img src="imagenes/peluche20.webp" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Mono Trepador</h2>
                    <p>Mono de brazos largos con velcro en las manos.</p>
                    <span class="precio">$8.800</span>
                </div>
            </div>

        </div>
    </main>

    <footer>
        <p>&copy; 2026 Tienda Ecoloop - Todos los derechos reservados</p>
    </footer>

</body>

</html>

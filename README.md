[pagina.html](https://github.com/user-attachments/files/32236976/codigonuevo.html)
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
                <p> </p>

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
                <img src= "vestidomarron.jpg" alt="Peluche Osito Clásico">
                <div class="producto-info">
                    <h2>Vestido</h2>
                    <p>Vestido color marrón talle U.</p>
                    <span class="precio">$3.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="vestidonegro.jpeg" alt="Peluche Conejo Orejón">
                <div class="producto-info">
                    <h2>Vestido</h2>
                    <p>Vestido color negro talle U.</p>
                    <span class="precio">$3.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="polleraniña.jpeg" alt="Peluche Perrito Dormilón">
                <div class="producto-info">
                    <h2>Pollera</h2>
                    <p>Pollera de jean de niña talle 6.</p>
                    <span class="precio">$3.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="remerablancaadidas.jpg" alt="Peluche Gatito Curioso">
                <div class="producto-info">
                    <h2>Remera</h2>
                    <p>Remera de algodón elastizado talle 6.</p>
                    <span class="precio">$1.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="topnegromangaslargas.jpg" alt="Peluche Panda Bebé">
                <div class="producto-info">
                    <h2>Top</h2>
                    <p>Top negro manga larga transparente.</p>
                    <span class="precio">$4.000</span>

                </div>
            </div>

            <div class="producto">
                <img src="pollerajeannenagrande.jpg" alt="Peluche Elefante Chiquito">
                <div class="producto-info">
                    <h2>Pollera</h2>
                    <p>Pollera de jean talle .</p>
                    <span class="precio">$4.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="pantalonnegro con friza.jpg" alt="Peluche León Melenudo">
                <div class="producto-info">
                    <h2>Pantalón</h2>
                    <p>Pantalón negro con friza.</p>
                    <span class="precio">$3.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="jeant44.jpg" alt="Peluche Jirafa Alta">
                <div class="producto-info">
                    <h2>Pantalón</h2>
                    <p>Pantalón de jean talle 46.</p>
                    <span class="precio">$4.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="sueterfelicialila.jpeg" alt="Peluche Zorro Astuto">
                <div class="producto-info">
                    <h2>Suéter</h2>
                    <p>suéter violeta Felicia.</p>
                    <span class="precio">$4.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="buzoverde.jpg" alt="Peluche Koala Tierno">
                <div class="producto-info">
                    <h2>Buzo</h2>
                    <p>buzo color verde talle 12.</p>
                    <span class="precio">$4.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="remeraparis.jpeg" alt="Peluche Pingüino Polar">
                <div class="producto-info">
                    <h2>Remera</h2>
                    <p>Remera "París  sanit-germain" talle S.</p>
                    <span class="precio">$2.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="remerarojacaptainfin.jpg" alt="Peluche Unicornio Mágico">
                <div class="producto-info">
                    <h2>Remera</h2>
                    <p>Remera roja captain fin talle M.</p>
                    <span class="precio">$2.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="buzoblanco.jpeg" alt="Peluche Tigre Rayado">
                <div class="producto-info">
                    <h2>Buzo del uniforme escolar</h2>
                    <p>Buzo blanco uniforme de educación fisica.</p>
                    <span class="precio">$4.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="chombapique.jpeg" alt="Peluche Oveja Lanuda">
                <div class="producto-info">
                    <h2>Chomba del uniforme escolar</h2>
                    <p>Chomba de piqué beige del uniforme.</p>
                    <span class="precio">$4.500</span>

                </div>
            </div>

            <div class="producto">
                <img src="sueterverde.jpeg" alt="Peluche Rana Saltarina">
                <div class="producto-info">
                    <h2>Suéter del uniforme escolar</h2>
                    <p>Suéter verde uniforme de clases.</p>
                    <span class="precio">$4.500</span>
                </div>
            </div>

            <div class="producto">
                <img src="pantalonuniforme.jpeg" alt="Peluche Pulpo Multicolor">
                <div class="producto-info">
                    <h2>Pantalón del uniforme escolar</h2>
                    <p>Pantalón de vestir del uniforme.</p>
                    <span class="precio">$4.500</span>
                </div>
            </div>

            <div class="producto">
                <img src="camperaacetato.jpg" alt="Peluche Búho Nocturno">
                <div class="producto-info">
                    <h2>Campera del uniforme escolar</h2>
                    <p>Campera uniforme de acetato.</p>
                    <span class="precio">$6.000</span>
                </div>
            </div>

            <div class="producto">
                <img src="JOGGINGVERDE.jpeg" alt="Peluche Dinosaurio Amigable">
                <div class="producto-info">
                    <h2>Pantalón del uniforme escolar</h2>
                    <p>Pantalon jogging verde del uniforme.</p>
                    <span class="precio">$4.500</span>
                </div>
            </div>

        

            <div class="producto">
                <img src="animalprintzapatos.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Zapatos</h2>
                    <p>Zapatos de gamuza negra con plataforma animal print talle 36.</p>
                    <span class="precio">$5.000</span>
                </div>
            </div>
            <div class="producto">
                <img src="sandaliasnegrascadenas.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Sandalias</h2>
                    <p>sandalias negras con aplique de cadenas talle 30/31.</p>
                    <span class="precio">$8.500</span>
                </div>
            </div>
            <div class="producto">
                <img src="botas marrones.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Botas</h2>
                    <p>botas marrones talle 3/31.</p>
                    <span class="precio">$9.000</span>
                </div>
            </div>
            <div class="producto">
                <img src="ZAPATOSNEGROSNENA.jpeg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Zapatos</h2>
                    <p>zapatos negros talle 37.</p>
                    <span class="precio">$7.500</span>
                </div>
            </div>
            <div class="producto">
                <img src="sandaliasblancas.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Sandalias</h2>
                    <p>sandalias blancas con plataforma talle 37.</p>
                    <span class="precio">$7.500</span>
                </div>
            </div>
            <div class="producto">
                <img src="botas negras.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Botas</h2>
                    <p>botas negras talle 30/31.</p>
                    <span class="precio">$7.500</span>
                </div>
            </div>
            <div class="producto">
                <img src="libroINGLESyabuelaANORMAL.jpeg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Libro</h2>
                    <p>LIbro “The picture of Dorian Gray” y "Una abuela anormal”".</p>
                    <span class="precio">$5.500</span>
                </div>
            </div>
            <div class="producto">
                <img src="libro_lluviasabeporque.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Libro</h2>
                    <p>Libro "La lluvia sabe por qué".</p>
                    <span class="precio">$3.000</span>
                </div>
            </div>
            <div class="producto">
                <img src="novelasimpresas_frankestein y ceremoniasecreta.jpeg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Novela</h2>
                    <p>Novela “Frankenstein o el moderno prometeo" y “Ceremonia secreta”.</p>
                    <span class="precio">$3.000</span>
                </div>
            </div>
            <div class="producto">
                <img src="libro_losvecinosmueren.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Novela</h2>
                    <p>Novela  "Los vecinos mueren en las novelas".</p>
                    <span class="precio">$3.000</span>
                </div>
            </div>
            <div class="producto">
                <img src="novelasimpresas_shrezada y rebeliondepalabras.jpeg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Novela</h2>
                    <p>Novela “Una y mil noches de sherezada" y “La rebelión de las palabras”.</p>
                    <span class="precio">$3.000</span>
                </div>
            </div>
            <div class="producto">
                <img src="libro_cronicamuerte.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Novela</h2>
                    <p>Novela "Crónica de una muerte anunciada".</p>
                    <span class="precio">$3.000</span>
                </div>
            </div>
            <div class="producto">
                <img src="plazaponis.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Juguete</h2>
                    <p>Juguete Plaza con ponis.</p>
                    <span class="precio">$5.000</span>
                </div>
            </div>
            <div class="producto">
                <img src="jueguetebebe.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Juguete</h2>
                    <p>Juguete bebé con bolso.</p>
                    <span class="precio">$3.500</span>
                </div>
            </div>
            <div class="producto">
                <img src="bolsofrozen.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Juguete</h2>
                    <p>Juguete bolso de frozen.</p>
                    <span class="precio">$1.500</span>
                </div>
            </div>
            <div class="producto">
                <img src="topbyn.jpeg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>TOP</h2>
                    <p>Top color blanco y negro con argolla Talle UNICO.</p>
                    <span class="precio">$3.500</span>
                </div>
            </div>
            <div class="producto">
                <img src="topnegroecocuero.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Top</h2>
                    <p>top negro de ecocuero Talle UNICO.</p>
                    <span class="precio">$3.500</span>
                </div>
            </div>
            <div class="producto">
                <img src="toprojo.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Top</h2>
                    <p>top rojo Talle UNICO.</p>
                    <span class="precio">$3.500</span>
                </div>
            </div>
            <div class="producto">
                <img src="toprosacon volados.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Top</h2>
                    <p>top color rosa claro con volados Talle UNICO.</p>
                    <span class="precio">$3.500</span>
                </div>
            </div>
            <div class="producto">
                <img src="toprosa.jpg" alt="Peluche Mono Trepador">
                <div class="producto-info">
                    <h2>Top</h2>
                    <p>top color rosa Talle UNICO.</p>
                    <span class="precio">$3.500</span>
                </div>
        </div>
 

    <footer>
        <p>&copy; 2026 Tienda Ecolook - Todos los derechos reservados</p>
    </footer>



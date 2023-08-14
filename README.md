<!DOCTYPE html>
<html>
<head>
    <title>Arilex HTML</title>

<style>
.contenedor {
            border: 2px solid #36271c;
            border-radius: 10px;
            padding: 20px;
        }
        .miBoton {
            background-color: #4e3c41;
            color: lightpink;
            padding: 10px 20px;
            border: none;
            border-radius: 20px; /* Cambia el radio para redondear las esquinas */
            cursor: pointer;
        }
        .contenido {
            display: none; /* Oculta el contenido inicialmente */
        }
        body {
          background-image: url('https://i.ibb.co/p1TyB0z/wallpaperbetter-com-1920x1080-2.jpg');
        background-size: cover;
        background-repeat: repeat; /* Repite el patrón en todo el fondo */
    }
            font-family:Palatino;
            font-size: 55px;
        }

        h1 {
            color: lightsalmon;
        }

        p {
          font-family:Georgia, cursive;
            font-size: 30px;
            color: darkgreen
        }
    </style>
    </head>
<body>
    <h1>Hola preciosa, esto es para ti!</h1>
    <p>Esta es mi primera página, y lo estoy haciendo por ti, te amo.
    Lo estoy haciendo justo cuando estas haciendo tarea con Ali jiji, ya ando aprendiendo, y de hecho
  fue por ti mi cielo, que decidi ya empezar a hacer estas cositas, te dejo este gif de Arisita
para mi Kuromilover, te amo tanto mi gordita preciosa, hago lo que sea por ti, aqui tienes esto
de ejemplo jiji</p>

<div class="contenedor">
        <h1>Mensaje para ti!</h1>
        <p>Mi gordita, no sabes lo feliz que me haces tu a mi, de verdad me haces bien, y quiero decirte que estoy mas enamorado de ti,
        cada dia me enamoro mas de ti, y yo te amo tal y como es mi verdadera Ari preciosa, me lleno de felicidad cuando te veo,
      y me encanta todo de ti, tu fisico es super increible y estoy orgulloso de tener a una mujer tan completa e ideal en mi vida
    no sabes cuanto orgullo me pones, es que simplemente lo eres TODO!!!!!</p>
    </div>

<button class="miBoton" id="miBoton">Haz clic para una sopresita!</button>
<div class="contenido" id="contenido">
        <img src="https://media.baamboozle.com/uploads/images/115506/1645035845_93210_gif-url.gif" alt="Gif de Kuromi">
        <p>Mira que bonita se ve nuestra Aricita!.
        A lo mejor puede que esto sea muy simple, pero recien hace como 1h empecé a aprender a como hacerlo
      con ayuda de ChatGPT, es un detalle rapido que hice para mi Ari tan linda, que se merece todo!
    TE AMOOOOOOOOOOOOOOO!!!</p>
    </div>

    <script>
            const boton = document.querySelector('#miBoton');
            const contenido = document.querySelector('#contenido');

            boton.addEventListener('click', () => {
                contenido.style.display = 'block';
            });
        </script>
</body>
</html>

# Paint

Juego de dibujo hecho con Python y turtle, basado en el juego Paint de freegames de Grant Jenks. Proyecto de la materia TC1005S Herramientas computacionales: el arte de la programacion, Tec de Monterrey.

## Requisitos

- Python 3
- tkinter (en Debian o Ubuntu: sudo apt-get install python3-tk)
- freegames

## Instalacion

    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt

## Como jugar

    python3 paint.py

Primero se elige la figura y el color con el teclado. Despues se da un clic donde empieza la figura y otro clic donde termina.

Figuras:

- l: linea
- s: cuadrado
- c: circulo (el primer clic es el centro)
- r: rectangulo
- t: triangulo

Colores (en mayuscula):

- K: negro
- W: blanco
- G: verde
- B: azul
- R: rojo
- Y: amarillo

Con la tecla u se deshace el ultimo trazo.

## Cambios realizados

- Se agrego el color amarillo.
- Se completo la funcion para dibujar circulos.
- Se completo la funcion para dibujar rectangulos.
- Se completo la funcion para dibujar triangulos.

## Autores

- jcontreras13
- Dilosch03

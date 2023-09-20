# Practica 1 VC

En esta primera práctica se nos ha propuesto una serie de tareas que explicaremos más adelante. El colab con todo el código se encuentra en el siguiente enlace: https://colab.research.google.com/drive/17aFVY7h1ETuZzcQUZmu0eytilbDG_NKO?usp=sharing

# Tarea 1: Tablero de Ajedrez
Para esta tarea hemos pintado de manera intermitente cuadrados blancos de 25x px sobre un fondo negro mostrado en matplotlib creando una figura idéntica a un tablero de ajedrez tradicional.


# Tarea 2: Imagen tipo Mondrian


# Tarea 3: Detección del punto más claro y más oscuro de la imagen
Para esta tercera tarea tomamos la imagen que entra por video y en cada iteración la convertimos a escala de grises y utilizando la función [cv2.minMaxLoc](https://docs.opencv.org/4.x/d2/de8/group__core__array.html#gab473bf2eb6d14ff97e89b355dac20707) (localiza el máximo y el mínimo globales en un array) encontramos los píxeles exactos con los valores más brillante y oscuro. 
Una vez encontrados los puntos se pintan dos círculos centrados en dichos píxeles.

# Tarea 4: Modificar el plano de la imagen

# Tarea 5: Propuesta Pop Art
Para nuestra propuesta "Pop Art" hemos decidido seguir el esquema clásico de Andy Warhol de la imagen cuatriplicada con los canales de color cambiados. Para darle un giro y aprovechando que disponemos de un medio dinámico (video vs foto) hemos decidido aleatorizar algunos de los canales de color en cada iteración. El no aleatorizar todos los canales provoca que, aunque la imagen cambia bastante, siempre haya un fondo que se mantiene y que se puede apreciar al ver los cambios a lo largo del tiempo.


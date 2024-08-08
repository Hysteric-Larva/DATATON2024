# DATATON2024
## Descripción del problema

El problema a resolver en este desafío consiste en predecir la distribución de masa de un sistema astrofísico a partir de las deformaciones que produce en la apariencia de cuerpos situados detrás de él. Esto es interesante porque nos permite estudiar la distribución de materia oscura asociada al sistema, materia que no puede ser observada directamente con nuestros telescopios porque no emite luz. En este desafío específico, el sistema astrofísico es un cúmulo de galaxias y los cuerpos detrás de él son galaxias.

En términos prácticos, se requiere construir un sistema que acepte X como entrada y devuelva Y como salida. Si aproximamos las galaxias de fondo como elipses, la entrada X será un cubo con 3 "tajadas" o "slices". Cada una de las primeras dos tajadas será una matriz que representa una de las dos componentes de las elipses que aproximan las galaxias detrás del sistema astrofísico de interés. La tercera tajada será una matriz que representa el error de medida de las elipticidad observada de las galaxias. Por otro lado, la salida Y es una matriz cuyos valores representan la masa proyectada del sistema astrofísico de interés en una posición determinada del cielo.

La forma en pixeles de la entrada es 128x128x3 y la forma de la salida es 128x128.

Para construir el sistema se dispone de un conjunto de "entrenamiento", es decir, muchos pares de la forma (X,Y) donde Y es la distribución de masa correcta para X. Sin embargo, el sistema se evaluará sobre un conjunto de pruebas, es decir, un conjunto de casos para los cuales los participantes sólo conocerán X.
## Links Importantes

* [Pagina Principal](https://dataton.inf.utfsm.cl/)
* [Pagina en Codabench](https://www.codabench.org/competitions/3583/#/pages-tab)
* [Descarga de datos](https://descargas.inf.santiago.usm.cl/train/1.tar.gz)
* [Drive Para Lecturas](https://drive.google.com/drive/folders/1L9aRpMQ1WaiCz-u3MBoK-nQmLNkvShfT?usp=drive_link)
* [Overleaf para bitacora y tomar notas:](https://www.overleaf.com/read/gphwhzxdvwfv#7c86f3)

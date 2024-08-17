# DATATON2024
## Descripción del problema

El problema a resolver en este desafío consiste en predecir la distribución de masa de un sistema astrofísico a partir de las deformaciones que produce en la apariencia de cuerpos situados detrás de él. Esto es interesante porque nos permite estudiar la distribución de materia oscura asociada al sistema, materia que no puede ser observada directamente con nuestros telescopios porque no emite luz. En este desafío específico, el sistema astrofísico es un cúmulo de galaxias y los cuerpos detrás de él son galaxias.

En términos prácticos, se requiere construir un sistema que acepte X como entrada y devuelva Y como salida. Si aproximamos las galaxias de fondo como elipses, la entrada X será un cubo con 3 "tajadas" o "slices". Cada una de las primeras dos tajadas será una matriz que representa una de las dos componentes de las elipses que aproximan las galaxias detrás del sistema astrofísico de interés. La tercera tajada será una matriz que representa el error de medida de las elipticidad observada de las galaxias. Por otro lado, la salida Y es una matriz cuyos valores representan la masa proyectada del sistema astrofísico de interés en una posición determinada del cielo.

La forma en pixeles de la entrada es 128x128x3 y la forma de la salida es 128x128.

Para construir el sistema se dispone de un conjunto de "entrenamiento", es decir, muchos pares de la forma (X,Y) donde Y es la distribución de masa correcta para X. Sin embargo, el sistema se evaluará sobre un conjunto de pruebas, es decir, un conjunto de casos para los cuales los participantes sólo conocerán X.
## Links Importantes

* [Página Principal del evento](https://dataton.inf.utfsm.cl/)
* [Página del evento en Codabench](https://www.codabench.org/competitions/3583/#/pages-tab)
* [Un Drive con las lecturas realizadas](https://drive.google.com/drive/folders/1L9aRpMQ1WaiCz-u3MBoK-nQmLNkvShfT?usp=drive_link)
* [Overleaf para bitacora y tomar notas:](https://www.overleaf.com/read/gphwhzxdvwfv#7c86f3)

## Links para descargar los datos
### Entrenamiento
* [Link para descarga de datos 1](https://descargas.inf.santiago.usm.cl/train/1.tar.gz)
* [Link para descarga de datos 2](https://descargas.inf.santiago.usm.cl/train/2.tar.gz)
* [Link para descarga de datos 3](https://descargas.inf.santiago.usm.cl/train/3.tar.gz)
* [Link para descarga de datos 4](https://descargas.inf.santiago.usm.cl/train/4.tar.gz)
* [Link para descarga de datos 5](https://descargas.inf.santiago.usm.cl/train/5.tar.gz)
* [Link para descarga de datos 6](https://descargas.inf.santiago.usm.cl/train/6.tar.gz)
* [Link para descarga de datos 7](https://descargas.inf.santiago.usm.cl/train/7.tar.gz)
* [Link para descarga de datos 8](https://descargas.inf.santiago.usm.cl/train/8.tar.gz)

### Validación
*[Link para descarga de datos](https://descargas.inf.santiago.usm.cl/test_public.tar.gz)

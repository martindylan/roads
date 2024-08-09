# roads~
![img](https://raw.githubusercontent.com/martindylan/martindylan.github.io/master/static/media/roads.2fd9a094e152cde14122.png)  
Efecto de audio granular polifónico (varios "trenes" de granos en distintas alturas), desarrollado en [Pure Data](https://github.com/pure-data/pure-data) + [Camomile](https://github.com/pierreguillot/Camomile).  
Se puede utilizar como plugin VST3 o como abstracción dentro de Pure Data.

## instalación del plugin
Descargar de la [última release](https://github.com/martindylan/roads/releases/latest) el .zip que corresponda según sistema operativo y arquitectura, y extraer en la carpeta donde pertenezcan los plugins VST3.

## guía de uso
rate: velocidad de los granos

length: largo de los granos

(rate y length pueden determinarse en ms o sincronizarse con el tempo del proyecto)

chance: probabilidades de que suenen los granos

dirección: determina si los granos se reproducen normal (forward), de atrás para adelante (reverse) o ir cambiando aleatoriamente entre esas dos (random)

smear: cantidad de desplazamiento aleatorio de los granos en el tiempo, superponiendo así distintos momentos de la señal entrante armando una especie de nube

detune: rango de desafinación por grano en relación a la altura original, se determina en cents y puede ser positivo o negativo

feedback: cantidad de la señal granulada que se vuelve a ingresar en el sistema

voices: para cada una de las 6 voces se cuenta con un switch para prenderla/apagarla, un fader de volumen y un número de transposición en semitonos en relación a la altura original que puede ser positivo o negativo

forma de ventana: distintas envolventes para los granos

smooth: introduce un breve fade para reducir los clicks que generan las formas de ventana straight, down y up

## créditos
- [Pure Data](https://github.com/pure-data/pure-data) por Miller Puckette y muchxs más.
- [Camomile](https://github.com/pierreguillot/Camomile) por Pierre Guillot.

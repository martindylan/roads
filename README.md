# roads~
![img](https://raw.githubusercontent.com/martindylan/martindylan.github.io/master/static/media/roads.2fd9a094e152cde14122.png)  
Efecto de audio granular polifónico (hasta seis "trenes" de granos), desarrollado en [Pure Data](https://github.com/pure-data/pure-data) + [Camomile](https://github.com/pierreguillot/Camomile).  
Se puede utilizar como plugin VST3 o como abstracción dentro de Pure Data.

## instalación del plugin
Descargar de la [última release](https://github.com/martindylan/roads/releases/latest) el .zip que corresponda según sistema operativo y arquitectura, y extraer en la carpeta donde pertenezcan los plugins VST3.

## guía de uso
- **rate**: Frecuencia de emisión de los granos (ms o subdivisión)

- **length**: Duración de los granos (ms o subdivisión)

\**el switch a la izquierda de rate apaga la emisión automática de los granos*
\**rate y length pueden utilizar **sync** para definirse como una subdivisión del tempo actual del proyecto*

- **chance**: Probabilidad de que se emitan los granos, se recalcula para cada grano (0-100%)

- **dirección**: Determina si los granos reproducen la señal entrante de manera normal (forward), de atrás para adelante (reverse) o van cambiando aleatoriamente entre esas dos (random)

- **trigger**: Emite un grano de manera "manual"

- **smear**: Cantidad de desplazamiento aleatorio de los granos en el tiempo, superponiendo así distintos momentos de la señal entrante armando una especie de nube (0-100%)

- **detune**: Nivel de desafinación máxima por grano en relación a la altura original, puede ser positivo o negativo (cents)

- **stereo**: Nivel de paneo máximo por grano (0-100%)

- **feedback**: Cantidad de la señal granulada que se vuelve a ingresar al sistema (0-100%)

- **dry/wet**: Mezcla entre la señal original y la señal granulada (0-100%)

- **voices**: Para cada una de las 6 voces se cuenta con: un switch para prenderla/apagarla, un fader de volumen y un número de transposición en semitonos en relación a la altura original que puede ser positivo o negativo

- **forma de ventana**: Distintas envolventes para los granos

- **smooth**: Introduce un breve fade para reducir los clicks que generan las formas de ventana straight, down y up

- **gain**: Ganancia de salida (dB)

## créditos
- [Pure Data](https://github.com/pure-data/pure-data) por Miller Puckette y muchxs más.
- [Camomile](https://github.com/pierreguillot/Camomile) por Pierre Guillot.

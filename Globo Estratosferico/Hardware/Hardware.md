# Sistemas a Bordo

## Computadora de Energía
*	Monitoreo de individual de estado de baterías
*	Monitoreo de corriente individual de baterías
*	Control de carga individual de baterías
*	Conmutación de carga para dispositivos
*	Faro marcador
*	Mecánica para expulsar el globo
*	Monitoreo de expulsión de globo
*	Mecánica para expulsar el paracaídas
*	Monitoreo de expulsión de paracaídas

## Computadora de Telemetría

#### Modulo GSM/GPRS
*	Comunicación terrestre para recuperación al descenso
*	Transmite la ubicación atreves de la red celular
*	Permite comandos de control y monitoreo
*	Comunicacion Bidireccional

#### Modulo de 900 MHz
*	Comunicación terrestre de telemetría y control
*	Transmisión de imágenes en tiempo real
*	Control y monitoreo de los sistemas a bordo
*	Transmisión de telemetría en tiempo real
*	Comunicacion Bidireccional

## Computadora de Imagen

#### Cámara VGA TTL a tierra
*	Capta imágenes del estado del globo al ascenso
*	Capta imágenes del lugar del aterrizaje para recuperación
*	Almacenamiento de imágenes en memoria interna
*	Transmisión de imágenes en tiempo real

#### Cámara VGA TTL Móvil
*	Capta imágenes del exterior
*	Movimiento en tiempo real X Y
*	Transmisión de imágenes en tiempo real
*	Almacenamiento de imágenes en memoria interna
*	Para referencia de imágenes de GoPro

#### Cámara GoPro
*	Almacenamiento de imágenes en memoria interna
*	Movimiento en tiempo real X Y
*	Imágenes en alta resolución
*	Captura en tiempo lapsado
*	Batería individual
*	Alimentación externa

## Computadora de Métrica
*	Monitoreo de sensores
*	Calculo de datos censados
*	Almacenamiento de datos en logger
*	Transmisión de datos en tiempo real
*	Consulta interna de datos para sistemas a bordo

#### Monitoreo Atmosférico
*	Temperatura Interior
*	Temperatura Exterior
*	Barómetro Interior del globo
*	Barómetro Exterior
*	Humedad Interior
*	Humedad Exterior

#### Monitoreo Físico
*	Acelerómetro X Y Z
*	Giroscopio X Y Z

#### Monitoreo de Orientación
*	GPS Sistema de Posicionamiento Global
*	Compas Magnético

#### Monitoreo de Tiempo
*	RTC Real Time Clock

## Computadora de Comunicaciones
*	Control de flujo de datos entre sistemas a bordo
*	Permite hacer puentes de comunicaciones entre dos o varios sistemas
*	Comunicaciones Full Duplex
*	Puentes de comunicaciones independientes y simultáneos

# Notas sobre la versión

## v0.3
* Corregido - GPS a computadora de métrica
* Agregado - Computadora de Comunicaciones Internas

## v0.2
* Corregido - RTC a computadora de métrica

## v0.1
* Agregado - RTC a computadora de comunicaciones

## v0.0
#### Sensores
* Acelerómetro X, Y, Z
* Giroscopio X, Y, Z
* Humedad
* Temperatura
* Presión Atmosférica dentro del globo
* Presión Atmosférica exterior
* Expulsión de paracaídas
* Estado de Batería
* Corriente en Batería
* Estado de Batería de Cámara

#### Comunicaciones
* Enlace Inalámbrico bidireccional RF
* Enlace Inalámbrico Celular GPRS
* GPS

#### CPU
* Arduino Mega
* Almacenamiento SD

#### Control
* Control de disparo de cámara
* Control de On/Off de cámara
* Control de comunicaciones internas
* Expulsión de globo
* Expulsión de paracaídas

#### Cámara
* Cámara digital 12MPx
* Enfoque automático
* Balance de Blancos
* Almacenamiento SD

#### Mecánica
* Separación de Globo
* Expulsión de Paracaídas

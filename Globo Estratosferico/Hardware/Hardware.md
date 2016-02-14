# Sistemas a Bordo

### Computadora de Energia
* Monitoreo de individual de estado de baterias
* Monitoreo de corriente individual de baterias
* Control de carga individual de baterias
* Conmutacion de carga para dispositivos
* Faro marcador
* Mecanica para expulsar el globo
* Monitoreo de expulsion de globo
* Mecanica para expulsar el paracaidas
* Monitoreo de expulsion de paracaidas

### Computadora de Telemetria

#### Modulo GSM/GPRS
* Comunicacion terrestre para recuperacion al desenso
* Trensmite la ubicacion atravez de la red celular
* Permite comandos de control y monitoreo

#### Modulo de 900 MHz
* Comunicacion terreste de telemetria y control
* Transmicion de imagenes en tiempo real
* Control y monitoreo de los sistemas a bordo
* Transmicion de telemetria en tiempo real

### Computadora de Imagen

#### Camara VGA TTL a tierra
* Capta imagenes del estado del glogo al ascenso
* Capta imagenes del lugar del aterrizaje para recuperacion
* Almacenamiento de imagenes en memoria interna
* Transmicion de imagenes en tiempo real

#### Camara VGA TTL Movil
* Capta imagenes del exterior
* Movimiento en tiempo real X Y
* Transmicion de imagenes en tiempo real
* Almacenamiento de imagenes en memoria interna
* Para referencia de imagenes de GoPro

#### Camara GoPro
* Almacenamiento de imagenes en memoria interna
* Movimiento en tiempo real X Y
* Imagenes en alta resolucion
* Captura en tiempo lapsado
* Bateria individual 
* Alimentacion externa

### Computadora de Metrica
* Monitoreo de sensores
* Calculo de datos sensados
* Almacenamiento de datos en logger
* Transmicion de datos en tiempo real
* Consulta interna de datos para sistemas a bordo

#### Monitoreo Atmosferico
* Temperatura Interior
* Temperatura Exterior
* Barometro Interior del globo
* Barometro Exterior
* Humedad Interior
* Humedad Exterior

#### Monitoreo Fisico
* Acelerometro X Y Z
* Giroscopio X Y Z

#### Monitoreo de Orientacion
* GPS Global Poscicion Sistem
* Compas Magnetico

#### Monitoreo de Tiempo
* RTC Real Time Clock

### Computadora de Comunicaciones
* Control de flujo de datos entre sistemas a bordo
* Permite hacer puentes de comunicaciones entre dos o varios sistemas
* Comunicaciones Full Duplex
* Puentes de comunicaciones independientes y simultaneos

# Notas dobre la version

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

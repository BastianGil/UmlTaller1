# UmlTaller1-Eclipse
## Main
Clase que contiene el Api de processing y ejecuta el Hilo princpal
### Variables
* **app:Logica:** Objeto tipo Logica parahacer udo del PApplet
### Metodos
* **main(String[]):void:** Medodo que ejecuta la aplicacion

* **settings():void:** Definir propiedades del lienz

* **Setup():void:** Medod donde se inicializan las variables

* **draw:void:** Hilo principal de la aplicacion, interfaz grafica

* **mousePressed:void:** Medodo que ejecuta las accionees del mouse 

## Logica
Clase que contine la interfaz grafica y reliza los pocesos
### Variables
* **diabetes:int:** Variable numerica que representa uno de los estados del juego
* **Cancer** Variable numerica que representa uno de los estados del juego
* **problemasdc:** Variable numerica que representa uno de los estados del juego
### Metodos
* **Logica(PApplet):** Cosstructor clase Logica

## Servidor
Extremo de la coneccion, recibe y envia datos 
### Variables
* **s:Socket:** Acepta las conecciones 
* **ss:ServerSocket:** Abre la coneccion, epieza a esuchar
### Metodos
* **enviar():void:** Datos que se envian del servidor al cliente

## Reseptor
Recive y responde 
### Variables
* **s:Socket:** Crea el flujo de datos
### Metodos
* **Reseptor(Sokcket): void:** Constructor de clase receptor 

## Thread
Crea objetos con caracteristicas de Hilos
### Variables
### Metodos
* **run():void:** Metodo que ejecuta el hilo

## Elemento
Crea los objetos recogibles del juego
### Variables
* **app:PApplet:** llama el uso de los elementos en el PApplet
* **x:float:** Posicion de los elementos e el eje x 
* **y:float:** Posicion de los elementos en el eje y
* **Imagen:PImage[]:** Numero de imagenes que reprecentan todod lo elemntos recogibles

### Metodos
* **Elemento(int,int,PApplet)

## Balon
### Metodos
* **Balon(PApplet,int,int):** Costructor de Balon
* **pintar():void:** Heredado de Elemento pone la imagen del Balon en el lienzo

## Zanahoria
### Metodos
* **Zanahoria(PApplet,int,int):** Costructor de Zanahoria
* **pintar():void:** Heredado de Elemento pone la imagen del Balon en el lienzo

## Libro
### Metodos
* **Libro(PApplet,int,int):** Costructor de Libro
* **pintar():void:** Heredado de Elemento pone la imagen del Libro en el lienzo


## Mc
### Metodos
* **Mc(PApplet,int,int):** Costructor de Mc
* **pintar():void:** Heredado de Elemento pone la imagen del Mc en el lienzo

## Iphone
### Metodos
* **Iphone(PApplet,int,int):** Costructor de IPhone
* **pintar():void:** Heredado de Elemento pone la imagen del Iphone en el lienzo

## Coca
### Metodos
* **Coca(PApplet,int,int):** Costructor de Coca
* **pintar():void:** Heredado de Elemento pone la imagen del Coca en el lienzo


## Personaje
Clase que Crea un objeto de tipo personaje, el objeto o jugador prinscipal
### Variables
* **app:PApplet:** llama el uso de los elementos en el PApplet
* **pos:PVector:** Representa la pocicion del jugador
* **x:float:** Componente en eje x de la poscicion
* **vel:Pvector:** cantida de cambio en salto del personaje
* **inmagen:PImage:** gif que forman la imagen del personaje e movimiento
### Metodos
* **Personaje(PApplet,int,int):** Costructor clase personaje
* **pintar:void:** Metodo abtracta que pinta a los personajes
* **mover():void:** Reprecenta el movimiento horozontal y vertical del personaje
* **morir():**representa la muerte de uno de los personajes y el fin del jugo para este

* **getX():float:** Obtener valor de la variable x
* **getY():float:** Obtener valor de la variable y
* **getVelx()float::** Obtener valor de la variable  velx
* **getVely():float:** Obtener valor de la variable vely

* **setX():void:** Modificar el valor de la variable x
* **setY():void:** Modificar el valor de la variable y
* **setVelx():void:** Modificar el valor de la variable velx
* **setVely():void:** Modificar el valor de la variable vel y


## Personaje1
Personaje con caracteristicas especiales
### Metodos
* **Perso1(PApplet,int,int):** Costructor de personaje 1
* **pintar():void:** Heredado de personaje pone la imagen del personaje en el lienzo

## Personaje2
Personaje con caracteristicas especiales
### Metodos
* **Perso2(PApplet,int,int):** Costructor de personaje 2
* **pintar():void:** Heredado de personaje pone la imagen del personaje en el lienzo



# UmlTaller1-Android Studio
## Main
Clase que ejecutable
### Variables
* **btn_go:Button:** Variable que reprecenta el boton adelante
* **btn_up:Button:** Valiable que reprecenta el votonde saltar
* **iv_perso:ImageView:** Imagen del personaje en pantalla
### Metodos
* **OnCreate:** Ejecuta la aplicacion

## Thead
Crea objetos con caracteristicas de Hilos
### Variables
### Metodos
* **run():void:** Metodo que ejecuta el hilo

## Cliente
Extremo de la coneccion, establece coneccion
### Variables
* **s:Socket:** Comenzar conexiones
### Metodos
* **Cliente(MainActivity)** Permite que se observable las interacciones de la conexion
* **enviar():void:** Datos que se envian del cliente al servidor

## Reseptor
Envia y recive informacion
### Variables
* **s:Socket:** Crea el flujo de datos
### Metodos
* **Reseptor(Sokcket): void:** Constructor de clase receptor 

## [Interfaz] onMessage
Crea el patron observer para mostrar lo envido por el servidor
## Metodos
* **OnReceived():String:** recibe el mensaje enviado por el servidor




























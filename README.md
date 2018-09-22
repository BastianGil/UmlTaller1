# UmlTaller1
## Main
Clase que contiene el Api de processing y ejecuta el Hilo princpal
### Variables
* **app:Logica:** Objeto tipo Logica parahacer udo del PApplet
### Metodos
* **main(Stringg[]):void:** Medodo que ejecuta la aplicacion

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
* **-s:Socket:** Acepta las conecciones 
* **-ss:ServerSocket:** Abre la coneccion, epieza a esuchar
### Metodos
* **enviar():void:** Datos que se envian del servidor al cliente

## Reseptor
Resive y responde 
### Variables
* **-s:Socket:** Crea el flujo de datos
### Metodos
* **Reseptor(Sokcket): void:** Constructor de clase receptor 

## Thead
Crea objetos con caracteristicas de Hilos
### Variables
### Metodos
* **run():void:** Metodo que ejecuta el hilo

## Elementos 
Crea los objetos recogibles del juego
### Variables
* **#app:PApplet:** llama el uso de los elementos en el PApplet
* **x:float:** Posicion de los elementos e el eje x 
* **y:float:** Posicion de los elementos en el eje y
* **Imagen:PImage[]:** Numero de imagenes que reprecentan todod lo elemntos recogibles

### Metodos
* **Elementos(int,int,PApllet)

## Balon
### Metodos

## Zanahoria
### Metodos

## Libro
### Metodos

## Mc
### Metodos

## Iphone
### Metodos

## Coca
### Metodos

## Personaje
Clase que Crea un objeto de tipo personaje, el objeto o jugador prinscipal
### Variables

### Metodos

## Personaje1
### Metodos






























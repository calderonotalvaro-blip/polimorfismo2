¿Por qué Bicicleta funcionó en mostrar() y en masEconomico() sin cambiar una sola línea de Flota?
-porque flota trabaja contra el tipo de base como vehiculo 

¿Por qué Vehiculo es abstracta y Moto no? ¿Qué pasaría si Moto también lo fuera?
-vehiculo es abstracta por que la tarifa kilometros depende del tipo de transporte mientras que moto tiene su propia tarifa 

 ¿Por qué Bodega implementa Asegurable pero no hereda de Vehiculo?
 -porque bodega no es un vehiculo pero si es asegurable 

 ¿Qué diferencia hay entre super(placa, capacidadKg) y super.describir()?
-invoca el constructor de la superclase Vehiculo (y solo puede ir en la primera línea del constructor de la subclase) para inicializar los atributos heredados.

Cierre del curso: explica con tus palabras qué es la POO y señala en tu código del taller un ejemplo de cada
pilar: abstracción, encapsulamiento, herencia y polimorfismo.
-poo:programacion orientada a objetos es un paradigma que organiza el sofware que combinan atributos y metodos 
-abstraccion:definen qué se debe hacer sin fijar cómo lo calcula cada tipo específico
-Encapsulamiento:consiste en ocultar los detalles internos de un objeto y controlar el acceso a sus datos
-es otra clase que viene de clase ya hecha 
-Polimorfismo:es que distintas clases respondan a un mismo metodo cada una con su propia implementacion 

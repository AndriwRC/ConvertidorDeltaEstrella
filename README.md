
# Convertidor Delta-Estrella

_Con el propósito de poder simplificar el análisis de un circuito, a veces es conveniente poder mostrar todo o una parte del mismo de una manera diferente, pero sin que el funcionamiento general de éste cambie. Algunos circuitos tienen un grupo de resistores (resistencias) que están ordenados formando: un triángulo (circuito en configuración triángulo) ó una estrella (circuito en configuración estrella). y aquí es donde entra el convertidor que no solo obtiene los resultados de un formato a otro y viceversa, sino también adaptando sus nuevos valores_

## Comenzando 🚀

_Estas son las formulas utilizadas en el convertidor Delta a Estrella_

```
– R1 = (Ra x Rc) / (Ra + Rb + Rc)
– R2 = (Rb x Rc) / (Ra + Rb + Rc)
– R3 = (Ra x Rb) / (Ra + Rb + Rc)
```

_Y estas son las formulas utilizadas en el convertidor Estrella a Delta_

```
– Ra = [ (R1 x R2) + (R1 x R3) + (R2 x R3) ] / R2
– Rb = [ (R1 x R2) + (R1 x R3) + (R2 x R3) ] / R1
– Rc = [ (R1 x R2) + (R1 x R3) + (R2 x R3) ] / R3
```

### Pre-requisitos 📋

_Estas son las funcionalidades que requiere el programa para llevarse a cabo_

_Conocimiento básico de resistencia y circuitos_
_Tener instalado el Apache Netbeans con Java_

```
https://netbeans.apache.org
https://www.java.com/es/
```

### Funcionalidad 🔧

_Serie de pasos bajo el entorno para que el programa se ejecute correctamente_

_Se colocan los datos de las resistencias en los cuadros seleccionados sobre cada uno de los ejes y se presiona "_


## Construido con 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Adobe Illustrator](https://www.adobe.com/la/products/illustrator.html) - Diseño visual del convertidor
* [JFrame](https://docs.oracle.com/javase/7/docs/api/javax/swing/JFrame.html) - Interfaz visual de Java

## Contribuyendo 🖇️

Este trabajo fue construido y diseñado para la clase de MICROPROCESADORES - PRESENCIAL-18817 con el Profesor Johan Mardini Bovea para la Corporación Universitaria de la Costa CUC


## Autores ✒️

_Autores y colaboradores que llevaron a cabo el proyecto_

* **Andriw Rollo** - *Trabajo Inicial y Final* - [AndriwRC](https://github.com/AndriwRC)
* **Camilo Ibañez** - *Trabajo Inicial y Final* - [xFreik](https://github.com/xFreik)
* **Bryan Romero** - *Documentación y descripción* - [Bromero01](https://github.com/Bromero01)


También puedes mirar la lista de todos los [contribuyentes](https://github.com/AndriwRC/ConvertidorDeltaEstrella/graphs/contributors) quíenes han participado en este proyecto excepto uno... 

## Licencia 📄

Este proyecto no está bajo licencia de ningún tipo

## Expresiones de Gratitud 🎁

* Gracias por probar y hacer uso de nuestro proyecto, sea para fines educativos, laborales o personales cumpliendo el buen uso de este.

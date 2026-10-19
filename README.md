# Ejercicio 3 - Transición de Estados (Auto)

## Explicación del programa

En este ejercicio se creó una clase llamada `Auto` que contiene los siguientes atributos de instancia:
* `marca`, de tipo `String`.
* `modelo`, de tipo `String`.
* `encendido`, de tipo `boolean` (que por defecto inicia en `false`).

Se definió un constructor parametrizado para inicializar la marca y el modelo del vehículo mediante la referencia `this`.

Además, la clase cuenta con tres métodos de instancia de tipo `void`:
* `encender()`: Cambia el atributo `encendido` a `true`.
* `apagar()`: Cambia el atributo `encendido` a `false`.
* `mostrarEstado()`: Evalúa mediante una estructura condicional `if/else` el valor del atributo `encendido` e imprime en consola si el auto se encuentra apagado o prendido.

Luego, dentro del método `main`, se creó un objeto de la clase `Auto` instanciándolo de la siguiente manera:
`Auto auto1 = new Auto("toyota", "nuevo");`

Finalmente, se simuló la secuencia de transición de estados invocando los métodos en el siguiente orden: `mostrarEstado()`, `encender()`, `mostrarEstado()`, `apagar()` y `mostrarEstado()`.

## Lógica utilizada

La lógica del programa consiste en:
* Crear la clase `Auto`.
* Definir sus atributos `marca`, `modelo` y `encendido`.
* Crear el constructor que recibe e inicializa la marca y el modelo.
* Definir el método `encender()` para modificar el estado del atributo `encendido` a `true`.
* Definir el método `apagar()` para modificar el estado del atributo `encendido` a `false`.
* Definir el método `mostrarEstado()` para consultar el atributo booleano mediante un `if/else` y mostrar el mensaje correspondiente.
* Instanciar un objeto `auto1` en la clase principal y llamar secuencialmente a los métodos para verificar los cambios de estado interno durante su ciclo de vida.

De esta manera se demuestra cómo los métodos de una clase pueden modificar y consultar el estado interno de un objeto a lo largo del tiempo.

## Resultado de la ejecución

La ejecución del programa muestra en la consola la secuencia de estados del vehículo:
* el auto esta apagado
* el auto esta prendido
* el auto esta apagado

## Captura de pantalla
<img width="1674" height="214" alt="ejercicio 3" src="https://github.com/user-attachments/assets/48d60639-0276-4148-acfb-eb1f7a48507c" />

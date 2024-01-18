# Desafio2

## Descripción

<p align="justify">Este programa, escrito en Java y utilizando el framework Android, es una actividad de pantalla completa que muestra y oculta la interfaz de usuario del sistema (es decir, la barra de estado y la barra de navegación/sistema) con la interacción del usuario.</p>

## Funcionalidad

<p align="justify">El programa tiene la capacidad de ocultar automáticamente la interfaz de usuario del sistema después de un cierto retraso tras la interacción del usuario. Este retraso se puede configurar con la constante `AUTO_HIDE_DELAY_MILLIS`.</p>

<p align="justify">Además, el programa tiene en cuenta que algunos dispositivos más antiguos necesitan un pequeño retraso entre las actualizaciones de los widgets de la interfaz de usuario y un cambio de la barra de estado y de navegación. Este retraso se puede configurar con la constante `UI_ANIMATION_DELAY`.</p>

<p align="justify">El programa también incluye un detector de toques para usarlo en los controles de la interfaz de usuario en el diseño para retrasar la ocultación de la interfaz de usuario del sistema. Esto es para prevenir el comportamiento brusco de los controles que desaparecen mientras se interactúa con la interfaz de usuario de la actividad.</p>

## Métodos

- `suma(ArrayList<Integer> lista)`: Este método recibe una lista de números enteros y calcula la suma de los múltiplos de 3 en la lista.
- `promedio(double suma, int n)`: Este método recibe la suma de los múltiplos de 3 y el número total de múltiplos de 3, y calcula el promedio.

## Uso

<p align="justify">Para usar este programa, simplemente ejecute el método `main`. Luego, siga las instrucciones en la consola para ingresar los números.</p>

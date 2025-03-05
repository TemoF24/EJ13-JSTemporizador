# Procesamiento de Promesas en Paralelo

Este repositorio contiene un ejemplo de cómo manejar múltiples promesas en paralelo utilizando JavaScript en una página web estática. Se utiliza `Promise.all` para ejecutar tres temporizadores en paralelo y mostrar los resultados una vez que todos hayan terminado.

## Descripción

El proyecto demuestra el uso de promesas en JavaScript para ejecutar múltiples tareas de manera asíncrona. En este caso, se simulan tres temporizadores con diferentes tiempos de espera, y se muestran los resultados una vez que todos se han completado.

## Estructura del Proyecto

El proyecto está compuesto por un solo archivo HTML que incluye código HTML, CSS y JavaScript embebido. Los componentes son:

1. **HTML**:
   - Estructura básica de una página web con un título y un área para mostrar los resultados.
   
2. **CSS**:
   - Estilos básicos para el cuerpo de la página y los resultados.

3. **JavaScript**:
   - Función `temporizador(ms, mensaje)` que crea promesas con un tiempo de espera.
   - Función `ejecutarTemporizadores()` que ejecuta tres temporizadores en paralelo y muestra los resultados.

## Funcionalidad

- Al cargar la página, tres temporizadores se ejecutan en paralelo.
- Los resultados de cada temporizador se muestran en un contenedor HTML una vez que todos los temporizadores hayan terminado.

## Requisitos

Este proyecto no requiere ninguna dependencia externa. Solo es necesario un navegador web moderno con soporte para JavaScript.

## Instalación

1. Clona el repositorio en tu máquina local:

    ```bash
    git clone https://github.com/tu_usuario/procesamiento-promesas-paralelo.git
    ```

2. Abre el archivo `index.html` en tu navegador:

    ```bash
    open index.html
    ```

## Uso

1. Abre el archivo `index.html` en cualquier navegador web.
2. Al cargar la página, verás que los temporizadores comienzan a ejecutarse en paralelo.
3. Los resultados de los temporizadores se mostrarán en el área de resultados en la página.

## Ejemplo de Resultados

Una vez que los temporizadores se completen, el contenedor de resultados mostrará algo similar a lo siguiente:

Temporizador 1 finalizado después de 2 segundos Temporizador 3 finalizado después de 3 segundos Temporizador 2 finalizado después de 5 segund

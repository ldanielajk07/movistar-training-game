# MovistarChat · Simulador Comercial

MovistarChat es un simulador web de formación comercial diseñado para practicar conversaciones de atención al cliente siguiendo un proceso comercial estructurado.

## Objetivo

Resolver casos de atención al cliente y completar la conversación siguiendo las distintas etapas del proceso. Al finalizar cada sesión, el sistema muestra una puntuación según el desempeño.

## Funcionalidades

- Casos aleatorios de atención al cliente.
- Categorías: portabilidad, facturas, averías, reclamaciones, pedidos y fidelización.
- Niveles de dificultad: fácil, medio, difícil y expertos.
- Estados emocionales que pueden cambiar según la calidad de las respuestas.
- Evaluación de empatía, diagnóstico, comunicación, proceso y resolución.
- Seguimiento del progreso y estadísticas por categoría.
- Exportación de resultados a CSV y JSON.
- Guardado local del historial mediante `localStorage`.

## Proceso de atención

Las conversaciones siguen estas fases:

1. Identificación
2. Diagnóstico
3. Explicación
4. Gestión
5. Validación
6. Cierre

## Uso

No requiere instalación ni dependencias externas.

1. Descarga o clona el repositorio.
2. Abre `index.html` en un navegador web moderno.
3. Selecciona la dificultad o deja la opción "Todos".
4. Responde las consultas del cliente en el cuadro de texto.
5. Completa todas las fases para recibir la evaluación final.

También puede ejecutarse mediante GitHub Pages si el repositorio tiene publicada la página.

## Archivos

- `index.html`: contiene toda la estructura, estilos y lógica JavaScript del simulador.
- `README.md`: descripción y guía de uso del proyecto.

## Evaluación

Cada sesión obtiene una puntuación por áreas específicas y una nota global. El progreso puede consultarse en la barra lateral, que muestra:

- Sesiones completadas.
- Promedio de puntuación.
- Mejor resultado.
- Nivel del jugador.
- Estado del cliente.
- Rendimiento por categoría.
- Últimas sesiones.

El nivel de rendimiento se calcula así:

- Bronce: menos de 70% de promedio.
- Plata: desde 70%.
- Oro: desde 80%.
- Experto: desde 90%.

## Datos locales

Las estadísticas se guardan únicamente en el navegador con `localStorage`. Los datos no se envían a ningún servidor.

# Mapa Mental - Hacer una búsqueda con filtros en Airbnb

## 📌 Descripción
Este proyecto muestra un mapa mental del flujo de usuario en el proceso de hacer una búsqueda de alojamiento utilizando los filtros de la página [airbnb.mx](https://www.airbnb.mx).  
El mapa está enfocado en la lógica de la funcionalidad del sitio y explora los requisitos de cada elemento, así como las restricciones de campos, validaciones, etc.

## 🎯 Objetivo
El mapa mental fue creado para organizar visualmente los requisitos y elementos clave que debe considerar un QA al momento de probar una funcionalidad web.

## 📌 Importancia de los Mapas Mentales en QA
Los mapas mentales ayudan a:
- Organizar ideas de manera clara y visual.
- Identificar flujos de usuario y posibles puntos de fallo.
- Detectar escenarios de prueba alternativos o negativos.
- Entender mejor los requerimientos funcionales y colaborar con el equipo de desarrollo y producto.

## 🧪 Ejemplo de Aplicación
A partir de este mapa mental, puedo identificar varios escenarios de prueba, como:
- Qué sucede si el usuario introduce datos inválidos.
- Qué pasa si omite campos obligatorios.
- Cómo responde la aplicación si se rompe el flujo en un punto específico.
- Qué validaciones existen (o faltan) en los diferentes filtros disponibles.

## 🔧 Herramientas utilizadas
- **FigJam** – para la creación del mapa mental.
- **GitHub** – para documentar y compartir el ejercicio.

## 🖼️ Mapa Mental
👉 [Ver el mapa mental en FigJam](https://www.figma.com/board/yYjy142l8iNR0QW05oeyPm/Mind-Map-Airbnb?node-id=0-1&t=HlfeLdhFRGIgBw41-1)

![Mapa Mental QA](https://github.com/paulinaburruel/paulinaburruel-qa-mapa-mental-airbnb/blob/c57af99ee333ec1fc3703aa3386d436f61f7fba1/mapa-mental-airbnb.jpg)

## 📝 Reflexión final
Este ejercicio me permitió estructurar mejor mi pensamiento como QA y reforzar la importancia de analizar una funcionalidad desde diferentes perspectivas: la del usuario, la del negocio y la técnica.

Al tratarse de una página pública de la cual no tengo acceso a documentación oficial ni requisitos funcionales, crear este mapa mental me ayudó a comprender mejor su estructura e incluso a detectar errores o áreas de mejora.

Un ejemplo de esto es el comportamiento en el flujo `Barra de búsqueda > Fecha > Meses`, donde el botón *“Elige una fecha de finalización”* no parece tener un objetivo o función clara, ya que no modifica las fechas seleccionadas, a diferencia del botón *“Elegir una fecha de inicio”*. Este tipo de hallazgos reflejan cómo una herramienta visual como el mapa mental puede apoyar en el análisis de funcionalidades reales.

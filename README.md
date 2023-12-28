# Conversor de Monedas Nacional 🌐

## Descripción
Esta aplicación web proporciona una interfaz sencilla y efectiva para convertir montos en Pesos Chilenos (CLP) a otras monedas (USD y EURO) utilizando datos actualizados de tipos de cambio. La herramienta está diseñada para ser intuitiva y fácil de usar, asegurando que los usuarios puedan obtener la información que necesitan con rapidez y precisión.

## Características
- **Librerias y Estilos**: Se ha utilizado la libreria Chart.js para la gráfica y Bootstrap para los estilos, ademas de CSS.

- **Obtención de Datos de Cambio**: Utiliza la API de [mindicador.cl](https://mindicador.cl/api) para obtener los datos más recientes sobre los tipos de cambio, asegurando que la conversión esté siempre actualizada.

- **Conversión de Monedas**: Calcula y muestra el resultado de la conversión directamente en la página, permitiendo a los usuarios ver la cantidad equivalente en la moneda seleccionada.

- **Selección de Moneda**: Ofrece un selector con varias opciones de moneda (Dólar y Euro), lo que permite a los usuarios elegir fácilmente a cuál desean convertir el monto ingresado.

- **Manejo de Errores**: Implementa bloques `try-catch` para gestionar las solicitudes de datos a la API. Cualquier error en la petición es capturado y mostrado de manera amigable en el DOM.

- **Visualización Gráfica**: Incluye una representación gráfica del historial de conversión de los últimos 10 días para la moneda seleccionada, proporcionando un contexto adicional sobre el rendimiento de la moneda a lo largo del tiempo.

## Uso
Para realizar una conversión, simplemente:
1. Ingrese el monto en Pesos CLP en el campo correspondiente.
2. Seleccione la moneda a la que desea convertir el monto.
3. Presione el botón "Buscar" para realizar la conversión.
4. Revise el resultado y el gráfico de historial que aparece debajo del formulario.

## Contribuciones
Las contribuciones son siempre bienvenidas. Si tienes alguna sugerencia o corrección, por favor, envía un pull request o abre un issue.

## Autor
Jorge Espinoza

---

Ⓒ 2023 Jorge Espinoza. Todos los derechos reservados.

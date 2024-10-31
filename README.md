# 🌎  Conversor-de-Monedas en tiempo real
Este repositorio contiene un proyecto Java de conversión de moneda en tiempo real, que permite convertir cantidades entre divisas utilizando datos actualizados desde una API de tasas de cambio. Con una interfaz de línea de comandos sencilla, el usuario puede seleccionar fácilmente las opciones de conversión disponibles.
## 🛠️ Funcionalidades
💱 Conversión entre múltiples monedas desde COP a las monedas establecidas: 
COP
USD
EUR 
MXN
ARS 
GBP.

Actualización en tiempo real de las tasas de cambio mediante una conexión con una API.
Validación de valores ingresados, con mensajes de alerta para cantidades no válidas.
Menú de navegación intuitivo para seleccionar opciones de conversión.

## 📋 Estructura del Proyecto
Principal.java: Clase principal que muestra el menú y recibe las opciones de usuario.
Conversor.java: Clase que gestiona las conversiones y validaciones de cantidades.
ApiConnector.java: Clase que se conecta a la API de tasas de cambio para obtener las tasas de conversión actualizadas.
Requisitos
Java 11 o superior
Gson: Librería para el manejo de datos JSON obtenidos de la API.
Ejecución
Clona el repositorio.
Configura las dependencias en tu entorno de desarrollo.
Compila y ejecuta la clase Principal para comenzar a usar el conversor.
Este proyecto es ideal para quienes deseen aprender sobre integración de APIs en Java y desarrollar aplicaciones con tasas de cambio en tiempo real.

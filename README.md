# TecnoMovil Data
Actividad evaluativa 2 de Programación Orientada a Objetos II.

El programa procesa registros simulados de transporte urbano mediante funciones puras, expresiones lambda, streams y colecciones inmutables. Calcula la afluencia por estación, las horas pico, las rutas más utilizadas, los patrones por usuario, el tiempo promedio de viaje y las rutas con sobrecarga.

## Ejecución en Visual Studio Code
Abre la carpeta del repositorio en Visual Studio Code. El equipo debe tener Java 17 o superior disponible en la terminal.

Selecciona **Terminal → Nueva terminal**. Desde la carpeta que contiene **TecnoMovil.java**, ejecuta la prueba de doce viajes:

```powershell
java TecnoMovil.java 12 3 secuencial
```

Para procesar cien mil viajes en modo paralelo:

```powershell
java TecnoMovil.java 100000 10000 paralelo
```

Los argumentos corresponden al número de viajes, el umbral de ocupación y el modo de procesamiento. Cada viaje genera dos registros, uno de entrada y otro de salida.

## Archivos de la entrega
- **TecnoMovil.java** contiene el código fuente.
- **EA2_Creación_de_repositorio_Altamiranda_Geiner.pdf** contiene el informe.
- **evidencias/ejecucion_1.png** muestra la ejecución de doce viajes.
- **evidencias/ejecucion_2.png** muestra la ejecución de cien mil viajes.

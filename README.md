# Laboratorio 1: COMPARACIÓN DE TECNOLOGÍA CMOS y TTL

Electrónica Digital, Grupo 1 - Equipo 4.
Universidad Nacional de Colombia

Estudiantes: 
Juan Felipe Rátiva Sánchez, jrativas@unal.edu.co
Santiago Gomez Camargo, sgomezcam@unal.edu.co
Cristian Mauricio Gil Pineda crgilp@unal.edu.co

# Objetivos
Plasme aquí los objetivos

# Recursos requeridos
    1.Negador TTL 74LS04
    2.Negador CMOS CD4069
    3.Simulador
    4.Modelos spice
    5.Datasheets

## INTRODUCCIÓN
Aquí va la introducción del informe

## MARCO TEÓRICO
Las compuertas lógicos son circuitos electrónucos que estan internamente conformados por transistores que se encuentran en arreglos especificos segun el tipo de compuerta y la familia a la que pertenezca. Su objetivo principal es breindar una señal de salida en respuesta a operaciones booleanas. En esta ocasión se observara el funcionamiento de las fmilias TTL y CMOS. Las tecnologías TTL (Transistor-Transistor Logic) y CMOS (Complementary Metal-Oxide-Semiconductor) son dos de las más comunes para construir estas compuertas. Cada una tiene aplicaciones distintas, esto debido a sus características, ventajas y limitaciones.

### Compuertas TTL
Las compuertas TTL están basadas en transistores bipolares, que forman circuitos lógicos como AND, OR, NOT, entre otros. Estas fueron las primeras tecnologías digitales de alta velocidad ampliamente adoptadas.

Características principales:
- Tensión de alimentación típica: 5 V.
- Niveles lógicos:
- Bajo: 0 V a 0.8 V.
- Alto: 2 V a 5 V.
- Velocidad de operación: rápida, típica en nanosegundos (ns).
- Consumo de potencia: relativamente alto debido al uso de transistores bipolares.

Ventajas de TTL
- Alta velocidad de conmutación.
- Mejor tolerancia al ruido en aplicaciones antiguas (mayor corriente de salida).
- Compatible con dispositivos de la misma familia.

### Compuertas CMOS
Las compuertas CMOS están basadas en transistores de efecto de campo (MOSFET) de canal N y P. Son ampliamente utilizadas en dispositivos modernos debido a su bajo consumo de energía.

Características principales:
- Tensión de alimentación típica: 3.3 V, 5 V o incluso menos en dispositivos modernos.
- Niveles lógicos:
- Bajo: 0 V a 0.3 V (para 3.3 V de alimentación).
- Alto: 0.7 Vcc a Vcc.
- Velocidad de operación: depende del diseño, más lenta que TTL en configuraciones clásicas pero más eficiente en versiones modernas.
- Consumo de potencia: muy bajo en estado estático (solo durante transiciones de encendido/apagado).

Ventajas de CMOS
- Consumo de potencia extremadamente bajo.
- Alta densidad de integración (millones de compuertas en un chip).
- Mayor rango de tensiones de alimentación en tecnologías modernas.
- Parámetros Importantes: Fan-Out y Tiempos de Subida

Cálculo del Fan-Out
El fan-out se define como la cantidad máxima de entradas de otras compuertas que una compuerta puede manejar sin degradar significativamente sus niveles lógicos.

## RESULTADOS DE SIMULACIÓN 
## SIMULACIONES
Adjuntar simlaciones pertinentes

## RESULTADOS EXPERIMENTALES
Adjuntar simlaciones pertinentes experimentales

## ANÁLISIS Y COMPARACIÓN DE RESULTADOS 

## CONCLUSIONES

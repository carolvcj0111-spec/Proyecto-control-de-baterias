
# Proyecto: Control de Baterías (BMS)

Este repositorio contiene el desarrollo completo de un **Sistema de Gestión de Baterías (BMS)**
diseñado para monitorear, proteger y controlar la carga y descarga de baterías de litio de 3.7V.
El sistema es capaz de gestionar múltiples celdas de forma independiente, garantizando su
correcto funcionamiento y prolongando su vida útil.

## ¿Cómo funciona el sistema?

El BMS desarrollado cuenta con los siguientes bloques funcionales:

- **Monitoreo de voltaje** mediante amplificadores operacionales LM324
- **Control de carga/descarga** a través de MOSFETs IRFZ44N y relés G5DLE
- **Protección** contra sobrecarga, descarga profunda e inversión de polaridad
- **Indicadores visuales** (LEDs) del estado de cada batería
- **Regulación de voltaje** con reguladores 7812

## Herramientas utilizadas

- LTspice — Simulación del circuito
- Proteus / KiCad — Diseño del esquemático y PCB
- Microsoft Excel — Presupuesto de componentes
- Microsoft Word — Redacción del informe

# Proyecto-control-de-baterias
Proyecto grupal - Control de Baterías
# Proyecto: Control de Baterías (BMS)

Este repositorio contiene el desarrollo completo de un **Sistema de Gestión de Baterías (BMS)**
diseñado para monitorear, proteger y controlar la carga y descarga de baterías de litio de 3.7V.
El sistema es capaz de gestionar múltiples celdas de forma independiente, garantizando su
correcto funcionamiento y prolongando su vida útil.

### 📄 Documentos
- **BorradorINFORME.docx** — Borrador del informe técnico del proyecto
- **Terminos_referencia_Proyecto_Final.pdf** — Términos de referencia del proyecto
- **Terminos_referencia_Proyecto_Final_Pres.pdf** — Presentación de los términos de referencia
- **CC_PCB.pdf** — Documentación del diseño del circuito impreso

### 📊 Hojas de Cálculo
- **Presupuesto_Componentes_BMS.xlsx** — Presupuesto detallado de los componentes utilizados

### 💻 Simulación
- **bms_4celdas_serie_v2(SimulaciónEnLTspice).net** — Archivo de simulación del BMS
  con 4 celdas en serie realizada en LTspice

---

## ⚙️ ¿Cómo funciona el sistema?

El BMS desarrollado cuenta con los siguientes bloques funcionales:

- **Monitoreo de voltaje** mediante amplificadores operacionales LM324
- **Control de carga/descarga** a través de MOSFETs IRFZ44N y relés G5DLE
- **Protección** contra sobrecarga, descarga profunda e inversión de polaridad
- **Indicadores visuales** (LEDs) del estado de cada batería
- **Regulación de voltaje** con reguladores 7812

---

## 🛠️ Herramientas utilizadas

- LTspice — Simulación del circuito
- Proteus / KiCad — Diseño del esquemático y PCB
- Microsoft Excel — Presupuesto de componentes
- Microsoft Word — Redacción del informe

---

*Proyecto desarrollado como trabajo final de curso.*

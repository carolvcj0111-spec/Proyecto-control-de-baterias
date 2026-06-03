# Proyecto-control-de-baterias
Proyecto grupal - Control de Baterías
# 🔋 Proyecto: Control de Baterías (BMS)

**Integrantes:**
- Johan Campo
- Carol Castellanos
- Jairo Córdoba
- Diego Martelo
- Pedro Regalao

---

## 📌 Descripción del Proyecto

Este repositorio contiene el desarrollo completo de un **Sistema de Gestión de Baterías (BMS)**
diseñado para monitorear, proteger y controlar la carga y descarga de baterías de litio de 3.7V.
El sistema es capaz de gestionar múltiples celdas de forma independiente, garantizando su
correcto funcionamiento y prolongando su vida útil.

---

## 📁 Contenido del Repositorio

### 🖼️ Imágenes y Evidencias
- **ImplementaciónProtoboard.jpeg** — Foto del circuito armado en protoboard
- **PCB_Diseño.jpeg** — Diseño del PCB del sistema
- **PCB_Objetivo.jpeg** — PCB físico fabricado
- **PrototiposTemprano.jpeg** — Fotografías de los primeros prototipos
- **Chasis.jpeg** — Estructura física del proyecto
- **DibujoCircuitoAMano.jpeg** — Esquemático dibujado a mano durante el diseño
- **CircuitoControladorDeCargaBAT1.jpeg** — Esquemático del controlador para la Batería 1
- **CircuitoControladorDeCargaBAT2.jpeg** — Esquemático del controlador para la Batería 2
- **CircuitoControladorDeCargaBAT3.jpeg** — Esquemático del controlador para la Batería 3
- **Extra.jpeg** — Material adicional del proyecto
- **Expectativa.png** — Imagen del diseño esperado del sistema
- **PaginaWeb.jpeg / PaginaWeb.html** — Prototipo de página web del proyecto

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

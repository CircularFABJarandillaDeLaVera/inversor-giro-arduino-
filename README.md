# ⚡ Inversor de Giro con Arduino (2 Relés)

Proyecto educativo para controlar el sentido de giro de un motor DC utilizando Arduino y un módulo de relés.

---

## 🧠 Descripción

Este proyecto implementa un **inversor de giro tipo puente H con relés**, permitiendo:

* ▶ Giro adelante
* ◀ Giro atrás
* ⏹ Parada segura

Incluye:

* Esquema interactivo
* Simulador visual
* Código Arduino listo para usar
* Tabla de verdad del sistema

---

## 🌐 Demo online

👉 https://TU_USUARIO.github.io/inversor-giro-arduino/

---

## ⚙️ Componentes

* Arduino (UNO / Nano / Mega)
* Módulo relé 2 canales (5V)
* Motor DC (6–24V)
* Fuente externa para motor
* 3 pulsadores
* Cables Dupont

---

## 🔌 Funcionamiento

El sistema utiliza dos relés para invertir la polaridad del motor:

| K1  | K2  | Estado     |
| --- | --- | ---------- |
| OFF | OFF | ⏹ STOP     |
| ON  | OFF | ▶ ADELANTE |
| OFF | ON  | ◀ ATRÁS    |
| ON  | ON  | ⚠ PELIGRO  |

---

## ⚠️ Seguridad

* ❌ Nunca activar ambos relés a la vez
* ✅ Uso de GND común obligatorio
* ✅ Retardo de seguridad en el código

---

## 💻 Código Arduino

Incluido en la web interactiva.

---

## 🎓 Uso educativo

Ideal para:

* Talleres de Arduino
* Formación profesional
* Proyectos de robótica básica
* Introducción a electrónica de potencia

---

## 🏭 Contexto

Proyecto desarrollado en el entorno de innovación del
**Circular FAB – Diputación de Cáceres**

---







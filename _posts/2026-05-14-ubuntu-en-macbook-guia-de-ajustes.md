---
layout: post
title: "Ubuntu en MacBook Pro: Registro de ajustes de hardware"
date: 2026-05-14
categories: [linux, macbook, cacharreo]
---

Este es mi cuaderno de bitácora para la transición a Ubuntu en el MacBook Pro. Aquí voy centralizando todas las soluciones a los problemas de hardware que surgen durante el "cacharreo".

---

## 🖱️ Touchpad (Trackpad)
*Última actualización: 14 de mayo, 2026*

**El problema:** 
Al probar el sistema, la respuesta táctil se sentía imprecisa y con un ligero retraso (lag). El sistema de "toque para hacer clic" (tap-to-click) introducía errores de interpretación.

**La solución:** 
Desactivar completamente el **"Tap to Click"** en los ajustes del sistema.

**Resultados:**
- **Mejora de rendimiento:** Al eliminar la espera que hace el software para ver si el "tap" es un clic o un gesto, la respuesta del cursor es instantánea.
- **Sensación física:** El uso del clic mecánico da una respuesta mucho más sólida y predecible, esencial para trabajar en entornos Linux.
- **Cero accidentes:** Se evitan saltos del cursor al rozar el trackpad mientras se escribe.

---

## 🔋 Gestión de Energía y SMC (En progreso)
*Espacio reservado para las notas de calibración.*

- **Estado actual:** Equilibrio de SMC en proceso para evitar apagados repentinos. 
- **Objetivo:** Dejar la gestión de energía lista en el firmware antes de la instalación final de Linux.

---

## 💻 Comportamiento del Sistema (Lid/Tapa)
*Espacio reservado para los ajustes de suspensión y login.*

- **Ajuste realizado:** Recuperado el comportamiento original (pedir login al abrir la tapa tras el cierre).

---

## 🛠️ Notas futuras / Pendiente
- [ ] Test de estabilidad de batería bajo carga en Ubuntu.
- [ ] Revisión de drivers de red.

---
*Este post se irá actualizando con cada nueva victoria en el taller.*

# 🛰️ TP Final de Redes – Colosungs Network Project

Este repositorio contiene el desarrollo del Trabajo Práctico Final de la materia Redes, cuyo objetivo es diseñar e implementar la infraestructura de red del proyecto Colosungs, un clúster de investigación distribuido entre tres centros del Instituto de Ciencias de la UNGS.

##  📌 Objetivo General

 Diseñar, documentar e implementar una red de comunicaciones confiable, escalable y segura que conecte:

Centro de Cómputos ICI-Colosungs (Central)

Centro IDEI-Colosungs II (Suc. 1)

Centro IDH-Colosungs III (Suc. 2)

La red debe garantizar conectividad total, intercambio eficiente de recursos y soporte al clúster de investigación Colosungs.

##  🗃️ Estructura de la Red
🔹 1. Centro de Cómputos ICI-Colosungs (Central)

Aloja los servicios centrales:

Servidor Colosungs principal (cluster de 128–256 Raspberry Pi)

Servidor de datos

Servidor web + DNS

Áreas funcionales:

Investigación — 120 usuarios

Logística y Administración — 10 usuarios

🔹 2. Centro IDEI-Colosungs II (Sucursal 1)

Provee redundancia y respaldo ante fallas de la central.

Áreas:

Investigadores — 100 usuarios

Logística y Administración — 5 usuarios

🔹 3. Centro IDH-Colosungs III (Sucursal 2)

Realiza extensiones, benchmarking y gestiona salidas hacia redes externas.

Áreas:

Investigadores — 50 usuarios

Logística y Administración — 3 usuarios

✔️ Requerimientos Básicos del TP
🧩 Diseño de Red y Subneteo

Uso obligatorio del rango privado 10.0.0.0/8.

Subneteo independiente para cada instituto y área funcional.

Optimización del espacio de direcciones.

##  🌐 Enrutamiento

Elección y configuración de un protocolo de enrutamiento dinámico adecuado.

Garantizar conectividad entre todas las subredes.

##  🖥️ Servicios Centrales

Configuración del servidor web en la central (ICI).

Implementación de un servidor DNS para resolución de nombres interna.

⭐ Requerimientos Adicionales (Promoción)
##  🔒 VLANs

Implementación de VLANs para segmentar el tráfico de:

Áreas de investigación

Logística/Administración
Mejorando seguridad, orden y rendimiento.


##  🗂️ Archivo .pkt (Cisco Packet Tracer)

Incluyendo toda la implementación de la red.

##  🧰 Software Requerido

Cisco Packet Tracer
(Se recomienda utilizar la misma versión del laboratorio para evitar problemas en el coloquio.)

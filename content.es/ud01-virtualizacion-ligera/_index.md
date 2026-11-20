---
title: "UD01. Virtualización ligera"
weight: 10
---

# UD01 · Introducción y virtualización ligera

Antes de instalar Docker o Kubernetes conviene saber **qué es realmente un contenedor**: no es una máquina virtual pequeña, sino un **proceso normal de Linux** al que el núcleo le enseña una vista aislada del sistema (namespaces), le limita los recursos (cgroups) y le monta un sistema de archivos por capas. En esta unidad lo compruebas construyendo un «contenedor» a mano, sin Docker.

{{< ra "RA1:a,b,c,d,e,f,g" "RA2:f" "RA6:a" >}}

| Página | Contenido |
|---|---|
| [Teoría](/ud01-virtualizacion-ligera/ud01-teoria/) | Tipos de virtualización, historia, namespaces, cgroups v2, capacidades, OverlayFS, estándares OCI y arquitectura de un motor (5 h) |
| [Prácticas](/ud01-virtualizacion-ligera/ud01-practicas/) | Seis prácticas (VM frente a contenedor, `unshare`, cgroups, OverlayFS, contenedor artesanal e informe) y la tarea del proyecto (10 h) |

**Duración:** 15 horas (5 h de teoría y 10 h de prácticas).

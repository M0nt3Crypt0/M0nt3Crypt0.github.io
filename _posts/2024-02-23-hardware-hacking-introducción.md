---
layout: post
title: 'Hardware Hacking: Introducción'
date: 2024-02-23 12:14 +0100
categories: [HardwareHacking, Reversing]
---

# Introducción al proyecto 
Desde que he visto en clase de ciberseguridad como mi tutor del TFM (Trabajo Final de Máster) destripaba un router, obtenía una consola y acababa cargando el código en Ghidra, he querido realizar este proyecto por mi cuenta. Y visto, que se me ha dado la oportunidad, estoy realizando mi TFM con este proyecto.

Tras comentarle esto a mi tutor, tuve una reunión con él para formalizarlo todo. Me enseñó su alijo de routers que tenía y me dió a elegir uno. Entre todos los que había me llamó la atención este:

![El router de mi TFM]()

Parecía mas nuevo que el resto y tenía conexión directa para fibra óptica. Esto puede llegar a ser malo, ya que a más nuevo más probable que tenga implementados mejores mecanismos de seguridad y menos información en internet, pero como me gustan los retos, me decidí por este.

# Mi planificación inicial

Para este proyecto he decidido separarlo en fases parecidas a las de una aduitoría de seguridad, aunque con algunos cambios:

* Enumeración o compilación de información
* Conexión y obtención del firmware
* Análisis de vulnerabilidades 
* Explotación

Básicamente, he añadido un paso extra para obtener el firmware o una conexión a la consola del router. 
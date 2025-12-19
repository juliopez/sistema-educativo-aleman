---
layout: default
title: Inicio
description: >
  Bienvenido al sitio de la serie “Sistema Educativo Alemán”.<br>
  <span class="tagline-small">Aquí encontrarás los apuntes base (Markdown), el mapa conceptual y el acceso ordenado a los 14 videos.</span>
---

<nav class="main-nav">
  <a class="nav-link" href="./">Inicio</a> |
  <a class="nav-link" href="./serie">Serie</a> |
  <a class="nav-link" href="./Referencias">Referencias</a>
</nav>

<script>
  // Resaltar página activa
  const path = window.location.pathname;
  document.querySelectorAll('.main-nav .nav-link').forEach(link => {
    const href = link.getAttribute('href').replace("./", "");
    if ((href === "" && path.endsWith("/")) || (href !== "" && path.toLowerCase().includes(href.toLowerCase()))) {
      link.classList.add('active');
    }
  });
</script>

# 🇩🇪 Sistema Educativo Alemán

Repositorio de **apuntes académicos** y **videos breves (~7 min)** sobre el sistema educativo alemán.
El contenido está organizado como recurso educativo abierto para estudiantes, docentes e investigadores.

---

## 🗺️ Mapa conceptual (visión general)

![Mapa conceptual del sistema educativo alemán](./assets/mapa_conceptual_sistema_educativo_aleman.png)

---

## 🎥 Lista de reproducción en YouTube

- 📺 Serie completa: **(https://www.youtube.com/playlist?list=PLrc3rKEj3Qc9BbuluW1guhJDhtKdC8v_J)**

---

## 📌 Cómo usar este sitio

1. Revisa la sección **Serie** para ver el orden lógico de los 14 videos y sus apuntes base.  
2. En cada video encontrarás el enlace directo al apunte correspondiente en GitHub.  
3. Las fuentes se encuentran en **Referencias** (bibliografía transversal).

➡️ Ir a la serie: [Serie](./serie)

---

## 👤 Autoría

**Autor:** Dr. Julio Lopez-Nunez  
**Para consultas o comentarios:** julio.lopez-nunez@uni-konstanz.de
**Año:** 2025  

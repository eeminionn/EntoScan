# 🦋 EntoScan  
Digitalización 3D de insectos endémicos mediante fotogrametría y escaneo infrarrojo  
**Proyecto académico — Diseño en Interacción Digital — UDD**

---

## 🖼️ Vista general del proyecto

<p align="center">
  <img src="fotos/portada.jpeg" width="70%">
</p>

---

## 📘 Sobre el proyecto

**EntoScan** busca preservar insectos endémicos chilenos mediante **escaneo 3D**, **fotogrametría** y **EDOF**, generando una colección digital accesible para investigación, educación y divulgación científica.

En Chile, más del **40%** de los insectos endémicos está amenazado o en peligro de extinción. La digitalización 3D permite conservar estas especies frágiles sin dañarlas, facilitando su estudio y acceso público.

---

## 🎯 Objetivos

- Digitalizar insectos endémicos con escaneo 3D de alta fidelidad.  
- Conservar estructuras anatómicas críticas.  
- Crear una colección digital abierta de libre acceso.  
- Integrar un pipeline basado en fotogrametría + EDOF.  
- Proyectar visualización educativa mediante **realidad aumentada (AR)**.

---

## 🧬 Fundamentación científica

<p align="center">
  <img src="fotos/morfo.jpeg" width="70%">
</p>

La identificación de insectos depende de rasgos morfológicos finos, difíciles de observar sin equipamiento especializado. La digitalización 3D ofrece una alternativa segura y de alta precisión.

Este proyecto contó con retroalimentación científica de:

**Melanie Clara Nagel Strasser — Biología (PUC)**  
Especialidad: entomología e identificación morfológica.

---

## 📚 Estado del arte

<p align="center">
  <img src="fotos/estado_del_arte.jpeg" width="80%">
</p>

Referentes utilizados:

- **scAnt** – Plataforma open-source para escaneo macro 3D.  
- **Insect Brain Database** – Modelos neuronales 3D.  
- **Digitalización de abejas nativas (PUCV)** – Fotogrametría avanzada.  
- **Pokédex** – Referente conceptual visual/interactivo.

---

## 🔍 Metodología

### **1. Selección del espécimen**
<p align="center">
  <img src="fotos/seleccion.jpeg" width="60%">
</p>

---

### **2. Manipulación segura**
Manipulación mínima para evitar daños en alas, escamas y extremidades.

---

### **3. Escaneo con Creality Raptor**

<p align="center">
  <img src="fotos/raptor_1.jpeg" width="45%">
  <img src="fotos/raptor_2.jpeg" width="45%">
</p>

---

### **4. Fotogrametría + EDOF**
<p align="center">
  <img src="fotos/escaneo_1.jpeg" width="45%">
  <img src="fotos/escaneo_2.jpeg" width="45%">
</p>

---

### **5. Postprocesado**
- Limpieza de geometría  
- Fusión de mallas (anverso/reverso)  
- Texturizado UV  
- Exportación en `.obj` / `.stl`  

<p align="center">
  <img src="fotos/render_1.jpeg" width="45%">
  <img src="fotos/render_2.jpeg" width="45%">
</p>

---

## 🦾 Resultados

<p align="center">
  <img src="fotos/modelos_finales.jpeg" width="75%">
</p>

- 4 modelos completos y texturizados  
- Captura fiel de color  
- Representación anatómica detallada  
- Modelos preparados para AR  

---

## 📱 Realidad aumentada (AR)

<p align="center">
  <img src="fotos/preview_ar.jpeg" width="60%">
</p>

Se proyecta:

- Visualización en dispositivos móviles vía WebAR.  
- Modelos optimizados para RA.  
- Posible rigging básico para explorar estructuras móviles.  
- Integración de fichas educativas y taxonómicas.  

Archivos AR en `/ar`.

---

## 📁 Estructura del repositorio


# 🦋 EntoScan  
Digitalización 3D de insectos endémicos mediante fotogrametría y escaneo infrarrojo  
**Proyecto académico — Diseño en Interacción Digital — UDD**

---

## 📘 Sobre el proyecto

**EntoScan** busca preservar insectos endémicos chilenos mediante **escaneo 3D**, **fotogrametría** y **apilamiento de enfoque (EDOF)**, generando una colección digital accesible para investigación, educación y divulgación científica.

En Chile, más del **40%** de los insectos endémicos está amenazado o en peligro de extinción. La digitalización 3D permite conservar estas especies frágiles sin dañarlas, facilitando su estudio y acceso público.

---

## 🎯 Objetivos

- Digitalizar insectos endémicos mediante escaneo 3D de alta fidelidad.
- Conservar estructuras anatómicas clave: antenas, patas, élitros, aparato bucal.
- Crear una colección digital abierta, educativa y científicamente útil.
- Desarrollar un pipeline basado en fotogrametría + EDOF.
- Proyectar una futura experiencia en **realidad aumentada (AR)**.

---

## 🧬 Fundamentación científica

La identificación de insectos depende de rasgos morfológicos finos, difíciles de observar sin equipamiento especializado. La digitalización 3D ofrece una alternativa segura y de alta precisión.

Este proyecto contó con retroalimentación científica de:

**Melanie Clara Nagel Strasser**  
Estudiante de Biología – Pontificia Universidad Católica de Chile  
Especialidad: entomología e identificación morfológica

Sus aportes guiaron criterios sobre:
- manipulación segura de especímenes frágiles,
- captura anatómica detallada,
- consideraciones éticas de trabajo con colecciones entomológicas.

---

## 🧠 Estado del arte

Referentes clave utilizados:
- **scAnt** — Plataforma open-source de escaneo macro 3D.
- **Insect Brain Database** — Modelos 3D neuronales de insectos.
- **Digitalización de abejas nativas (PUCV)** — Fotogrametría de alta resolución.
- **Pokédex** — Referente conceptual para organización de modelos + fichas.

Estos casos entregan métodos, escalas y lógicas de clasificación visual relevantes para fortalecer EntoScan.

---

## 🔍 Metodología

### **1. Selección del espécimen**  
Insectos preservados en colecciones educativas y museos, priorizando muestras no vivas.

### **2. Manipulación segura**  
Evita contacto directo para proteger escamas, alas y estructuras frágiles.

### **3. Escaneo 3D con Creality Raptor**
- Sensor infrarrojo  
- Captura de malla + textura  
- Alta precisión morfológica  

Fotos del proceso en `/photos/proceso_raptor`.

### **4. Fotogrametría + EDOF**
- Captura del anverso y reverso
- Integración de imágenes con profundidad extendida
- Alineación de mallas y texturizado

### **5. Postprocesado**
- Limpieza de geometría  
- Reconstrucción final  
- Texturizado UV  
- Exportación a `.obj` / `.stl`  

Modelos finales en `/models`.

### **6. Documentación**
Informes, análisis y poster EntoScan disponibles en `/docs`.

---

## 🦾 Resultados

- 4 modelos 3D completos y texturizados.
- Representaciones fieles en color y detalle anatómico.
- Mallas optimizadas para visualización interactiva y experiencias AR.

Renders disponibles en `/photos/renders`.

---

## 📱 Realidad aumentada (AR)

Como proyección futura, EntoScan considera:

- Visualización AR en dispositivos móviles.  
- Modelos optimizados para WebAR.  
- Rigging básico para explorar movimiento/anatomía.  
- Integración de fichas descriptivas por especie.

Recursos AR en `/ar`.

---

## 📁 Estructura del repositorio


# 🚀 QA Testing: Interfaz y Lógica de Mapas - Urban Routes

## 📋 Descripción del Proyecto
Este proyecto consistió en el aseguramiento de calidad del módulo principal de la aplicación **Urban Routes**. El enfoque principal fue validar la interactividad del mapa, la precisión de los campos de búsqueda "Desde" y "Hasta" y el flujo lógico de selección de destinos.

## 🛠️ Actividades Realizadas
* **Pruebas de Navegación:** Verificación de los campos de dirección y pines del mapa.
* **Interactividad:** Comprobación de botones de zoom, capas de mapa y renderizado de objetos.
* **Bug Reporting:** Documentación detallada de errores visuales y de flujo detectados durante la exploración..

## 🔍 Cobertura de la Suite de Pruebas
Se ejecutaron pruebas exhaustivas sobre los siguientes componentes:
* **Campos de Dirección:** Validación de entradas de texto y sincronización con los pines del mapa.
* **Interactividad del Mapa:** Pruebas de renderizado de objetos 3D, edificios, estaciones de metro y parques.
* **Modos de Visualización:** Verificación de controles de zoom, modo Satélite, Relieve y Street View.

## 🐛 Gestión de Defectos (Bug Reporting)
Se documentaron fallos críticos que afectan la experiencia del usuario. A continuación, el resumen del informe de errores:

| ID | Defecto | Severidad | Prioridad |
| :--- | :--- | :--- | :--- |
| **B001** | Al buscar en el campo "Hasta", la lista de estaciones de metro no aparece. | **Crítica** | **Alta** |
| **B002** | El sistema no identifica lugares específicos (ej. "subway") en la búsqueda. | **Crítica** | **Alta** |
| **B003** | El campo "Desde" no señaliza visualmente direcciones válidas ingresadas. | Menor | Media |
| **B004** | El logotipo de la aplicación no es interactivo (no despliega información). | Trivial | Baja |

> **Nota Técnica:** Los errores B001 y B002 fueron clasificados como críticos ya que impiden completar el flujo principal de navegación de la aplicación.

## 📈 Entregables
1. **Plan de Pruebas:** Detalle de casos ejecutados (Aprobados/Fallidos).
2. **Reporte de Bugs:** Documentación técnica de los hallazgos para el equipo de desarrollo.
3. **Evidencias:** Capturas de pantalla de los errores de renderizado detectados.

---
### 👤 Contacto
**Edwin Sánchez** 📧 [esanchez9103@outlook.com](mailto:esanchez9103@outlook.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/edwin-sanchez-041a8722b/)

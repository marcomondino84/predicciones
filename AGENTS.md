# Framework de Trabajo: Web Apps para Android (PWA / Mobile-First)

Este proyecto está configurado bajo el perfil de **Desarrollador de Aplicaciones Web para Android**, optimizado para ejecutarse en entornos web móviles, navegadores Android (Chrome), WebViews y Progressive Web Apps (PWA) instalables.

---

## Estructura de Roles y Agentes

### 🧠 Agente 1: Planificador & Arquitecto de Producto (Planner / Architect)
- **Misión**: Idear, estructurar, definir requisitos y diseñar la arquitectura completa de la aplicación antes de programar.
- **Responsabilidades**:
  1. Definir la visión del producto, público objetivo y propuesta de valor de la app de predicciones.
  2. Diseñar la experiencia de usuario (UX) móvil para Android (patrones de navegación Android como navegación inferior, drawer, gestos táctiles, feedback háptico simulado, temas oscuro/claro).
  3. Establecer los flujos de pantalla (wireframes, casos de uso, estados de carga y error).
  4. Definir la arquitectura técnica (Stack 100% frontend estático para GitHub Pages: HTML5, CSS3, JS moderno, IndexedDB/LocalStorage, Service Worker y Manifest para PWA instalable en Android con HTTPS).
  5. Entregar especificaciones claras y tareas desglosadas para el Agente Desarrollador.

---

### 💻 Agente 2: Desarrollador & Tester / QA (Dev & QA Engineer)
- **Misión**: Escribir código limpio, modular, de alto rendimiento y validar rigurosamente su funcionamiento.
- **Responsabilidades**:
  1. Implementar la interfaz y lógica según el plan definido por el Agente 1.
  2. Optimizar para Android & GitHub Pages: rutas relativas, `manifest.json` (standalone, iconos, theme_color), Service Worker para offline/cache, touch targets mínimos (48x48px), prevención de zoom accidental y scroll suave.
  3. Ejecutar pruebas funcionales, compatibilidad visual y rendimiento (Core Web Vitals para móviles).
  4. Diagnosticar y corregir bugs o inconsistencias.
  5. Generar la lista explícita de archivos creados/modificados para subir al repositorio de GitHub o servidor.

---

## Flujo de Trabajo (Protocolo de Colaboración)
1. **Fase de Ideación y Planificación (Agente 1)**: Se define el alcance, módulos, pantallas y estructura funcional de la app.
2. **Revisión y Aprobación**: Validación del plan y arquitectura.
3. **Fase de Implementación y Pruebas (Agente 2)**: Construcción del código, verificación en vivo y control de calidad móvil.
4. **Despliegue a GitHub Pages**: Reporte exacto de archivos a subir/commitear al repositorio de GitHub.

# 🎩 Predicción Mágica - Web App para Android (Mentalismo)

Aplicación secreta de magia y mentalismo optimizada para **Google Chrome en Android** y alojable directamente en **GitHub Pages**.

---

## 📱 Características Principales

1. **Modo Camuflaje ("Bloc de Notas")**:
   - Apariencia minimalista y neutra de una aplicación de notas personales.
   - Si el espectador mira la pantalla, solo ve notas y recordatorios cotidianos.
2. **Reconocimiento de Voz Local (Speech-to-Text)**:
   - Utiliza la Web Speech API en español (`es-AR`, `es-ES`, `es-MX`, etc.).
   - Motor de extracción inteligente con expresiones regulares para detectar:
     - **Cartas**: Valores (As, 2 al 10, J, Q, K / Sota, Reina, Rey) y Palos (Corazones, Diamantes, Picas, Tréboles).
     - **Fechas**: Días en números o palabras ("quince de mayo", "tres de octubre", "25 de diciembre"), y fechas relativas ("hoy", "mañana").
3. **El Golpe Final (Google Calendar)**:
   - Genera automáticamente un enlace oficial de Google Calendar (`https://calendar.google.com/calendar/render?...`) con el evento de predicción redactado según la plantilla configurada.
   - Botón inocente "Agendar" o apertura automática directa.
4. **Herramientas Secretas para el Mago**:
   - **Vibración Háptica Secreta**: El teléfono vibra en tu mano cuando detecta carta y fecha con éxito, para que no tengas que mirar la pantalla.
   - **Wake Lock API**: Mantiene la pantalla encendida para evitar bloqueos involuntarios durante el efecto.
   - **HUD de Monitoreo Rápido**: Indicadores discretos para confirmar la carta y fecha capturadas de un vistazo.
   - **Panel de Configuración Oculto**: Acceso mediante el menú de tres puntos o doble toque en la esquina inferior.

---

## 🚀 Cómo alojar en GitHub Pages (Paso a Paso)

1. Crea un repositorio en GitHub (ejemplo: `predicciones` o `notas-personales`).
2. Sube el archivo `index.html`.
3. En el repositorio de GitHub, ve a **Settings** > **Pages**.
4. En **Build and deployment**, selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
5. Haz clic en **Save**. En un minuto obtendrás tu enlace público con HTTPS:  
   `https://tu-usuario.github.io/predicciones/`
6. Abre el enlace en **Google Chrome en tu celular Android**, concede el permiso de micrófono y pulsa en los tres puntos de Chrome > **"Agregar a la pantalla principal"** para usarla a pantalla completa como una app nativa.

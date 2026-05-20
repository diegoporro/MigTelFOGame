⚡ **Migtel - Fibra Master v1.0 | MigTel Labs***

¡Bienvenido al repositorio de Migtel: Fibra Master! Un juego web educativo e interactivo diseñado para capacitar a técnicos, ingenieros y estudiantes en los conceptos fundamentales y despliegue de redes de fibra óptica FTTH (GPON).

El juego está desarrollado en un único archivo autocontenido (HTML5 + Tailwind CSS + Vanilla JS), lo que facilita su portabilidad y despliegue inmediato sin necesidad de configuraciones ni servidores complejos.

🎮 **En qué consiste el juego**

El jugador asume el rol de un Ingeniero de Planta Externa en Migtel. A través de 3 misiones de dificultad progresiva (Cliente Residencial, Edificio de Apartamentos y Enlace Interurbano), el usuario debe superar con éxito las 4 etapas críticas de un enlace óptico:

[Misión] ──> 1. Planificación FTTH ──> 2. Guía de Luz (Física) ──> 3. Fusión de Núcleo ──> 4. Diagnóstico OTDR


🛰️ **Las 4 Etapas de Aprendizaje**

**Estrategia FTTH (Cálculo de Link Budget):**

El jugador ajusta la potencia de la OLT central (desde +1 dBm hasta +9 dBm).

Configura la arquitectura de doble división o cascada seleccionando el splitter en la FDT (Caja de Distribución) y en la NAP (Caja de Acceso).

El sistema calcula la atenuación total considerando pérdidas por distancia, splitters y conectores. El objetivo es lograr una señal de llegada saludable a la ONT entre -15 dBm y -27 dBm.

**El Camino de la Luz (Física y Curvatura):**

Simulación interactiva basada en física de ondas con HTML5 Canvas.

El jugador debe guiar el haz de luz ajustando el ángulo de emisión para asegurar la Reflexión Total Interna.

Si el ángulo genera demasiados rebotes o curvas pronunciadas, la luz se escapa al revestimiento, aumentando la pérdida en decibelios ($dB$).

**Fusión de Núcleo (Cirujano de Fibra):**

Simulación interactiva de una fusionadora de precisión.

El usuario controla servomotores virtuales para alinear el núcleo (core) de silicio de la fibra monomodo (de apenas $9\ \mu m$) en el eje vertical Y.

Una vez lograda la alineación perfecta, dispara un arco eléctrico virtual de alta temperatura para soldar las fibras con una pérdida inferior a 0.30 dB.

**Inspector OTDR (Diagnóstico de Redes):**

Interfaz gráfica de diagnóstico que traza la firma reflectométrica de la línea.

El jugador aprende a interpretar curvas de atenuación, picos reflectivos por conectores y caídas por anomalías mecánicas.

Debe localizar e identificar el kilómetro exacto donde ocurre la caída brusca de señal para autorizar la reparación.

✨ **Características Especiales**

☀️/🌙 **Modo Claro por Defecto y Modo Oscuro:** Botón interactivo para alternar fluidamente la visualización según las preferencias de iluminación del usuario.

❓ **Ayuda Técnica Integrada:** Cada nivel cuenta con un botón de interrogación (?) que despliega un modal explicando detalladamente la teoría científica o técnica detrás de esa sección (conceptos como GPON cascada, ángulo crítico, dimensiones de fibra monomodo, etc.).

📱 **Aesthetics & Responsive Design:** Maquetado con Tailwind CSS de forma adaptativa. Los Canvas interactivos se redibujan de forma automática ante cambios de tamaño en dispositivos móviles o desktops.

🎓 **Pedagogía Activa:** Ideal para onboarding o capacitaciones técnicas rápidas dentro del ecosistema de Migtel.

🛠️ **Tecnologías utilizadas**

Este proyecto fue construido utilizando tecnologías web nativas para asegurar su rendimiento, estabilidad y cero dependencias pesadas:

HTML5 & CSS3 (Estructura de maquetación avanzada).

Tailwind CSS (Estilos modernos, transiciones suaves y layouts responsivos).

HTML5 Canvas API (Animaciones físicas del haz láser y renderizado de la gráfica del OTDR).

Vanilla JavaScript (ES6+) (Lógica del juego, álgebra de atenuaciones y control de estados).

Lucide Icons (Iconografía limpia y moderna basada en vectores SVG).

Google Fonts (Space Grotesk & Plus Jakarta Sans) (Tipografías optimizadas para lectura técnica).

🚀 **Cómo ejecutar el proyecto localmente**

Dado que el juego es completamente autocontenido, no requiere de servidores locales, base de datos ni compiladores.

**Clona el repositorio:**

git clone [https://github.com/tu-usuario/migtel-fibra-master.git](https://github.com/tu-usuario/migtel-fibra-master.git)


🏢 **Créditos**

Desarrollado con pasión para el equipo de ingeniería y operaciones de MigTel.

Soporte y Consultas: soporte@migtel.net.ve ; tecnologia@migtel.net.ve

Tecnología de Simulación: MigTel Labs 2026

_Nota:_ Este software es una herramienta didáctica de simulación lúdica independiente.

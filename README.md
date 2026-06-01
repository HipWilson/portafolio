# Portafolio — Wilson Arodi Peña Hip

🔗 **[Ver portafolio en vivo →](https://hipwilson.github.io/portafolio/)**

---

## Reflexión

### ¿A qué tipo de audiencia o trabajo está dirigido este portafolio?

Este portafolio está dirigido a startups o empresas de tamaño mediano que busquen un desarrollador con capacidad tanto en frontend como en manejo de datos. No apunto a una agencia creativa donde el diseño visual sea el único criterio, ni a una empresa corporativa grande donde el proceso pese más que la capacidad técnica. Me interesa un equipo donde se valore que puedo construir una interfaz funcional y bien diseñada *y* conectarla a una base de datos real — es decir, un rol donde el frontend no termine en el pixel sino que incluya la lógica detrás.

El perfil al que le habla este portafolio es alguien que evalúa desarrolladores con criterio técnico: que revise el repositorio, que haga clic en los demos, que note si el código está bien organizado. No está pensado para impresionar visualmente a alguien sin contexto técnico, sino para convencer a un tech lead o a un equipo de producto.

### ¿Qué tecnologías eligieron usar y por qué?

El portafolio en sí está construido en HTML, CSS y JavaScript vanilla — sin framework — porque para un sitio estático de una sola página, introducir React habría sido innecesario y habría complicado el deploy. El objetivo fue que el código fuera limpio, rápido y fácil de leer para cualquiera que lo revise.

Para los proyectos mostrados, el stack central es **React con Vite**, que es la combinación con la que trabajo con más confianza y que refleja bien el ecosistema frontend actual. Tailwind CSS aparece como elección de estilos porque permite moverse rápido con consistencia visual. En el lado de datos, **Firebase/Firestore** y **MySQL** representan los dos extremos del espectro que el portafolio quiere cubrir: una base de datos en tiempo real en la nube y una base de datos relacional más tradicional.

### ¿Qué tecnología del curso decidieron no usar, y por qué?

Decidí no incluir proyectos con **Next.js** aunque lo vimos en clase. La razón es honesta: no me siento lo suficientemente cómodo con él todavía como para mostrarlo en un portafolio sin que se note. Incluir un proyecto construido a medias en Next.js habría diluido la coherencia del resto. Prefiero mostrar tres proyectos donde domino completamente el stack a mostrar cuatro donde uno revela incertidumbre técnica. Si tuviera más tiempo, Next.js sería la siguiente tecnología en agregar con intención.

### ¿Dónde se arriesgaron y dónde la jugaron seguro? ¿Por qué?

**Jugué seguro** en la elección de tecnologías para los proyectos: React, Vite y Tailwind son exactamente lo que ya domino. No quise arriesgar en la parte que evalúa conocimiento técnico directo — ese no era el lugar para experimentar.

**Me arriesgué** en el diseño del portafolio mismo. En lugar de usar una plantilla o un generador, construí el diseño completo desde cero con una estética dark mode y tipografía no convencional. También me arriesgué al construir el portafolio en HTML/CSS/JS vanilla en lugar de React, lo que va contra el instinto de "mostrar el stack" pero fue la decisión técnicamente correcta para este caso. Esa decisión dice algo sobre criterio: saber cuándo *no* usar un framework también es una habilidad.

### Si tuvieran otra semana, ¿qué mejorarían?

Hay tres cosas concretas que mejoraría:

1. **Agregar un proyecto con backend real.** El portafolio habla de Firebase y MySQL, pero el proyecto más completo (SportsTracker) usa LocalStorage en el frontend. Con más tiempo, construiría una versión con Firestore o con una API en Node.js + MySQL desplegada en un servidor real, que es lo que el portafolio promete.

2. **Mejorar las animaciones de transición.** Las que están implementadas son funcionales pero básicas (fade-up al hacer scroll). Me gustaría explorar transiciones más fluidas entre secciones y micro-interacciones en los botones y tarjetas de proyectos.

3. **Agregar un caso de estudio.** Ahora cada proyecto tiene una descripción corta. Con más tiempo, expandiría al menos uno con capturas de pantalla reales, decisiones de diseño y lecciones aprendidas — algo que le dé contexto más profundo a quien lo revise.

---

## Tecnologías usadas en el portafolio

- HTML5 semántico
- CSS3 (custom properties, grid, flexbox, animaciones)
- JavaScript vanilla (IntersectionObserver para animaciones de entrada)
- Google Fonts (Syne + DM Sans)
- Deploy: GitHub Pages

## Proyectos incluidos

| Proyecto | Tipo | Demo |
|---|---|---|
| SportsTracker | Fullstack / CRUD | [Ver →](https://hipwilson.github.io/sportstracker-frontend/) |
| Calculadora React | UI / Componentes | [Ver →](https://hipwilson.github.io/react-calculator/) |
| Password Strength Meter | Seguridad / UX | [Repo →](https://github.com/HipWilson/password-strength-meter) |

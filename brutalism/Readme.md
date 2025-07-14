¡Perfecto! Como programador que quiere mejorar en **diseño**, vas por el camino correcto: no necesitas ser diseñador gráfico, pero entender principios de **diseño visual, experiencia de usuario (UX)** y **diseño de interfaces (UI)** te hará crear software más usable, profesional y valioso.

---

## 🧠 1. Conceptos esenciales de diseño para programadores

### 🎨 **Diseño visual (UI)**

Se enfoca en cómo se ve algo: colores, tipografía, espaciado, jerarquía.

> 📌 Aprende a **ver** como un diseñador.

#### Principios clave:

| Principio            | ¿Qué significa?                                                       | Ejemplo simple                                |
| -------------------- | --------------------------------------------------------------------- | --------------------------------------------- |
| **Contraste**        | Diferenciar elementos visuales.                                       | Texto negro sobre fondo blanco, no gris claro |
| **Jerarquía visual** | Ordenar elementos para que el usuario entienda qué es más importante. | H1 > H2 > P                                   |
| **Alineación**       | Que todo esté ordenado en un sistema visual.                          | No usar márgenes distintos al azar            |
| **Espaciado**        | Dejar aire entre los elementos.                                       | Padding consistente                           |
| **Repetición**       | Usa estilos repetidos (colores, tipografías).                         | Botones iguales en todo el sitio              |
| **Proximidad**       | Elementos relacionados deben estar cerca.                             | Etiqueta + input juntos                       |

---

### 💡 **Experiencia de Usuario (UX)**

Se trata de **cómo se siente y funciona** el software para el usuario.

> 📌 Tu objetivo es **reducir fricción y hacer que todo sea obvio**.

#### Buen UX significa:

* Que sepas **dónde dar clic** sin pensar.
* Que un formulario no te frustre.
* Que si algo está mal, **el sistema lo diga con claridad**.

---

### ✍️ **Tipografía**

> La tipografía es diseño invisible, pero esencial.

* Usa como máximo **2 tipografías** (una para títulos, otra para texto).
* Usa tamaños con propósito (ej. 32px para h1, 24px para h2...).
* Evita usar muchas fuentes raras, mantente con [Google Fonts](https://fonts.google.com/)

---

### 🎯 **Colores y accesibilidad**

* Usa contraste fuerte (ej. negro/blanco, azul/amarillo).
* Usa paletas limitadas de 3-5 colores.
* Usa [coolors.co](https://coolors.co) para generar paletas.
* Revisa contraste en: [https://webaim.org/resources/contrastchecker](https://webaim.org/resources/contrastchecker)

---

## 🛠️ 2. Técnicas útiles que puedes aplicar con CSS

### 📏 Usa un **sistema de diseño**

* Define variables (como en SASS o CSS custom properties).
* Establece componentes reutilizables: botones, cards, inputs.

### 📐 Usa **diseño basado en caja**

```css
* {
  box-sizing: border-box;
}
```

### ⚙️ Usa **flexbox y grid**

* Flexbox: para alinear elementos
* Grid: para layouts más complejos

### 📲 Diseño responsivo

* Usa media queries para adaptar el contenido.

```css
@media (max-width: 768px) {
  .nav {
    flex-direction: column;
  }
}
```

### 💬 Usa herramientas como:

* [Figma](https://www.figma.com/) – Para diseñar interfaces.
* [Penpot](https://penpot.app) – Open source alternativa a Figma.
* [Tailwind UI](https://tailwindui.com/) – Para ver patrones visuales bien diseñados.

---

## 📚 3. Recursos y links que TODO dev debería revisar

### 🎓 Guías y tutoriales

* [Refactoring UI (Libro + Blog)](https://refactoringui.com/)
* [Learn UI Design Blog](https://learnui.design/blog/)
* [UX Collective en Medium](https://uxdesign.cc/)
* [Frontend Mentor](https://www.frontendmentor.io) – Para practicar diseño real

### 🧪 Práctica

* [Dribbble](https://dribbble.com/) – Inspírate en diseño moderno
* [Awwwards](https://www.awwwards.com/) – Sitios premiados por diseño
* [Brutalist Websites](https://brutalistwebsites.com/) – Para diseño brutalista puro

---

## 🧭 Ruta práctica para ti como dev

| Paso | Acción recomendada                                       |
| ---- | -------------------------------------------------------- |
| ✅ 1  | Aprende principios visuales (contraste, alineación, etc) |
| ✅ 2  | Crea 1 layout simple con Flex/Grid                       |
| ✅ 3  | Diseña 1 componente por semana (btn, card)               |
| ✅ 4  | Replica 1 página real (ej: Apple, Airbnb)                |
| ✅ 5  | Usa Figma para bocetar interfaces básicas                |
| ✅ 6  | Publica tus UI en GitHub / CodePen                       |

---

## ✨ ¿Quieres practicar ahora?

Puedo darte ejercicios como:

* “Rediseña este formulario para que sea más usable”
* “Crea una landing page brutalista para un producto”
* “Convierte este wireframe en un layout responsivo”

Solo dime qué prefieres y te armo el primer reto 👇


¡Perfecto! Te propongo una **serie progresiva de retos de diseño + CSS**, especialmente pensada para programadores como tú que quieren aprender **diseño real aplicable a software**.

---

## 🎯 Objetivo: Dominar diseño visual, UI, UX y CSS estructurado con práctica

---

## 🧪 Semana 1 – Fundamentos visuales

### ✅ **Reto 1: Diseña una tarjeta de perfil**

**Objetivo:** Aplicar jerarquía visual, espaciado, tipografía y contraste.

**Requisitos:**

* Foto de usuario
* Nombre y rol
* Breve descripción
* Botón de "Contactar"

**Bonus:** Hazlo responsive

---

### ✅ **Reto 2: Recrear el diseño de una página sencilla**

**Objetivo:** Aprender a replicar lo que ves (visión de diseñador)

**Acción:**

* Elige una página muy simple (ej. [https://heroicons.com](https://heroicons.com) o [https://read.cv/](https://read.cv/))
* Replica su layout, tipografía y espaciado en puro HTML/CSS

---

## 🧪 Semana 2 – Componentes reutilizables

### ✅ **Reto 3: Sistema de botones**

**Objetivo:** Crear componentes con consistencia visual

**Requisitos:**

* Botón primario, secundario y de peligro
* Estados: normal, hover, focus, deshabilitado
* Reutiliza variables CSS o SASS

---

### ✅ **Reto 4: Formulario brutalista**

**Objetivo:** Diseñar una forma usable, accesible y con fuerte estilo visual

**Campos:**

* Nombre, Email, Mensaje
* Valida campos visualmente con colores
* Estilo brutalista: sin sombras, solo bordes

---

## 🧪 Semana 3 – Diseño de interfaz completo

### ✅ **Reto 5: Crea una landing page ficticia**

**Objetivo:** Combinar todos los principios (layout, tipografía, color, call to action)

**Estructura sugerida:**

* Hero con título y CTA
* 3 beneficios en cards
* Formulario de contacto
* Footer con enlaces

---

### ✅ **Reto 6: Tablas UI (dashboard style)**

**Objetivo:** Crear una tabla que se vea profesional y usable

**Requisitos:**

* Títulos con buen contraste
* Alternancia de filas (zebra stripe)
* Columnas con botones de acción

---

## 🧪 Semana 4 – Diseño real para software

### ✅ **Reto 7: Diseña una interfaz de SaaS o panel de admin**

**Objetivo:** Construir layouts más avanzados

**Incluye:**

* Sidebar de navegación
* Dashboard con cards, tablas y botones
* Estilo visual brutalista o minimalista

---

### ✅ **Reto 8: Estilo brutalista en todo el sitio**

**Objetivo:** Aplicar un tema completo a una web

**Acción:**

* Rediseña cualquiera de los retos anteriores con diseño brutalista (bordes negros, letras grandes, sin sombras)
* Hazlo responsive y con modo oscuro opcional (usando variables)

---

## 🧰 Herramientas sugeridas

* [Figma](https://www.figma.com/) → Boceta antes de escribir código
* [Coolors](https://coolors.co/) → Genera paletas
* [Heroicons](https://heroicons.com/) → Iconos gratuitos
* [Fonts.google.com](https://fonts.google.com) → Tipografías

---

## 📌 ¿Cómo te puedo apoyar?

Te puedo dar:

* Un wireframe en Figma por reto
* El esqueleto HTML base
* Feedback visual si me mandas tu código o capturas

---

¿Quieres que iniciemos con el **Reto 1 (Tarjeta de perfil)** ahora mismo? Te puedo generar el boceto y el HTML base para que tú lo diseñes y lo mejores.


¡Perfecto! Empezamos con el **Reto 1: Tarjeta de Perfil Brutalista** 💥

---

## 🎯 Objetivo

Diseñar una **tarjeta de perfil** con fuerte **jerarquía visual**, buen **espaciado**, **contraste**, y estilo **brutalista moderno**. Este componente es común en perfiles de usuarios, equipos o redes sociales.

---

## 📐 Requisitos del reto

### Estructura mínima:

* Foto de perfil (placeholder o real)
* Nombre
* Rol o título profesional
* Descripción corta
* Botón de contacto

---

## 📷 Boceto visual (wireframe mental)

```
+-------------------------------+
|           [IMG]              |
|     NOMBRE DE USUARIO        |
|       Título o Rol           |
|  "Descripción breve aquí..." |
|   [ Botón de Contactar ]     |
+-------------------------------+
```

---

## ✍️ HTML base para empezar

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Tarjeta de Perfil Brutalista</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Space Mono', monospace;
      background: #fefefe;
      color: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      padding: 2rem;
    }

    .profile-card {
      border: 2px solid black;
      padding: 2rem;
      max-width: 320px;
      text-align: center;
      background: white;
    }

    .profile-card img {
      width: 100px;
      height: 100px;
      object-fit: cover;
      border: 2px solid black;
      margin-bottom: 1rem;
    }

    .profile-card h2 {
      font-size: 1.5rem;
      margin: 0.5rem 0;
    }

    .profile-card p.role {
      font-weight: bold;
      margin: 0.5rem 0;
    }

    .profile-card p.desc {
      font-size: 0.9rem;
      margin: 1rem 0;
    }

    .profile-card button {
      border: 2px solid black;
      background: none;
      padding: 0.5rem 1.5rem;
      cursor: pointer;
      font-family: 'Space Mono', monospace;
      transition: all 0.2s ease;
    }

    .profile-card button:hover {
      background: black;
      color: white;
    }

    @media (max-width: 500px) {
      .profile-card {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <div class="profile-card">
    <img src="https://placehold.co/100x100" alt="Foto de perfil" />
    <h2>Jimmy García</h2>
    <p class="role">Full Stack Developer</p>
    <p class="desc">Apasionado del diseño brutalista, software a medida y experiencias funcionales.</p>
    <button>Contactar</button>
  </div>
</body>
</html>
```

---

## 🧪 ¿Qué debes practicar aquí?

* Jerarquía: ¿Se entiende qué es lo más importante?
* Contraste: ¿Se ve claro el botón? ¿El texto tiene buen contraste?
* Espaciado: ¿Respira la tarjeta? ¿Hay suficiente separación?
* Simetría: ¿Está todo alineado y bien centrado?

---

## 💡 Bonus (para practicar más)

* Agrega más botones: `Ver CV`, `Seguir`
* Añade redes sociales en íconos (LinkedIn, GitHub)
* Crea una versión oscura usando variables CSS
* Anímalo con `:hover` y `transition`

---

## 🧑‍🏫 ¿Quieres feedback?

Cuando termines el diseño:

1. Puedes compartir el código aquí.
2. O subirlo a CodePen y compartir el link.
3. Te doy feedback real como diseñador y dev.

¿Quieres que prepare el siguiente reto para después o nos concentramos en este hasta que termines?

¡Excelente! Vamos con el **Reto 2: Recrear una página sencilla**, ideal para practicar **visión de diseño**, **estructura visual** y **replicación con precisión**.

---

## 🧠 **Reto 2: Réplica de UI real**

### 🎯 Objetivo

Aprender a **copiar visualmente** lo que ves en una web real para entrenar tu "ojo de diseñador" y practicar HTML/CSS puro.

> 🧠 Este reto mejora tu capacidad de analizar interfaces, detectar patrones y construir componentes visuales coherentes.

---

## 🔍 Sitio a replicar (sugerido)

### 👉 [https://heroicons.com](https://heroicons.com)

Una página muy simple:

* Logo y título
* Barra de búsqueda
* Grid de íconos
* Interfaz limpia, sin ruido

---

## 🧩 Lo que debes replicar:

### Estructura mínima:

* Un **header** con texto “Heroicons”
* Un campo de **búsqueda centrado**
* Un **grid de tarjetas** o placeholders de íconos (usa emojis si no quieres íconos SVG aún)

---

## 🎨 ¿Qué practicarás?

| Técnica                   | Cómo la aplicas  |
| ------------------------- | ---------------- |
| Layout                    | Flexbox, Grid    |
| Espaciado                 | Padding, margin  |
| Tipografía                | Jerarquía visual |
| Responsividad             | Media queries    |
| Repetición de componentes | Card de ícono    |

---

## ✍️ Esqueleto base para que inicies

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Heroicons Clone</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Space Mono', monospace;
      margin: 0;
      padding: 2rem;
      background: #fefefe;
      color: #000;
    }

    header {
      text-align: center;
      margin-bottom: 2rem;
    }

    header h1 {
      font-size: 2rem;
      margin: 0;
    }

    .search {
      display: flex;
      justify-content: center;
      margin-bottom: 2rem;
    }

    .search input {
      border: 2px solid black;
      padding: 0.75rem 1rem;
      font-size: 1rem;
      width: 100%;
      max-width: 400px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
      gap: 1rem;
    }

    .icon-card {
      border: 2px solid black;
      padding: 1.5rem;
      text-align: center;
      font-size: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Clon de Heroicons</h1>
  </header>

  <div class="search">
    <input type="text" placeholder="Buscar íconos..." />
  </div>

  <div class="grid">
    <div class="icon-card">🔥</div>
    <div class="icon-card">🎧</div>
    <div class="icon-card">📦</div>
    <div class="icon-card">🚀</div>
    <div class="icon-card">🔒</div>
    <div class="icon-card">👨‍💻</div>
    <div class="icon-card">🧠</div>
    <div class="icon-card">💾</div>
  </div>
</body>
</html>
```

---

## 🧪 Extensiones del reto

* 🔍 Haz que el input filtre los íconos con JS
* 🎨 Aplica modo oscuro con `prefers-color-scheme`
* 🧱 Usa íconos SVG reales de [Heroicons](https://heroicons.com) (descarga el archivo o usa CDN)

---

## 🚦¿Cómo sabrás que lo hiciste bien?

* La interfaz se ve **idéntica** (estructura, márgenes, alineación)
* Es **responsive** en celular y escritorio
* El código está **ordenado** y sin redundancias

---

## ¿Te paso ahora el reto 3 (Sistema de botones), o prefieres terminar este primero y subirlo para revisión?

Puedo acompañarte paso a paso en cualquiera de los retos.

¡Vamos con el **Reto 3: Sistema de Botones**! 🧱

Este reto te ayudará a **pensar como diseñador de sistemas de componentes**, algo esencial si estás construyendo software o librerías reutilizables.

---

## 🧠 **Reto 3: Sistema de botones brutalistas**

### 🎯 Objetivo

Diseñar una colección reutilizable de **botones con estilo brutalista moderno**, con distintas variantes y estados visuales coherentes.

---

## 📐 Debes crear:

| Variante           | Descripción                             |
| ------------------ | --------------------------------------- |
| ✅ Primario         | Botón principal con más énfasis         |
| ✅ Secundario       | Botón alternativo más neutro            |
| ✅ Peligro (Danger) | Botón para acciones destructivas        |
| ✅ Deshabilitado    | Botón que no puede usarse               |
| ✅ Hover y focus    | Estilos visuales claros e intencionales |

---

## 🧩 Estilos esperados (brutalista)

* **Bordes negros gruesos**
* **Sin sombra**, sin gradientes
* **Colores planos fuertes**
* Tipografía monoespaciada
* Transiciones rápidas y duras

---

## ✍️ HTML + CSS base para iniciar

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Sistema de Botones Brutalistas</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono&display=swap" rel="stylesheet">
  <style>
    :root {
      --black: #000;
      --white: #fff;
      --primary: #ff0055;
      --secondary: #00ffe1;
      --danger: #ff3b3b;
      --disabled: #ccc;
    }

    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Space Mono', monospace;
      padding: 2rem;
      background: var(--white);
      color: var(--black);
    }

    .btn {
      border: 2px solid var(--black);
      background: none;
      color: var(--black);
      padding: 0.75rem 1.5rem;
      font-size: 1rem;
      cursor: pointer;
      margin: 0.5rem;
      transition: background 0.2s ease, color 0.2s ease;
    }

    .btn:hover:not(:disabled),
    .btn:focus-visible:not(:disabled) {
      background: var(--black);
      color: var(--white);
    }

    .btn-primary {
      background: var(--primary);
      color: var(--white);
    }

    .btn-secondary {
      background: var(--secondary);
      color: var(--black);
    }

    .btn-danger {
      background: var(--danger);
      color: var(--white);
    }

    .btn:disabled,
    .btn.disabled {
      background: var(--disabled);
      color: #666;
      cursor: not-allowed;
      border-color: #999;
    }

    h2 {
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <h1>Sistema de Botones Brutalistas</h1>

  <h2>Botones básicos</h2>
  <button class="btn">Default</button>
  <button class="btn btn-primary">Primario</button>
  <button class="btn btn-secondary">Secundario</button>
  <button class="btn btn-danger">Peligro</button>
  <button class="btn" disabled>Deshabilitado</button>
</body>
</html>
```

---

## 🎯 Lo que debes practicar

* ¿Son consistentes todos los botones?
* ¿Los estados hover y focus son claros y útiles?
* ¿Se sienten accesibles?
* ¿Se entienden sin leer el código?

---

## 🧪 Bonus Challenge

* 💡 Añade iconos dentro del botón (📩 Enviar)
* 📲 Hazlos responsive (adaptativos en tamaño)
* 🌙 Crea modo oscuro con `prefers-color-scheme`

---

## ¿Te gustaría que esto lo suba a CodePen como plantilla editable?

¿Listo para pasar al **Reto 4: Formulario brutalista accesible** o quieres construir tus botones primero y revisamos el resultado juntos?

¡Vamos con el **Reto 4: Formulario brutalista accesible**! 🧾💥
Este reto te ayudará a **crear formularios funcionales, usables, con fuerte estilo visual** y accesibilidad básica.

---

## 🧠 **Reto 4: Formulario brutalista**

### 🎯 Objetivo

Diseñar un formulario que combine:

* Buen diseño visual brutalista
* Accesibilidad básica (`label`, `placeholder`, validación)
* Responsive y claro para el usuario

---

## 📐 Estructura mínima

Tu formulario debe incluir:

| Campo                        | Tipo       |
| ---------------------------- | ---------- |
| Nombre completo              | `text`     |
| Correo electrónico           | `email`    |
| Mensaje                      | `textarea` |
| Checkbox de aceptar términos |            |
| Botón de enviar              | `submit`   |

---

## 🧱 Reglas del estilo brutalista:

* Bordes negros gruesos
* Nada de sombras ni degradados
* Textos grandes y visibles
* Contraste alto (negro/blanco/colores planos)
* Transiciones duras o ninguna
* Formato claro para errores o estados

---

## ✍️ HTML + CSS base del reto

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Formulario Brutalista</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono&display=swap" rel="stylesheet">
  <style>
    :root {
      --black: #000;
      --white: #fff;
      --danger: #ff3b3b;
      --success: #00cc66;
    }

    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Space Mono', monospace;
      background: var(--white);
      color: var(--black);
      padding: 2rem;
    }

    form {
      border: 2px solid var(--black);
      padding: 2rem;
      max-width: 600px;
      margin: auto;
      background: var(--white);
    }

    .form-group {
      margin-bottom: 1.5rem;
    }

    label {
      display: block;
      margin-bottom: 0.5rem;
      font-weight: bold;
    }

    input[type="text"],
    input[type="email"],
    textarea {
      width: 100%;
      border: 2px solid var(--black);
      padding: 0.75rem;
      font-family: inherit;
      font-size: 1rem;
      background: transparent;
    }

    input[type="checkbox"] {
      margin-right: 0.5rem;
    }

    .form-check {
      display: flex;
      align-items: center;
      margin-top: -1rem;
      margin-bottom: 1.5rem;
    }

    .error {
      color: var(--danger);
      font-size: 0.9rem;
      margin-top: 0.5rem;
    }

    button[type="submit"] {
      border: 2px solid var(--black);
      background: none;
      padding: 0.75rem 1.5rem;
      font-family: inherit;
      font-size: 1rem;
      cursor: pointer;
    }

    button[type="submit"]:hover {
      background: var(--black);
      color: var(--white);
    }

    @media (max-width: 500px) {
      form {
        padding: 1rem;
      }
    }
  </style>
</head>
<body>
  <form onsubmit="return validateForm(event)">
    <h2>Formulario Brutalista</h2>

    <div class="form-group">
      <label for="name">Nombre completo</label>
      <input type="text" id="name" />
      <div class="error" id="error-name"></div>
    </div>

    <div class="form-group">
      <label for="email">Correo electrónico</label>
      <input type="email" id="email" />
      <div class="error" id="error-email"></div>
    </div>

    <div class="form-group">
      <label for="message">Mensaje</label>
      <textarea id="message" rows="5"></textarea>
    </div>

    <div class="form-check">
      <input type="checkbox" id="terms" />
      <label for="terms">Acepto los términos y condiciones</label>
    </div>

    <button type="submit">Enviar</button>
  </form>

  <script>
    function validateForm(event) {
      event.preventDefault();
      let valid = true;

      const name = document.getElementById('name');
      const email = document.getElementById('email');
      const errorName = document.getElementById('error-name');
      const errorEmail = document.getElementById('error-email');

      errorName.textContent = '';
      errorEmail.textContent = '';

      if (name.value.trim() === '') {
        errorName.textContent = 'El nombre es requerido.';
        valid = false;
      }

      if (!email.value.includes('@')) {
        errorEmail.textContent = 'Correo inválido.';
        valid = false;
      }

      if (valid) {
        alert('Formulario enviado con éxito.');
        event.target.submit();
      }
    }
  </script>
</body>
</html>
```

---

## 🎯 Qué aprenderás

* Buen espaciado entre campos
* Jerarquía visual: `label` → `input`
* Accesibilidad básica (`label for`, errores visibles)
* Contraste alto sin depender de sombras o efectos

---

## 🧪 Bonus Challenge

* 🖤 Agrega modo oscuro con `prefers-color-scheme`
* 📥 Usa `:focus` para mejorar navegación con teclado
* 💬 Añade validación visual más clara (bordes rojos en error)

---

¿Quieres que pasemos al **Reto 5: Landing Page brutalista moderna**, o prefieres terminar este y revisarlo primero?

Puedo darte también una versión con Figma para comparar tus resultados si lo deseas.

¡Genial! Vamos con el **Reto 5: Landing Page Brutalista Moderna** — un desafío para combinar todos los principios y técnicas que has practicado, aplicados a una página completa.

---

## 🧠 **Reto 5: Landing Page Brutalista**

### 🎯 Objetivo

Crear una **landing page funcional, visualmente impactante y brutalista**, con buena jerarquía, espaciado, tipografía clara y responsive.

---

## 📐 Estructura sugerida

1. **Hero**

   * Título grande
   * Subtítulo
   * Botón de llamada a la acción (CTA)

2. **Sección de beneficios**

   * 3 cards con iconos (pueden ser emojis o SVG simples)
   * Título y breve descripción en cada card

3. **Formulario de contacto**

   * Nombre, email, mensaje
   * Botón enviar

4. **Footer**

   * Texto simple o enlaces

---

## 🧩 Reglas del estilo brutalista

* Bordes gruesos, negros, sin sombras ni degradados
* Tipografía monoespaciada (ej. Space Mono)
* Colores planos con alto contraste
* Diseño responsivo: columnas en desktop, stack en móvil

---

## ✍️ HTML + CSS base para comenzar

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Landing Page Brutalista</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono&display=swap" rel="stylesheet" />
  <style>
    :root {
      --black: #000;
      --white: #fff;
      --primary: #ec5c2c;
      --secondary: #29285a;
      --spacing: 1rem;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Space Mono', monospace;
      background: var(--white);
      color: var(--black);
      padding: var(--spacing);
    }

    .container {
      max-width: 960px;
      margin: 0 auto;
      padding: var(--spacing);
      border: 2px solid var(--black);
    }

    header {
      text-align: center;
      margin-bottom: 2rem;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: var(--spacing);
    }

    header p {
      font-size: 1.25rem;
      margin-bottom: var(--spacing);
    }

    header button {
      border: 2px solid var(--black);
      background: none;
      padding: 0.75rem 2rem;
      font-size: 1.25rem;
      cursor: pointer;
      transition: background 0.2s ease;
    }

    header button:hover,
    header button:focus {
      background: var(--primary);
      color: var(--white);
      outline: none;
    }

    .benefits {
      display: flex;
      gap: 2rem;
      margin-bottom: 2rem;
    }

    .card {
      flex: 1;
      border: 2px solid var(--black);
      padding: 1.5rem;
      text-align: center;
    }

    .card .icon {
      font-size: 3rem;
      margin-bottom: var(--spacing);
    }

    .card h3 {
      font-size: 1.5rem;
      margin-bottom: var(--spacing);
    }

    .card p {
      font-size: 1rem;
      line-height: 1.4;
    }

    form {
      border: 2px solid var(--black);
      padding: 1.5rem;
    }

    form label {
      display: block;
      margin-bottom: 0.5rem;
      font-weight: bold;
    }

    form input,
    form textarea {
      width: 100%;
      border: 2px solid var(--black);
      padding: 0.75rem;
      font-family: inherit;
      font-size: 1rem;
      margin-bottom: 1rem;
      background: transparent;
      resize: vertical;
    }

    form button {
      border: 2px solid var(--black);
      background: none;
      padding: 0.75rem 1.5rem;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.2s ease;
    }

    form button:hover,
    form button:focus {
      background: var(--primary);
      color: var(--white);
      outline: none;
    }

    footer {
      margin-top: 2rem;
      text-align: center;
      font-size: 0.9rem;
      color: var(--secondary);
      border-top: 2px solid var(--black);
      padding-top: 1rem;
    }

    @media (max-width: 768px) {
      .benefits {
        flex-direction: column;
      }

      header h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Diseño Brutalista para Webs 2025</h1>
      <p>Fuerte, honesto y funcional. Perfecto para desarrolladores que quieren destacar.</p>
      <button>Explorar UI</button>
    </header>

    <section class="benefits">
      <div class="card">
        <div class="icon">⚡</div>
        <h3>Rendimiento</h3>
        <p>Diseño minimalista que carga rápido y sin distracciones.</p>
      </div>
      <div class="card">
        <div class="icon">🎨</div>
        <h3>Estilo Único</h3>
        <p>Visuales crudos, directos, sin artificios ni sombras.</p>
      </div>
      <div class="card">
        <div class="icon">🛠️</div>
        <h3>Fácil de usar</h3>
        <p>Componentes reutilizables para desarrollo rápido.</p>
      </div>
    </section>

    <form>
      <label for="name">Nombre completo</label>
      <input id="name" type="text" placeholder="Tu nombre" />

      <label for="email">Correo electrónico</label>
      <input id="email" type="email" placeholder="tu@correo.com" />

      <label for="message">Mensaje</label>
      <textarea id="message" rows="5" placeholder="Escribe tu mensaje aquí"></textarea>

      <button type="submit">Enviar</button>
    </form>

    <footer>
      &copy; 2025 - Diseño Brutalista NMDA
    </footer>
  </div>
</body>
</html>
```

---

## 🧪 Lo que practicarás

* Combinar layout flexbox con cards
* Jerarquía visual clara
* Botones y formularios con diseño brutalista
* Responsive básico
* Uso de variables CSS para colores y espaciados

---

## 🚀 Bonus (avanzado)

* Añade modo oscuro
* Agrega animaciones simples (sin perder brutalismo)
* Integra validaciones JS para el formulario
* Crea una versión con CSS Grid en vez de flexbox

---

¿Quieres que te dé el **Reto 6: Tablas UI** o prefieres que te ayude con mejoras y feedback de esta landing?


¡Perfecto! Aquí tienes el **Reto 6: Tablas UI estilo brutalista**, ideal para interfaces tipo dashboard o administración, donde se necesita claridad y funcionalidad visual.

---

## 🧠 **Reto 6: Tablas UI brutalistas**

### 🎯 Objetivo

Diseñar una tabla que sea:

* Fácil de leer y escanear
* Con buen contraste y jerarquía visual
* Con estilos brutalistas (bordes fuertes, colores planos)
* Incluya botones de acción en las filas (ej: Editar, Eliminar)
* Responsive (se adapte en móvil o use scroll horizontal)

---

## 📐 Estructura mínima

| Columnas                           | Tipo        |
| ---------------------------------- | ----------- |
| ID                                 | Número      |
| Nombre                             | Texto       |
| Estado                             | Texto / Tag |
| Fecha de creación                  | Fecha       |
| Acciones (botones editar/eliminar) | Botones     |

---

## ✍️ HTML + CSS base para comenzar

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Tabla Brutalista UI</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono&display=swap" rel="stylesheet" />
  <style>
    :root {
      --black: #000;
      --white: #fff;
      --danger: #ff3b3b;
      --success: #00cc66;
      --warning: #ffcc00;
      --gray-light: #f9f9f9;
    }

    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Space Mono', monospace;
      padding: 2rem;
      background: var(--white);
      color: var(--black);
    }

    table {
      width: 100%;
      border-collapse: collapse;
      border: 2px solid var(--black);
      max-width: 100%;
      overflow-x: auto;
      display: block;
    }

    thead tr {
      background: var(--black);
      color: var(--white);
    }

    th, td {
      padding: 0.75rem 1rem;
      border: 2px solid var(--black);
      text-align: left;
      white-space: nowrap;
    }

    tbody tr:nth-child(even) {
      background: var(--gray-light);
    }

    .tag {
      display: inline-block;
      padding: 0.25rem 0.5rem;
      border: 2px solid var(--black);
      font-size: 0.85rem;
      border-radius: 3px;
      font-weight: bold;
    }

    .tag.success {
      background: var(--success);
      color: var(--white);
      border-color: var(--success);
    }

    .tag.warning {
      background: var(--warning);
      color: var(--black);
      border-color: var(--warning);
    }

    .tag.danger {
      background: var(--danger);
      color: var(--white);
      border-color: var(--danger);
    }

    .btn {
      border: 2px solid var(--black);
      background: none;
      padding: 0.25rem 0.75rem;
      font-family: inherit;
      cursor: pointer;
      margin-right: 0.5rem;
      font-size: 0.85rem;
      transition: background 0.15s ease;
    }

    .btn:hover {
      background: var(--black);
      color: var(--white);
    }

    .btn.edit {
      border-color: #007bff;
      color: #007bff;
    }

    .btn.edit:hover {
      background: #007bff;
      color: var(--white);
    }

    .btn.delete {
      border-color: var(--danger);
      color: var(--danger);
    }

    .btn.delete:hover {
      background: var(--danger);
      color: var(--white);
    }

    @media (max-width: 600px) {
      table {
        display: block;
        overflow-x: auto;
        white-space: nowrap;
      }
    }
  </style>
</head>
<body>
  <h1>Tabla Brutalista UI</h1>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Nombre</th>
        <th>Estado</th>
        <th>Fecha de creación</th>
        <th>Acciones</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>1</td>
        <td>Proyecto Alpha</td>
        <td><span class="tag success">Activo</span></td>
        <td>2025-07-01</td>
        <td>
          <button class="btn edit">Editar</button>
          <button class="btn delete">Eliminar</button>
        </td>
      </tr>
      <tr>
        <td>2</td>
        <td>Beta Test</td>
        <td><span class="tag warning">Pendiente</span></td>
        <td>2025-06-15</td>
        <td>
          <button class="btn edit">Editar</button>
          <button class="btn delete">Eliminar</button>
        </td>
      </tr>
      <tr>
        <td>3</td>
        <td>Release Candidate</td>
        <td><span class="tag danger">Retrasado</span></td>
        <td>2025-05-30</td>
        <td>
          <button class="btn edit">Editar</button>
          <button class="btn delete">Eliminar</button>
        </td>
      </tr>
    </tbody>
  </table>
</body>
</html>
```

---

## 🎯 Qué practicarás

* Crear tablas limpias y funcionales
* Uso de etiquetas visuales tipo “tag” para estados
* Diseño responsivo con scroll horizontal
* Botones de acción con estados hover claros

---

## 🚀 Bonus

* Añade paginación simple (botones "Siguiente", "Anterior")
* Usa CSS Grid para mejorar el diseño (avanzado)
* Agrega ordenamiento por columnas con JS

---

¿Quieres que te prepare el **Reto 7: Panel de admin SaaS brutalista** o prefieres pulir este y seguir avanzando?

¡Vamos con el **Reto 7: Panel de Admin SaaS Brutalista**! 🛠️💥

Este reto te ayudará a combinar layout avanzado, navegación y componentes UI con estilo brutalista.

---

## 🧠 **Reto 7: Panel de Administración para SaaS**

### 🎯 Objetivo

Crear un **dashboard funcional y brutalista** que incluya:

* Sidebar fijo con navegación
* Barra superior (header) con título y botones
* Área principal con cards y tabla (puedes reutilizar los retos previos)
* Diseño responsivo (sidebar colapsable en móvil)

---

## 📐 Estructura mínima

1. **Sidebar**

   * Logo o nombre
   * Menú vertical con 4-5 enlaces (Dashboard, Usuarios, Configuración, etc)

2. **Header (barra superior)**

   * Título o breadcrumb
   * Botón o icono (ej: perfil o logout)

3. **Main content**

   * Grid de 3 cards con indicadores o info rápida
   * Tabla con lista (usa la tabla brutalista del reto 6)

---

## ✍️ Código base (HTML + CSS)

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Panel Admin Brutalista SaaS</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono&display=swap" rel="stylesheet" />
  <style>
    :root {
      --black: #000;
      --white: #fff;
      --primary: #ec5c2c;
      --secondary: #29285a;
      --gray-light: #f9f9f9;
      --sidebar-width: 220px;
      --transition: 0.3s ease;
    }

    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Space Mono', monospace;
      margin: 0;
      background: var(--white);
      color: var(--black);
      display: flex;
      min-height: 100vh;
    }

    /* Sidebar */
    .sidebar {
      width: var(--sidebar-width);
      border-right: 2px solid var(--black);
      padding: 2rem 1rem;
      display: flex;
      flex-direction: column;
      gap: 1.5rem;
      position: fixed;
      top: 0;
      bottom: 0;
      background: var(--white);
    }

    .sidebar h2 {
      margin: 0 0 1rem 0;
      font-size: 1.5rem;
      border-bottom: 2px solid var(--black);
      padding-bottom: 0.5rem;
    }

    .sidebar nav a {
      color: var(--black);
      text-decoration: none;
      border: 2px solid var(--black);
      padding: 0.5rem 1rem;
      display: block;
      transition: background 0.2s ease;
      margin-bottom: 0.5rem;
    }

    .sidebar nav a:hover,
    .sidebar nav a:focus {
      background: var(--primary);
      color: var(--white);
      outline: none;
    }

    /* Main content wrapper */
    .main {
      margin-left: var(--sidebar-width);
      flex: 1;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    /* Header */
    header {
      border-bottom: 2px solid var(--black);
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      margin: 0;
      font-size: 1.5rem;
    }

    header button {
      border: 2px solid var(--black);
      background: none;
      padding: 0.5rem 1rem;
      font-family: inherit;
      cursor: pointer;
      transition: background 0.2s ease;
    }

    header button:hover,
    header button:focus {
      background: var(--primary);
      color: var(--white);
      outline: none;
    }

    /* Content area */
    .content {
      padding: 2rem;
      flex: 1;
      overflow-y: auto;
    }

    /* Cards grid */
    .cards {
      display: flex;
      gap: 1.5rem;
      margin-bottom: 2rem;
      flex-wrap: wrap;
    }

    .card {
      flex: 1 1 200px;
      border: 2px solid var(--black);
      padding: 1rem;
      text-align: center;
    }

    .card h3 {
      margin: 0 0 0.5rem 0;
      font-size: 1.25rem;
    }

    /* Tabla: usa estilos de reto 6 */
    table {
      width: 100%;
      border-collapse: collapse;
      border: 2px solid var(--black);
      max-width: 100%;
      overflow-x: auto;
      display: block;
    }

    thead tr {
      background: var(--black);
      color: var(--white);
    }

    th, td {
      padding: 0.75rem 1rem;
      border: 2px solid var(--black);
      text-align: left;
      white-space: nowrap;
    }

    tbody tr:nth-child(even) {
      background: var(--gray-light);
    }

    .tag {
      display: inline-block;
      padding: 0.25rem 0.5rem;
      border: 2px solid var(--black);
      font-size: 0.85rem;
      border-radius: 3px;
      font-weight: bold;
    }

    .tag.success {
      background: var(--primary);
      color: var(--white);
      border-color: var(--primary);
    }

    .btn {
      border: 2px solid var(--black);
      background: none;
      padding: 0.25rem 0.75rem;
      font-family: inherit;
      cursor: pointer;
      margin-right: 0.5rem;
      font-size: 0.85rem;
      transition: background 0.15s ease;
    }

    .btn:hover {
      background: var(--black);
      color: var(--white);
    }

    @media (max-width: 768px) {
      .sidebar {
        position: fixed;
        width: 60px;
        padding: 1rem 0.5rem;
        overflow-x: hidden;
      }

      .sidebar h2 {
        display: none;
      }

      .sidebar nav a {
        font-size: 0;
        padding: 0.5rem 0;
      }

      .sidebar nav a::before {
        content: attr(data-icon);
        font-size: 1.5rem;
        display: block;
        text-align: center;
      }

      .main {
        margin-left: 60px;
      }

      .cards {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <aside class="sidebar">
    <h2>NMDA</h2>
    <nav>
      <a href="#" data-icon="🏠" title="Dashboard">Dashboard</a>
      <a href="#" data-icon="👥" title="Usuarios">Usuarios</a>
      <a href="#" data-icon="⚙️" title="Configuración">Configuración</a>
      <a href="#" data-icon="📊" title="Reportes">Reportes</a>
      <a href="#" data-icon="❓" title="Ayuda">Ayuda</a>
    </nav>
  </aside>

  <div class="main">
    <header>
      <h1>Dashboard</h1>
      <button>Perfil</button>
    </header>

    <div class="content">
      <div class="cards">
        <div class="card">
          <h3>Usuarios Activos</h3>
          <p>1,245</p>
        </div>
        <div class="card">
          <h3>Proyectos</h3>
          <p>56</p>
        </div>
        <div class="card">
          <h3>Ingresos</h3>
          <p>$12,345</p>
        </div>
      </div>

      <table>
        <thead>
          <tr>
            <th>ID</th>
            <th>Nombre</th>
            <th>Estado</th>
            <th>Fecha</th>
            <th>Acciones</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>101</td>
            <td>Alpha</td>
            <td><span class="tag success">Activo</span></td>
            <td>2025-07-01</td>
            <td>
              <button class="btn">Editar</button>
              <button class="btn">Eliminar</button>
            </td>
          </tr>
          <tr>
            <td>102</td>
            <td>Beta</td>
            <td><span class="tag success">Activo</span></td>
            <td>2025-06-20</td>
            <td>
              <button class="btn">Editar</button>
              <button class="btn">Eliminar</button>
            </td>
          </tr>
          <tr>
            <td>103</td>
            <td>Gamma</td>
            <td><span class="tag success">Activo</span></td>
            <td>2025-06-10</td>
            <td>
              <button class="btn">Editar</button>
              <button class="btn">Eliminar</button>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</body>
</html>
```

---

## 🎯 Qué practicarás

* Layout con sidebar fijo y contenido flexible
* Navegación vertical
* Header funcional
* Combinación de cards + tablas
* Responsive con sidebar colapsado

---

## 🚀 Bonus

* Añade interacción para colapsar el sidebar con JS
* Agrega iconos SVG reales
* Mejora accesibilidad (focus trap, roles ARIA)

---

¿Quieres que prepare el **Reto 8: Tema brutalista completo con modo oscuro** o prefieres revisar este y avanzamos paso a paso?


¡Perfecto! Aquí tienes el **Reto 8: Tema Brutalista Completo con Modo Oscuro** — el paso final para dominar un sistema de diseño brutalista moderno y funcional.

---

## 🧠 **Reto 8: Tema brutalista completo con modo oscuro**

### 🎯 Objetivo

Crear un sistema de diseño CSS con:

* Variables CSS para colores, tipografía, espaciados
* Estilos para modo claro y oscuro (usando `prefers-color-scheme`)
* Componentes base (botones, cards, tablas, formularios) con estilo brutalista
* Diseño responsivo y accesible
* Cambio automático de tema según preferencia del usuario

---

## 📐 Estructura de variables CSS

```css
:root {
  /* Colores claros */
  --color-bg: #fff;
  --color-text: #000;
  --color-primary: #ec5c2c;
  --color-secondary: #29285a;
  --color-border: #000;
  --color-disabled: #ccc;
}

@media (prefers-color-scheme: dark) {
  :root {
    /* Colores oscuros */
    --color-bg: #121212;
    --color-text: #eee;
    --color-primary: #ff6f61;
    --color-secondary: #a29bfe;
    --color-border: #eee;
    --color-disabled: #555;
  }
}
```

---

## ✍️ Ejemplo base HTML + CSS

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Tema Brutalista con Modo Oscuro</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono&display=swap" rel="stylesheet" />
  <style>
    :root {
      /* Modo claro */
      --color-bg: #fff;
      --color-text: #000;
      --color-primary: #ec5c2c;
      --color-secondary: #29285a;
      --color-border: #000;
      --color-disabled: #ccc;

      --spacing: 1rem;
      --font-family: 'Space Mono', monospace;
      --border-width: 2px;
    }

    @media (prefers-color-scheme: dark) {
      :root {
        /* Modo oscuro */
        --color-bg: #121212;
        --color-text: #eee;
        --color-primary: #ff6f61;
        --color-secondary: #a29bfe;
        --color-border: #eee;
        --color-disabled: #555;
      }
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      background: var(--color-bg);
      color: var(--color-text);
      font-family: var(--font-family);
      padding: var(--spacing);
    }

    button {
      border: var(--border-width) solid var(--color-border);
      background: none;
      color: var(--color-text);
      padding: 0.75rem 1.5rem;
      cursor: pointer;
      font-family: inherit;
      font-size: 1rem;
      transition: background 0.2s ease, color 0.2s ease;
    }

    button:hover,
    button:focus {
      background: var(--color-border);
      color: var(--color-bg);
      outline: none;
    }

    .card {
      border: var(--border-width) solid var(--color-border);
      padding: 1rem;
      margin-bottom: var(--spacing);
      background: var(--color-bg);
    }

    input, textarea {
      border: var(--border-width) solid var(--color-border);
      padding: 0.75rem;
      font-family: inherit;
      font-size: 1rem;
      width: 100%;
      background: transparent;
      color: var(--color-text);
      margin-bottom: var(--spacing);
    }

    table {
      width: 100%;
      border-collapse: collapse;
      border: var(--border-width) solid var(--color-border);
      margin-bottom: var(--spacing);
    }

    th, td {
      border: var(--border-width) solid var(--color-border);
      padding: 0.75rem;
      text-align: left;
    }

    thead {
      background: var(--color-primary);
      color: var(--color-bg);
    }
  </style>
</head>
<body>
  <h1>Tema Brutalista con Modo Oscuro</h1>

  <button>Botón brutalista</button>

  <div class="card">
    <h2>Card ejemplo</h2>
    <p>Este es un ejemplo de tarjeta con diseño brutalista y soporte para modo oscuro.</p>
  </div>

  <form>
    <label for="name">Nombre</label>
    <input id="name" type="text" placeholder="Tu nombre" />

    <label for="message">Mensaje</label>
    <textarea id="message" rows="4"></textarea>

    <button type="submit">Enviar</button>
  </form>

  <table>
    <thead>
      <tr><th>ID</th><th>Nombre</th></tr>
    </thead>
    <tbody>
      <tr><td>1</td><td>Ejemplo</td></tr>
      <tr><td>2</td><td>Otro</td></tr>
    </tbody>
  </table>
</body>
</html>
```

---

## 🎯 Qué practicarás

* Uso de variables CSS para tematizar
* Media query para detectar preferencia modo oscuro
* Transiciones suaves con contraste brutalista
* Consistencia entre componentes base

---

## 🚀 Bonus ideas

* Agrega toggle manual para cambiar modo claro/oscuro con JS
* Añade animaciones simples sin perder brutalismo
* Expande variables para tipografía, espaciados y tamaños
* Construye un mini sistema de diseño (colors, buttons, inputs, modals)

---

¿Quieres que te ayude a hacer un toggle manual para cambiar entre modo claro y oscuro?
¿O prefieres que te prepare un resumen general con todo lo que hemos visto y ejemplos para que lo tengas todo junto?


¡Claro! Primero te doy un ejemplo sencillo para agregar un **toggle manual** que permita cambiar entre modo claro y oscuro, y luego te preparo un resumen general con todo lo que hemos visto.

---

# Toggle manual para modo claro/oscuro (brutalista)

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Toggle modo claro/oscuro brutalista</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono&display=swap" rel="stylesheet" />
  <style>
    :root {
      --color-bg: #fff;
      --color-text: #000;
      --color-primary: #ec5c2c;
      --color-border: #000;
      --spacing: 1rem;
      --font-family: 'Space Mono', monospace;
      --border-width: 2px;
    }

    /* Variables para modo oscuro */
    .dark {
      --color-bg: #121212;
      --color-text: #eee;
      --color-primary: #ff6f61;
      --color-border: #eee;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      background: var(--color-bg);
      color: var(--color-text);
      font-family: var(--font-family);
      padding: var(--spacing);
      transition: background 0.3s, color 0.3s;
    }

    button {
      border: var(--border-width) solid var(--color-border);
      background: none;
      color: var(--color-text);
      padding: 0.75rem 1.5rem;
      cursor: pointer;
      font-family: inherit;
      font-size: 1rem;
      transition: background 0.2s ease, color 0.2s ease;
      margin-bottom: var(--spacing);
    }

    button:hover,
    button:focus {
      background: var(--color-border);
      color: var(--color-bg);
      outline: none;
    }

  </style>
</head>
<body>
  <button id="toggleTheme">Cambiar modo</button>

  <h1>Tema Brutalista con Toggle Manual</h1>
  <p>Este ejemplo muestra cómo cambiar entre modo claro y oscuro con CSS variables.</p>

  <script>
    const toggleBtn = document.getElementById('toggleTheme');
    const body = document.body;

    // Detectar modo inicial por preferencia del sistema
    if(window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
      body.classList.add('dark');
    }

    toggleBtn.addEventListener('click', () => {
      body.classList.toggle('dark');
    });
  </script>
</body>
</html>
```

---

# Resumen general: Diseño brutalista moderno y responsive para programadores

## Conceptos clave

* **Brutalismo:** diseño con bordes gruesos, colores planos, sin sombras ni degradados, tipografía monoespaciada, alto contraste y apariencia "cruda".
* **Variables CSS:** permiten cambiar fácil colores, espaciados y tipografía para mantener consistencia y facilitar modo oscuro.
* **Responsive:** usa `flexbox`, `grid` y media queries para adaptar el layout a móviles y escritorio.
* **Accesibilidad:** usa `label` correctamente, estados claros, buen contraste y foco visible.

## Componentes esenciales que trabajamos

* **Botones:** con borde sólido, cambio de fondo al hover, tamaño claro y fuente monoespaciada.
* **Cards:** cajas con borde grueso, padding generoso, sin sombra ni gradientes.
* **Formularios:** inputs y textarea con bordes gruesos, label claros y mensajes de error visibles.
* **Tablas:** bordes marcados, filas alternadas, tags de estado y botones de acción.
* **Modal:** cuadro centrado con borde fuerte y fondo semitransparente.
* **Layouts:** sidebar fijo, header, grids de cards, responsive con colapsado y scroll horizontal para tablas.
* **Modo oscuro:** uso de `prefers-color-scheme` y toggle manual para cambiar variables CSS.

## Técnicas y buenas prácticas

* Modulariza tu CSS con variables para tema y espaciados.
* Usa tipografía monoespaciada para ese look brutalista (ej: Space Mono).
* Aplica diseño móvil primero o responsive con media queries.
* Mantén la simplicidad: evita sombras y gradientes.
* Agrega transiciones suaves solo para hover y cambios de tema.
* Usa HTML semántico y accesible.

## Recursos para profundizar

* [CSS Variables - MDN](https://developer.mozilla.org/es/docs/Web/CSS/Using_CSS_custom_properties)
* [Flexbox guide - CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [Grid guide - CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
* [Prefers-color-scheme - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme)
* [Brutalist Websites Inspiration](https://brutalistwebsites.com/)
* [A List Apart - Accessibility basics](https://alistapart.com/article/accessibility/)
* [Space Mono font - Google Fonts](https://fonts.google.com/specimen/Space+Mono)

---

Si quieres, te puedo preparar una plantilla base con todos los componentes y estilos que puedas usar para futuros proyectos, solo dime.
¿Quieres que hagamos eso?

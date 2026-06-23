# 🎯 Memorama de Profesiones

Juego de memoria interactivo con temática de profesiones. Desarrollado con HTML, CSS y JavaScript vanilla.

---

## ✨ Características

| Funcionalidad | Descripción |
|--------------|-------------|
| 🎨 **Diseño moderno** | Fondo oscuro con degradados vibrantes, formas flotantes y efectos glassmorphism |
| 👔 **18 profesiones** | Doctor, maestra, chef, bombero, piloto, astronauta, programadora y más |
| ⚡ **3 dificultades** | Fácil (8 pares), Medio (10 pares), Difícil (12 pares) |
| ⏱️ **Temporizador** | Mide el tiempo de cada partida |
| 👆 **Contador de movimientos** | Registra cada intento |
| ⭐ **Sistema de estrellas** | Calificación de 1 a 3 estrellas según eficiencia |
| 🎊 **Confetti de victoria** | Animación celebratoria con partículas de colores |
| 🔄 **Efecto 3D** | Volteo realista de cartas con perspectiva |
| 📱 **Responsive** | Adaptado a móvil, tablet y escritorio |
| ♿ **Accesibilidad** | Navegación completa con teclado (Tab + Enter/Espacio) |

---

## 📁 Estructura del proyecto

```
memorama-profesiones/
├── index.html          ← Página principal
├── css/
│   └── main.css        ← Estilos, animaciones y diseño responsive
├── js/
│   └── main.js         ← Lógica del juego (clase Memorama)
└── README.md           ← Este archivo
```

---

## 🚀 Cómo usar

### Opción 1: Abrir directamente

1. Descarga o clona la carpeta del proyecto
2. Abre `index.html` en tu navegador
3. ¡A jugar!

### Opción 2: Con servidor local

```bash
# Con Node.js
npx serve memorama-profesiones

# Con Python
cd memorama-profesiones
python3 -m http.server 3000
```

---

## 🎮 Cómo jugar

1. Haz clic en una carta para voltearla y ver la profesión oculta
2. Haz clic en otra carta para intentar encontrar el par
3. Si coinciden, las cartas quedan descubiertas con un efecto verde
4. Si no coinciden, se voltean de nuevo tras una breve pausa
5. Encuentra todos los pares para ganar
6. Usa el botón **⚡ Fácil / Medio / Difícil** para cambiar de nivel
7. Usa **🔄 Reiniciar** para empezar de nuevo

---

## 🧩 Personalización

### Agregar más profesiones

Edita el arreglo `PROFESSIONS` en `js/main.js`:

```javascript
const PROFESSIONS = [
  { id: 'doctor', emoji: '👨‍⚕️', label: 'Doctor' },
  // Agrega más profesiones aquí:
  { id: 'veterinarian', emoji: '👨‍⚕️🐾', label: 'Veterinario' },
  // ...
];
```

### Cambiar los colores

Edita las variables CSS en `css/main.css`:

```css
:root {
  --color-primary: #8b5cf6;   /* Púrpura principal */
  --color-pink: #ec4899;      /* Rosa acento */
  --color-bg-start: #0f0c29;  /* Fondo oscuro */
  /* ... más variables ... */
}
```

---

## 🛠️ Tecnologías

- **HTML5** – Semántico y accesible
- **CSS3** – Variables, Grid, Flexbox, animaciones 3D, glassmorphism
- **JavaScript (ES6+)** – Clases, módulos, template literals, Fisher-Yates shuffle

Cero dependencias externas (solo la fuente Nunito desde Google Fonts).

---

## 📄 Licencia

MIT — libre para usar, modificar y compartir.

---

## 👤 Autor

Desarrollado como proyecto educativo de memorama. ¡Diviértete jugando!
# 💖 Nuestra Historia - Experiencia Web Interactiva

Este proyecto es una página web animada e interactiva, diseñada para regalar una experiencia única a tu pareja en San Valentín, aniversarios o fechas especiales. Combina una narrativa emotiva con hermosos efectos visuales de partículas.

## ✨ Características

*   **🔒 Pantalla de Bloqueo con Fecha**: La experiencia está protegida por un código que corresponde a su fecha especial (aniversario).
*   **✨ Animaciones de Partículas**: Efectos visuales fluidos que forman números, flechas, esferas y corazones.
*   **📖 Modo Historia**: Cuenta su historia paso a paso con textos personalizados y transiciones suaves.
*   **💘 Propuesta Interactiva**: Una pregunta final (¿Quieres ser mi San Valentín?) con botones interactivos.
*   **⏳ Cuenta Regresiva**: Un contador en tiempo real para el próximo San Valentín (o la fecha que elijas).
*   **📱 Diseño Responsivo**: Funciona perfectamente en computadoras y celulares.

## 🚀 Cómo funciona (Demo)

1.  **El Código**: Al iniciar, debes ingresar la fecha de inicio de la relación.
    *   *Configuración por defecto: **23 de Julio de 2023** (Código: `23 07 23`)*.
2.  **La Historia**: Al desbloquear, navega por los recuerdos especiales.
3.  **El Final**: Acepta la propuesta para ver una celebración de fuegos artificiales y corazones.

## 🛠️ Cómo Personalizarlo para TI

¿Quieres usar esto para tu propia pareja? ¡Es muy fácil! Solo necesitas editar el archivo `index.html`.

1.  **Descarga el archivo** `index.html` o clona este repositorio.
2.  Ábrelo con cualquier editor de texto (como Bloc de Notas, VS Code, Sublime Text).
3.  Busca la etiqueta `<script>` cerca del final del archivo.

### 1. Cambiar la Fecha Especial (La contraseña)
Busca esta línea:
```javascript
const startDate = new Date(2023, 6, 23);
```
Cambia los números: `(Año, Mes, Día)`.
> **⚠️ IMPORTANTE**: En programación, los meses empiezan en 0.
> *   Enero = 0
> *   Febrero = 1
> *   ...
> *   Julio = 6
> *   Diciembre = 11

### 2. Cambiar los textos de la Historia
Busca la sección `const storySequence`. Ahí puedes cambiar los mensajes y el tiempo que dura cada uno:
```javascript
{ text: "Tu mensaje personalizado aquí...", time: 6000 },
```

---

## 🌐 Cómo subirlo a Internet (Tu Página Personal)

Para que tu persona especial pueda ver esto desde su celular en cualquier lugar, puedes subirlo gratis usando **GitHub Pages**.

### Opción A: Usando GitHub (Recomendado)

1.  **Crea una cuenta** en [GitHub.com](https://github.com/) si no tienes una.
2.  Crea un **Nuevo Repositorio** (botón "New" o "+").
    *   Nombre del repositorio: `tu-usuario.github.io` (Reemplaza `tu-usuario` con tu nombre de usuario real de GitHub).
    *   Asegúrate de que sea **Público**.
    *   Marca la casilla "Add a README file".
3.  Dentro de tu nuevo repositorio, haz clic en **Add file** > **Upload files**.
4.  Arrastra tu archivo `index.html` (ya personalizado) y dale al botón **Commit changes**.
5.  ¡Listo! En unos minutos, entra a `https://tu-usuario.github.io` y verás tu página.

### Opción B: Si haces un Fork de este repositorio

1.  Dale clic al botón **Fork** arriba a la derecha de esta página.
2.  Ve a la pestaña **Settings** (Configuración) de tu repositorio copiado.
3.  En el menú de la izquierda, busca la sección **Pages**.
4.  Debajo de "Build and deployment", en **Branch**, selecciona `main` (o `master`) y guarda.
5.  Tu página estará lista en el enlace que te mostrará GitHub ahí mismo.

---

Disfruta creando momentos inolvidables. ❤️

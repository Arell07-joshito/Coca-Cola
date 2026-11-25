# Coca-Cola: La Chispa de la Cultura Global

Presentación web interactiva de **12 diapositivas** sobre la historia, el diseño industrial, el marketing emocional y el impacto global de **Coca-Cola**, lista para alojar en **GitHub** y publicar como sitio web en **GitHub Pages**.

---

## Características de la Presentación

- **12 diapositivas temáticas** con identidad visual inspirada en Coca-Cola (Rojo #F40009, tipografía caligráfica estilo *Spencerian*, crema vintage y modo oscuro).
- **100% autocontenida (`index.html`)**: no requiere dependencias ni instalaciones externas.
- **Controles interactivos**:
  - Navegación con teclado (`←`, `→`, `Espacio`) y gestos táctiles en móviles.
  - **Notas del orador** integradas (tecla `N` o botón superior).
  - **Modo pantalla completa** (tecla `F` o botón superior).
  - Animación sutil de burbujas carbonatadas y barra de progreso.

---

## Estructura del Repositorio

```text
coca-cola-presentacion/
├── index.html   # Presentación web interactiva completa (12 diapositivas)
└── README.md    # Documentación del proyecto y guía de despliegue
```

---

## Cómo subirlo a GitHub y publicarlo con GitHub Pages

### Opción 1: Desde la web de GitHub (sin usar terminal)
1. Crea un nuevo repositorio en [GitHub](https://github.com/new) (por ejemplo: `coca-cola-presentacion`) y márcalo como **Public**.
2. Haz clic en **Add file** → **Upload files**.
3. Arrastra los archivos `index.html` y `README.md` y haz clic en **Commit changes**.
4. Ve a **Settings** → **Pages** (en el menú lateral izquierdo).
5. En **Build and deployment** → **Branch**, selecciona `main` y la carpeta `/ (root)`, luego haz clic en **Save**.
6. En 1 minuto tendrás tu presentación publicada en línea en:  
   `https://TU-USUARIO.github.io/coca-cola-presentacion/`

### Opción 2: Usando Git desde la terminal
```bash
git init
git add index.html README.md
git commit -m "feat: agregar presentacion interactiva sobre Coca-Cola"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/coca-cola-presentacion.git
git push -u origin main
```

# 🌿 EcoMarket

## 📖 Descripción del proyecto

Sitio web de un e-commerce de productos sustentables, desarrollado con **HTML5 y CSS3 puro** (sin frameworks ni JavaScript). Presenta un catálogo de 20 productos ecológicos para el cuidado personal, el hogar y el estilo de vida, junto con la historia, los valores y las opiniones de clientes de la marca.

🌐 **Sitio en vivo:** 
moonlit-cassata-71deec.netlify.app


> Proyecto académico. Los filtros del catálogo son visuales y los testimonios son ficticios.

## 📸 Capturas de pantalla

El sitio es responsive. A continuación se muestran las vistas principales en escritorio y en móvil.

### 🖥️ Vista de escritorio

| Inicio | Catálogo |
|:---:|:---:|
<img width="1918" height="956" alt="image" src="https://github.com/user-attachments/assets/f8caf7dc-e0c3-423f-b7fd-3314fd436f90" />


| Detalle de producto | Sobre Nosotros |
|:---:|:---:|
<img width="1192" height="773" alt="image" src="https://github.com/user-attachments/assets/2fc26096-8e17-4ba1-a58e-f15bfad3c7fa" />


| Contacto |
|:---:|
<img width="1900" height="951" alt="image" src="https://github.com/user-attachments/assets/6ed4aea5-ff7e-4f83-9b59-b24b6b2547ef" />


### 📱 Vista móvil

| Inicio |

<img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/a82a059f-42e7-4007-b99c-7288d9b90373" />


| Sobre Nosotros 
|:---:|:---:|
<img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/a686a94f-ff2a-4193-aa56-1517b965de60" />


## ✨ Características

- Catálogo de **20 productos** repartido en 2 páginas con paginación.
- Barra lateral de filtros por categoría (Cuidado Personal, Hogar y Limpieza, Estilo de Vida).
- Página de **detalle de producto** enlazada desde cada tarjeta.
- Página **Sobre Nosotros** con historia, misión, valores, impacto ambiental y reseñas de clientes.
- Formulario de **contacto** para solicitar productos.
- Diseño **responsive** con CSS Grid y Flexbox.
- Accesibilidad básica: enlace "Saltar al contenido", `aria-label`, `aria-current` y textos `alt` descriptivos en todas las imágenes.
- Precios en pesos colombianos (COP).

## 🗂️ Estructura del proyecto

```
EcoMarket/
├── index.html
├── css/
│   ├── main.css          # Estilos base y variables
│   ├── components.css    # Tarjetas, botones, reseñas, paginación
│   ├── layout.css        # Estructura de páginas y cuadrículas
│   └── animations.css    # Transiciones y animaciones
├── img/
│   └── products/         # Imágenes de los 20 productos
├── docs/
│   └── screenshots/      # Capturas para el README (escritorio y móvil)
└── views/
    ├── productos.html        # Catálogo, página 1
    ├── productos-p2.html     # Catálogo, página 2
    ├── detalle-producto.html # Detalle de cada producto
    ├── sobre-nosotros.html   # Historia, valores, impacto y reseñas
    └── contacto.html         # Formulario de contacto
```

## 🚀 Instrucciones de visualización

No requiere instalación ni dependencias.

**Opción 1: abrir directamente**
1. Descarga o clona el repositorio.
2. Abre `index.html` en tu navegador.

**Opción 2: con un servidor local (recomendado)**

Con la extensión *Live Server* de VS Code, haz clic derecho en `index.html` y elige **Open with Live Server**. También puedes usar Python:

```bash
python -m http.server 8000
```

y abrir `http://localhost:8000`.

```bash
git clone https://github.com/castrorueda-afk/EcoMarket_Juan_Manuel_Castro.git
cd EcoMarket_Juan_Manuel_Castro
```

## 🌍 Despliegue

El sitio está publicado en internet y se puede visitar sin instalar nada:

**https://TU-SITIO.netlify.app** <!-- REEMPLAZAR por tu URL real de Netlify -->

- **Plataforma:** [Netlify](https://www.netlify.com/)
- **Tipo de sitio:** estático (HTML y CSS, sin proceso de compilación)
- **Actualización:** automática. Cada `git push` a la rama `main` redespliega el sitio.

### Cómo se desplegó

1. Se subió el proyecto a GitHub, con `index.html` en la raíz y las imágenes en `img/products/`.
2. En Netlify: **Add new site → Import an existing project → GitHub**, y se seleccionó el repositorio `EcoMarket_Juan_Manuel_Castro`.
3. Se dejaron **vacíos** el *Build command* y el *Publish directory*, porque no hay nada que compilar.
4. Se pulsó **Deploy**. En menos de un minuto el sitio quedó disponible en su URL pública.
5. Opcionalmente se cambió el nombre en **Site configuration → Change site name**.

### Cómo desplegarlo por tu cuenta

- **Netlify (arrastrar y soltar):** entra a [app.netlify.com/drop](https://app.netlify.com/drop) y arrastra la carpeta completa del proyecto.
- **Vercel:** importa el repositorio, elige **Other** como *Framework Preset* y deja vacíos *Build Command* y *Output Directory*.
- **GitHub Pages:** en **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`.

Las rutas relativas del proyecto (`../css/...`, `../img/...`) funcionan igual en las tres opciones.

### Verificación después de publicar

- [x] El despliegue terminó sin errores en Netlify.
- [ ] El sitio carga desde una ventana de incógnito y desde el celular.
- [ ] Las páginas abren bien: inicio, catálogo (1 y 2), detalle, sobre nosotros y contacto.
- [ ] Se ven las 20 imágenes de los productos.
- [ ] Los enlaces del menú y de la paginación funcionan.

## 🛍️ Productos

| Categoría | Productos |
|---|---|
| **Cuidado personal** | Cepillo de bambú, shampoo sólido, acondicionador sólido, desodorante natural, jabón de avena, discos desmaquillantes, esponja de luffa |
| **Hogar** | Detox de cocina, detergente en hojas, servilletas de tela, bolsas de silicona, envoltorios de cera de abeja, velas de cera de soja |
| **Estilo de vida** | Bolsa tote bag, bolsas de malla, botella térmica, cubiertos de bambú, popotes de acero, vaso plegable, cuaderno reciclado |

## 🖼️ Convención de imágenes

Las imágenes viven en `img/products/` y siguen estas reglas para evitar errores de carga, sobre todo en servidores Linux y GitHub Pages, donde se distinguen mayúsculas y minúsculas:

- Nombres en **minúsculas**, separados por **guiones**.
- Sin espacios, tildes ni caracteres especiales.
- Extensión real del archivo (`.jpg`, `.png` o `.webp`).

Ejemplo: `cepillo-de-bambu.jpg`.

## 🛠️ Tecnologías

- HTML5 semántico
- CSS3 (Grid, Flexbox, variables CSS, media queries)

## 🔮 Posibles mejoras

- Hacer funcionales los filtros del catálogo.
- Carrito de compras y proceso de pago.
- Buscador de productos.
- Reseñas reales de clientes.
- Optimizar las imágenes (por ejemplo, convertir todas a `.webp`).

## 👤 Autor

**Juan Manuel Castro**
GitHub: [@castrorueda-afk](https://github.com/castrorueda-afk)

## 📄 Licencia

Proyecto con fines educativos. Define aquí la licencia que prefieras (por ejemplo, MIT) si decides publicarlo.

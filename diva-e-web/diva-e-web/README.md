# DIVA E · Sitio web

Sitio estático (HTML, CSS y JavaScript en un solo archivo `index.html`, más la carpeta `assets/`). No requiere instalación ni comando de compilación.

## Publicar en Vercel

**Opción rápida (sin GitHub)**
1. Entra a https://vercel.com/new y elige subir una carpeta, o arrastra la carpeta `diva-e-web` completa.
2. En "Framework Preset" deja **Other**. No llenes "Build Command" ni "Output Directory".
3. Pulsa **Deploy**. En un minuto tendrás tu link `.vercel.app`.

**Opción con GitHub (recomendada para hacer cambios después)**
1. Crea un repositorio y sube el contenido de esta carpeta (`index.html` debe quedar en la raíz).
2. En Vercel: Add New → Project → importa el repositorio → Deploy.
3. Cada cambio que subas a GitHub se publica solo.

**Desde la terminal**
```
npm i -g vercel
cd diva-e-web
vercel --prod
```

## Ver en tu computador antes de publicar
Abre `index.html` con doble clic, o ejecuta `python3 -m http.server 8000` dentro de la carpeta y visita http://localhost:8000.

## Estructura
- `index.html`: todo el sitio (estructura, estilos y animaciones).
- `assets/`: fotografías optimizadas en formato webp. `vial.webp` es el vial recortado sin fondo.

## Pendientes antes de abrirlo al público
- Validar biografía, capítulos y preguntas de Diva Academy con Diva Elisa Bustamante.
- Conectar el formulario de Diva Room a un canal real (hoy solo muestra un mensaje de confirmación de prueba).
- Verificar documentación y autorizaciones antes de publicar afirmaciones sobre HidraRegen 3D.
- Definir la política de tratamiento de datos antes de recibir registros.

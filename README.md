# Reporta Ya! — Landing page

Landing page estática de Reporta Ya!, creada con HTML semántico, CSS y JavaScript sin dependencias de runtime. Incluye una escena hero con profundidad 3D, animación sutil y controles compatibles con movimiento reducido.

## Ejecutar en Visual Studio Code

Requisitos: Node.js 20.19+ o 22.12+ y npm.

1. Abre la carpeta `reporta-ya-landing` en VS Code.
2. Abre **Terminal → Nuevo terminal** en VS Code.
3. Instala las dependencias una sola vez:

   ```bash
   npm install
   ```

4. Inicia el servidor de desarrollo:

   ```bash
   npm run dev
   ```

5. Abre la dirección que imprime Vite, normalmente `http://127.0.0.1:5173/`.

Para generar la versión de producción usa `npm run build`. Para verla localmente después de compilar, ejecuta `npm run preview`.

No requiere `.env`, API ni base de datos: es únicamente la landing pública del producto.

## Estructura

```text
reporta-ya-landing/
├── assets/
│   ├── css/styles.css
│   ├── images/reporta-mark.svg
│   └── js/main.js
├── docs/aviso-de-uso.md
├── package.json
├── vite.config.js
├── .editorconfig
├── .gitignore
├── .nojekyll
├── index.html
├── LICENSE
└── README.md
```

## Alcance responsable

La landing explica el propósito del producto y no recopila datos. No se deben ingresar amenazas, nombres ni evidencias en formularios de demostración. Reporta Ya! organiza información y no reemplaza a las autoridades ni ofrece asesoría legal.

## Licencia

MIT. Copyright © 2026 STACK TEAM.

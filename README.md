# CV — Jesús Aguilar

Portfolio / CV web personal hecho con HTML, CSS y JavaScript puro.

## 🚀 Tecnologías usadas

- HTML5
- CSS3 (variables, grid, flexbox, animaciones)
- JavaScript vanilla

## 📂 Estructura

```
cv-jesus-aguilar/
└── index.html   ← todo en un solo archivo
```

## ▶️ Cómo correrlo localmente

Abrí `index.html` directamente en el navegador, o con un servidor local:

```bash
# Con Node.js
node -e "require('http').createServer((req,res)=>{require('fs').readFile('./index.html',(e,d)=>{res.writeHead(200,{'Content-Type':'text/html'});res.end(d)});}).listen(3000)"
```

Luego entrá a [http://localhost:3000](http://localhost:3000)

## 🌐 Deploy en GitHub Pages

1. Subí el repo a GitHub
2. Andá a **Settings → Pages**
3. En "Branch" seleccioná `main` y carpeta `/ (root)`
4. ¡Listo! Tu CV va a estar online en `https://tuusuario.github.io/cv-jesus-aguilar`

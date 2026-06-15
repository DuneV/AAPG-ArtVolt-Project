# ArVolt Landing Page

Landing page del proyecto ArVolt para GitHub Pages.

**"One tower. Every source. Any territory."**

## 🚀 Cómo publicar en GitHub Pages

### Opción 1 — Repositorio nuevo (recomendada)

1. Ve a [github.com/new](https://github.com/new) y crea un repositorio llamado `arvolt` (o `arvolt-landing`).
2. Sube los archivos:
   ```bash
   cd arvolt-landing
   git init
   git add .
   git commit -m "Initial ArVolt landing page"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/arvolt.git
   git push -u origin main
   ```
3. En GitHub → Settings → Pages → Source: **Deploy from branch `main` / `/ (root)`**
4. En ~1 minuto tu página estará en `https://TU_USUARIO.github.io/arvolt/`

### Opción 2 — Repositorio `usuario.github.io`

Si quieres que sea tu página principal:
1. Crea un repo llamado `TU_USUARIO.github.io`
2. Sube los archivos igual que arriba
3. Queda en `https://TU_USUARIO.github.io/`

---

## Estructura

```
arvolt-landing/
└── index.html    ← Todo en un solo archivo (HTML + CSS)
```

## Personalización rápida

- **Email de contacto**: busca `arvolt@contact.co` en el HTML y reemplázalo
- **Video**: el ID de YouTube `hCwC5xsjuMc` está en el iframe embed
- **Colores**: ajusta las variables CSS en `:root` al inicio del `<style>`
- **Founders**: edita las tarjetas en la sección `#team`

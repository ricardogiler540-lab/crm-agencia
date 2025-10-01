
# CRM Kommo-like (BM Tours) — Ready for Vercel

Este repositorio contiene un prototipo de CRM construido en React + Vite + Tailwind.
Sigue estos pasos para publicarlo online en Vercel.

## 1) Preparar local (opcional)
Si quieres ejecutar localmente:
- Instala Node.js (LTS): https://nodejs.org
- Luego en la carpeta del proyecto:
```bash
npm install
npm run dev
```
La app abrirá en http://localhost:5173

## 2) Subir a GitHub
1. Crea un nuevo repositorio en GitHub (por ejemplo: `crm-kommo-like`).
2. Desde tu PC arrastra los archivos (o usa `git`):
```bash
git init
git add .
git commit -m "Initial commit - CRM prototype"
git branch -M main
git remote add origin https://github.com/YOUR_USER/YOUR_REPO.git
git push -u origin main
```

## 3) Desplegar en Vercel (recomendado)
1. Accede a https://vercel.com and login.
2. Click **New Project** → **Import Git Repository** → elige el repo que subiste.
3. Vercel detectará automáticamente Vite. Haz clic en **Deploy**.
4. En minutos tendrás tu URL pública, por ejemplo `https://crm-kommo-like.vercel.app`.

## Notas
- Este prototipo usa `localStorage` para persistencia. Para multiusuario en producción necesitas backend + base de datos.
- Si quieres, puedo preparar la arquitectura backend (Node + Express + PostgreSQL) y añadir autenticación.
- Para personalizar dominio o seguridad, comentamos los siguientes pasos.


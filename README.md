# 🍕 Pizzería Mamma Mía - React

Proyecto desarrollado en React para el curso de Desafío Latam.

## 🚀 Descripción

Aplicación web de una pizzería que permite:

- Visualizar pizzas desde una API
- Ver el detalle de una pizza
- Navegar entre distintas vistas con React Router
- Simular un carrito de compras
- Acceder a páginas de login, registro y perfil
- Por ahora, en el menú Profile, tanto el botón de cerrar sesión como el email del usuario son estáticos. En los siguientes hitos se implementará

## 🛠 Tecnologías

### Frontend
- React
- React Router DOM
- Bootstrap
- Fetch API

### Backend (material de apoyo)
- Node.js
- Express

## 📦 Instalación Frontend

```bash
npm install
npm run dev
``` 

## 🔌 Backend

Este proyecto utiliza un backend de apoyo (Node + Express) para servir las pizzas.

Pasos para levantar el backend
``` Bash
npm install
npm start
```

El servidor se ejecuta en:

http://localhost:5000

📡 Endpoints utilizados
- GET http://localhost:5000/api/pizzas
- GET http://localhost:5000/api/pizzas/p001

# UPTASK MERN - Frontend

Este es el **frontend** del proyecto **UPTASK MERN**, construido con **React + TypeScript + Vite**.  
Se conecta a una API backend para la gestión de proyectos, tareas, notas y perfiles de usuario.  

---

## 🚀 Tecnologías utilizadas

- React + Vite
- TypeScript
- React Router
- TailwindCSS
- Axios

---

## 📦 Instalación

Clona el repositorio:

```bash
git clone https://github.com/crisomarjs/uptask-frontend
cd uptask-frontend
npm install
````
## ⚙️ Configuración de variables de entorno
Debes crear un archivo .env.local en la raíz del proyecto (uptask_frontend) con la siguiente variable:

```bash
VITE_API_URL= urldelbackend
````

## 📂 Estructura del proyecto
```bash
src/
 ├── components/      # Componentes reutilizables
 │   ├── auth/
 │   ├── notes/
 │   ├── profile/
 │   ├── projects/
 │   ├── tasks/
 │   ├── team/
 │   ├── ErrorMessage.tsx
 │   └── NavMenu.tsx
 │
 ├── hooks/           # Custom hooks
 ├── layouts/         # Layouts principales
 ├── lib/             # Librerías y helpers
 ├── locales/         # Traducciones (i18n)
 ├── types/           # Tipado global de TypeScript
 ├── utils/           # Funciones utilitarias
 │
 ├── views/           # Vistas del frontend
 │   ├── 404/
 │   ├── auth/
 │   ├── profile/
 │   └── projects/
 │
 ├── DashboardView.tsx
 ├── router.tsx
 └── main.tsx
````

---
## 🔗 Repositorios

- [Frontend](https://github.com/crisomarjs/uptask-frontend)
- [Backend](https://github.com/crisomarjs/backend-uptask)

# Velarys — Backend

API REST en Node.js + Express para la aplicación Velarys. Maneja autenticación con JWT, persistencia en MySQL y está preparada para despliegue serverless en Vercel.

## Stack

- **Runtime:** Node.js
- **Framework:** Express
- **Base de datos:** MySQL (via `mysql2`)
- **Autenticación:** JSON Web Tokens (JWT) + bcrypt / bcryptjs
- **Deploy:** Vercel (configuración en `vercel.json`)
- **Testing:** Mocha + Chai + Supertest

## Estructura

```
app.js          Entrada de la app Express
config.js       Configuración (BD, secretos, variables)
routes/         Definición de endpoints
controllers/    Lógica de negocio
models/         Modelos de datos
```

## Cómo correrlo

```bash
npm install
npm start
```

Variables de entorno necesarias (configúralas en `.env` o en el panel de Vercel): credenciales de MySQL y `JWT_SECRET`.

## Repositorio relacionado

- [Velarys-Front-End](https://github.com/Cristian-Oropeza/Velarys-Front-End) — cliente web en Angular

## Autor

Cristian Oropeza Yepiz · [LinkedIn](https://linkedin.com/in/cristian-oropeza-yepiz) · [Perfil GitHub](https://github.com/Cristian-Oropeza)

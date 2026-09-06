# Voluntarios — Estacionamiento

Aplicación web móvil para registrar voluntarios y administrar turnos de estacionamiento.

## Arquitectura

- Frontend: HTML/CSS/JavaScript estático.
- Backend: Supabase (PostgreSQL, Auth y Realtime).
- Hosting: Vercel.

## Publicación en Vercel

Importar este repositorio y usar:

- Framework Preset: Other
- Build Command: vacío
- Output Directory: `.`
- Install Command: vacío

No requiere Node.js ni proceso de compilación.

## Seguridad

Los datos de voluntarios se leen únicamente con sesión autenticada. El registro público usa una función RPC que controla la capacidad de los turnos en servidor.

## Estado

V1 preparada para pruebas de producción. Antes del evento debe probarse registro concurrente desde varios teléfonos y la autenticación del administrador.
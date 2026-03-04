# Sistema de Gestion de Consultorios

Aplicacion web para la administracion de centros de salud y consultorios, construida sobre Next.js. El proyecto usa la marca funcional `ProSalud` y centraliza la operacion diaria de pacientes, profesionales, turnos e historias clinicas desde una sola interfaz.

## Que incluye hoy

- Landing publica para presentar el producto y sus funcionalidades.
- Autenticacion con Clerk para proteger las areas privadas.
- Integracion con Convex como backend y base de datos en tiempo real.
- Paneles separados por rol para recepcion, gerencia y profesionales.
- Gestion de pacientes, profesionales, especialidades y obras sociales.
- Agenda de turnos con vistas de calendario, tabla y modales de edicion.
- Historias clinicas con diagnosticos, indicaciones, medicamentos y tratamientos.
- Reportes visuales para seguimiento operativo y ocupacion.

## Modulos principales

### Recepcionista

- Alta y consulta de pacientes.
- Gestion de turnos.
- Calendario de disponibilidad.
- Acceso a historias clinicas.
- Administracion de profesionales.

### Gerencia

- Gestion de pacientes.
- Gestion de profesionales.
- Gestion de especialidades.
- Gestion de obras sociales.
- Reportes con metricas y visualizaciones.

### Profesional

- Vista de turnos del dia.
- Agenda y calendario.
- Consulta de pacientes.
- Carga y seguimiento de historias clinicas.
- Perfil y reportes.

## Stack tecnico

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS 4
- Clerk
- Convex
- Radix UI
- Recharts

## Estructura del proyecto

- `app/`: rutas y pantallas principales, separadas por roles.
- `components/`: componentes reutilizables de UI y modulos funcionales.
- `convex/`: esquema, funciones y logica de datos.
- `hooks/`: hooks de soporte para UI y sincronizacion.
- `lib/`: utilidades compartidas.
- `public/`: assets estaticos.

## Puesta en marcha

1. Instalar dependencias:

```bash
npm install
```

2. Configurar variables de entorno necesarias para Clerk y Convex.

Variables minimas detectadas en el codigo:

- `NEXT_PUBLIC_CONVEX_URL`
- Variables de Clerk para cliente y servidor

3. Iniciar el proyecto en desarrollo:

```bash
npm run dev
```

4. Abrir `http://localhost:3000`.

## Scripts disponibles

- `npm run dev`: inicia el entorno de desarrollo.
- `npm run build`: genera la build de produccion.
- `npm run start`: levanta la aplicacion compilada.
- `npm run lint`: ejecuta ESLint.

## Estado actual

Este repositorio ya contiene el codigo base del proyecto actual y sirve como punto de partida para continuar el desarrollo, ordenar modulos y preparar futuras mejoras funcionales.

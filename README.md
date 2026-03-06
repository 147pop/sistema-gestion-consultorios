# Sistema de Gestión de Consultorios - ProSalud

**Plataforma integral de gestión para centros de salud y consultorios médicos** construida con tecnologías modernas (Next.js, React, TypeScript) que centraliza la administración de pacientes, profesionales, turnos e historias clínicas en una interfaz colaborativa.

## 🎯 Propósito

ProSalud es una solución empresarial para automatizar y optimizar las operaciones diarias de:
- Centros médicos y políclinicos
- Consultorios privados
- Clínicas especializadas
- Obras sociales y seguros

Permite que recepcionistas, profesionales y gerentes trabajen en sincronía desde una plataforma única con control de acceso por roles.

---

## ✨ Características Principales

### 👥 Gestión de Pacientes
- Registro completo con datos personales, documentación y contacto
- Búsqueda rápida y filtrado avanzado
- Historial de atenciones y tratamientos
- Integración con obras sociales y planes de cobertura

### 📅 Sistema de Agenda y Turnos
- **Calendario interactivo** con vista mensual, semanal y diaria
- **Formulario inteligente** para agendar turnos con validaciones
- **Estados de turnos**: pendiente, confirmado, completado, cancelado
- Disponibilidad de profesionales por especialidad
- Notificaciones y recordatorios
- Vista tabular de turnos con filtros

### 📋 Historias Clínicas Digitales
- Carga de diagnósticos, síntomas e indicaciones
- Registro de medicamentos y tratamientos prescritos
- Notas evolutivas del profesional
- Acceso control por roles (lectura/escritura según perfil)
- Trazabilidad completa de cambios

### 📊 Reportes y Análisis
- Dashboard ejecutivo con métricas clave (KPIs)
- Ocupación de consultorio por profesional
- Estadísticas de pacientes atendidos
- Análisis de especialidades más demandadas
- Reportes exportables para auditoría

### 🔐 Control de Acceso y Seguridad
- Autenticación integrada con **Clerk** (OAuth, passwords, 2FA)
- Paneles separados por rol:
  - **Recepcionista**: gestión de pacientes y turnos
  - **Profesional**: agenda personal y carga de historias
  - **Gerencia**: reportes, configuración y administración
- Variables de entorno para datos sensibles

---

## 🏗️ Arquitectura Técnica

### Tech Stack
- **Frontend**: Next.js 15 + React 19 + TypeScript
- **Styling**: Tailwind CSS 4 + Radix UI (componentes accesibles)
- **Backend BaaS**: Convex (base de datos en tiempo real, serverless functions)
- **Autenticación**: Clerk
- **Visualización**: Recharts (gráficos y dashboards)
- **Code Quality**: ESLint + TypeScript strict mode

### Estructura del Proyecto

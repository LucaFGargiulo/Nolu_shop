# Nolu Shop

> E-commerce full stack orientado a una experiencia de compra rápida, segura y responsive.

## Acerca del proyecto

**Nolu Shop** es un proyecto de e-commerce. Su objetivo es construir una tienda online moderna, escalable y segura.

La primera versión se enfocará en una tienda de un solo vendedor.

## Objetivo

Construir una aplicación web que permita explorar productos, realizar compras de forma segura y administrar catálogo, inventario y órdenes desde un panel de administración.

Además de resolver una necesidad de negocio, el proyecto busca demostrar buenas prácticas de desarrollo: tipado end-to-end, diseño responsive, separación de responsabilidades, control de acceso, documentación y despliegue reproducible.

## Stack tecnológico

| Capa | Tecnologías |
| --- | --- |
| Frontend | Next.js, React, TypeScript y Tailwind CSS |
| Backend | NestJS, Node.js y TypeScript |
| Base de datos | PostgreSQL con Prisma ORM |
| Servicios previstos | Supabase (base de datos, autenticación y/o almacenamiento) y Mercado Pago |
| Calidad | ESLint, Prettier y pruebas automatizadas |
| Control de versiones | Git y GitHub |

## Funcionalidades — versión 1

- Catálogo de productos y categorías.
- Búsqueda y filtrado de productos.
- Detalle de producto con disponibilidad y stock.
- Registro, inicio de sesión y gestión de perfil.
- Carrito de compras persistente.
- Checkout e integración de pagos.
- Historial y estado de órdenes para clientes.
- Panel de administración para productos, categorías, stock y órdenes.
- Diseño adaptable a dispositivos móviles, tablet y escritorio.

## Alcance futuro

- Lista de favoritos.
- Cupones y promociones.
- Reseñas de productos.
- Métricas y panel de ventas.
- Integración con servicios de envío.
- Marketplace multi-vendedor.

## Arquitectura

```text
Cliente
  │
  ▼
Frontend · Next.js
  │
  ▼
API · NestJS
  ├── PostgreSQL · Prisma
  ├── Autenticación / almacenamiento · Supabase
  └── Pagos · Mercado Pago
```

## Estructura del repositorio

```text
Nolu_shop/
├── frontend/       # Aplicación Next.js
├── backend/        # API NestJS y Prisma
├── docs/           # Documentación técnica, diagramas y decisiones
└── README.md
```

## Principios del proyecto

- **Seguridad desde el diseño:** las credenciales se gestionan mediante variables de entorno y nunca se suben al repositorio.
- **Experiencia de usuario:** interfaz clara, rápida, accesible y responsive.
- **Código mantenible:** componentes reutilizables, módulos con responsabilidades definidas y TypeScript en todo el stack.
- **Evolución controlada:** funcionalidades organizadas en un backlog y entregadas por iteraciones.

## Estado del proyecto

Actualmente, **Nolu Shop se encuentra en etapa de planificación y definición funcional**. El repositorio contiene la estructura inicial de frontend y backend; los requisitos, el diseño y la arquitectura se documentarán antes de comenzar el desarrollo de funcionalidades.

## Roadmap inicial

- [x] Crear repositorio y estructura base.
- [x] Inicializar frontend con Next.js, TypeScript y Tailwind CSS.
- [x] Inicializar backend con NestJS y Prisma.
- [ ] Definir alcance de la versión 1.
- [ ] Diseñar wireframes y sistema visual.
- [ ] Modelar la base de datos.
- [ ] Implementar autenticación y roles.
- [ ] Implementar catálogo, carrito y órdenes.
- [ ] Integrar pagos y panel de administración.
- [ ] Probar, documentar y desplegar.

## Autor

Desarrollado por [Luca Gargiulo](https://github.com/LucaFGargiulo) y [Noelia Coro](https://github.com/noecoro).

---

_Proyecto de portfolio en evolución. Las funcionalidades y decisiones técnicas podrán ajustarse durante el desarrollo._

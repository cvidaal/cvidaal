# Carlos Vidal · Backend Developer (Go)

Desarrollo integraciones en Go en **Top Doctors**. Sincronizo agendas y citas entre la plataforma y sistemas externos del sector salud (aseguradoras, hospitales, software de gestión clínica, diagnóstico por imagen) usando APIs REST, webhooks y GCP Pub/Sub.

El código de mi trabajo es privado. Aquí están mis proyectos personales.

## Lo que hago

- **Más de 10 integraciones** con APIs de terceros: datos maestros (centros, doctores, servicios, seguros) y ciclo completo de citas.
- **Procesamiento asíncrono** con GCP Pub/Sub: publicación de eventos y handlers por proveedor.
- **Pipeline de ingesta** semanal de un catálogo público de medicamentos: parseo de XML, modelo relacional, migraciones y API HTTP.
- **Servicios por capas** (handlers, servicios, repositorios, mappers) con tests unitarios y mocks.

## Proyecto destacado

### [Acelerik Booking](https://github.com/cvidaal/acelerik-demo): API de reservas y pagos en Go

Sistema de reservas y cobro de señal para parques infantiles.

- API REST con **Gin + Huma** (documentación OpenAPI generada) sobre **PostgreSQL** con **pgx**.
- Máquina de estados de reservas validada: pendiente, confirmada, cancelada, completada.
- Cobro de señal con **Stripe Checkout y webhooks**, con transacciones y `SELECT … FOR UPDATE` para evitar pagos duplicados.
- Tests unitarios table-driven de servicios y handlers.

## Stack

- **Backend:** Go · Gin · APIs REST · Webhooks · GCP Pub/Sub
- **Datos:** SQL · PostgreSQL · GORM · pgx
- **Testing y herramientas:** testing de Go · mockery · Docker · Git
- **También he trabajado con:** TypeScript · Node.js · React · Flutter

## Contacto

[LinkedIn](https://www.linkedin.com/in/carlosvidaldev) · [carlosvidal.developer@gmail.com](mailto:carlosvidal.developer@gmail.com)

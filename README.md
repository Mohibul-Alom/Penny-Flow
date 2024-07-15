# Penny Flow Back

Penny Flow es una aplicación backend de gestión de dinero personal diseñada para ayudarte a realizar un seguimiento de tus ingresos y gastos. Construida enteramente con NESTJS, esta aplicación permite a los usuarios gestionar sus finanzas de manera eficiente y colaborativa.

## Características

- **Registro de Ingresos y Gastos**: Inserta el dinero total que tienes y añade los gastos diarios.
- **Categorías de Gastos**: Organiza tus gastos diarios en diferentes categorías.
- **Balance Actualizado**: Visualiza el balance actualizado restando los gastos del dinero total.
- **Ingresos y Gastos Recurrentes**: Programa ingresos y gastos recurrentes para una planificación financiera más precisa.
- **Multiusuario**: Permite que varias personas gestionen una única cuenta compartida.
- **Notificaciones en Tiempo Real** (próximamente): Recibe notificaciones instantáneas sobre movimientos en tu cuenta.

## Tecnologías Utilizadas

- **NestJs**: Para la lógica de negocio, gestión de datos y API.
- **KYSELY**: Para la manipulación de datos y la integración con la base de datos.
- **Arquitectura Hexagonal**: Para una estructura de código mantenible y escalable.

## Installation

```bash
$ pnpm install
```

## Running the app

```bash
# development
$ pnpm run start

# watch mode
$ pnpm run start:dev

# production mode
$ pnpm run start:prod
```

## Test

```bash
# unit tests
$ pnpm run test

# e2e tests
$ pnpm run test:e2e

# test coverage
$ pnpm run test:cov
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).

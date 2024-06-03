This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

=============================================================================================================

Release 1 (MVP): --------------------------------------------------------------------------------------------

29/05/2024 23:35 hrs (USUARIO) :
El sitio ya cuenta con un SIDEBAR dónde se despliegan las categorias disponibles en el Quiosco de Comida (US1).

30/05/2024 16:23 hrs (ADMIN):
Según la Categoría seleccionada se muestran los productos pertenecientes a esa Categoría junto con una imagen del Producto (US5).

01/06/2024 09:54 hrs (USUARIO) :
Se implementó que al dar clic en un producto se agregue a mi carrito. Se pueden agregar,
eliminar y modificar cantidades de cada producto y se muestra un subtotal (US2).

01/06/2024 10:56 hrs (USUARIO):
Ya se puede ver un resumen de productos, cantidades, subtotales y total a pagar del carrito de un Uusario. (US3)


Release 2 (MVP): --------------------------------------------------------------------------------------------

02/06/2024 18:33 hrs (ADMIN):
Ahora se pueden realizar pedidos de varias cantidades de distintos productos ingresando el nombre del cliente
antes de confirmar el pedido (US8).

02/06/2024 20:56 hrs (ADMIN):
Se implementó el tablero del administrador que permite visualizar en tarjetas individuales los datos de cada pedido (productos, cantidades, total y nombre del cliente) para su elaboración en la cocina (US9).

02/06/2024 23:10 hrs (ADMIN):
En las tarjetas que muestran cada pedido se agregó un botón que permite marcar como completado un pedido y elimina la tarjeta del tablero (US10).


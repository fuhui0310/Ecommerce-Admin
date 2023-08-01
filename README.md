# Full Stack E-Commerce Project with Next.js 13, React, Tailwind, Prisma, and MySQL - Learning Journal

I worked on this project based on a tutorial by Antonio Erdeljac on Full Stack E-Commerce with a Dashboard & CMS using Next.js 13 App Router, React, Tailwind, Prisma, and MySQL. The purpose of this document is to record my key learnings and experiences from this project.

https://ecommerce-admin-pqnyib3mo-fuhui0310.vercel.app/

## Key Features & Learnings

- **Shadcn UI for Admin**: The admin dashboard was built using Shadcn UI. This helped me understand how to integrate external UI libraries into a Next.js application.

- **Multi-vendor CMS and API**: I learned to create a CMS and API that could handle multiple vendors or stores. This involved creating, updating, and deleting categories, products, and filters.

- **Image Upload**: The application supports multiple image uploads for each product. I understood the complexities involved in handling image uploads in a web application.

- **Search and Pagination**: The ability to search through categories, products, sizes, colors, and billboards and the use of pagination to manage the display of search results was another key learning.

- **Order Creation and Stripe Checkout**: Integrating Stripe for checkout and handling order creation was a key part of this project. This helped me understand the process of integrating third-party payment gateways.

- **Authentication with Clerk**: I learned how to implement authentication in the app using Clerk.

- **MySQL + Prisma + PlanetScale**: Using Prisma as an ORM for MySQL in conjunction with PlanetScale for database management was a valuable experience. I learned how to manage databases, create schemas, and handle database operations.

## Installation and Setup

The project can be cloned and set up locally as follows:

1. **Clone the Repository**: `git clone https://github.com/AntonioErdeljac/next13-ecommerce-admin.git`
2. **Install Packages**: `npm i`
3. **Setup .env file**: Set up environment variables as instructed in the original README.
4. **Connect to PlanetScale and Push Prisma**: `npx prisma generate` followed by `npx prisma db push`
5. **Start the App**: `npm run dev`

## References

- [VIDEO TUTORIAL](https://youtu.be/5miHyP6lExg)

I would recommend this project for anyone looking to gain a hands-on understanding of full-stack web development using modern technologies like Next.js, React, and Prisma.```

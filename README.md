# Ejecutar en Dev

1. Clonar el repositorio
2. Instalar dependencias con `npm install`
3. Generar el archivo de entorno con `cp .env.template .env`
3. Levantar la base de datos con `docker-compose up -d`
4. Generar el Prisma Client con `npx prisma generate`
5. Ejecutar proyecto con `npm run start:dev`

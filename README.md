{
  "name": "nextjs-prisma-starter",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "dev": "next dev -p 3000",
    "build": "next build",
    "start": "next start",
    "lint": "next lint",
    "prisma:migrate": "prisma migrate dev",
    "prisma:generate": "prisma generate",
    "seed": "ts-node --esm prisma/seed.ts"
  },
  "dependencies": {
    "@prisma/client": "^5.0.0",
    "axios": "^1.4.0",
    "bcryptjs": "^2.4.3",
    "next": "13.5.7",
    "next-auth": "^4.22.1",
    "react": "18.2.0",
    "react-dom": "18.2.0",
    "tailwindcss": "^3.5.0"
  },
  "devDependencies": {
    "@types/node": "20.5.1",
    "@types/react": "18.2.27",
    "eslint": "8.49.0",
    "eslint-config-next": "13.5.7",
    "prisma": "^5.0.0",
    "postcss": "^8.4.33",
    "autoprefixer": "^10.4.14",
    "ts-node": "^10.9.1",
    "typescript": "5.9.6"
  }
}

# Product Microservice

## Dev

1. Clone the repository
2. Install dependencies
3. Create a `.env` file based on `env.template`
4. Run prisma immigration `npx prisma migrants dev`
5. Start the NATS server
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
6. Run `npm run start:dev`

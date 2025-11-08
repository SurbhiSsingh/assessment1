This project is that shows how an order execution engine works.
It is made using Node.js, TypeScript, Fastify, Redis (BullMQ), and PostgreSQL.
Takes an order request
Finds the best DEX route
Processes the order in the background using a queue
Sends live status updates through WebSocket
Saves the result in the database
npm install'npm run dev

# schism-gateway

Uses Apollo router to serve as a federated gateway for microservices.

# Environment
1. Rename `example.env` to `.env`
1. `npm i`
1. Start other microservices and their dependencies
1. Fetch their schemas and compose the supergraph with `npm run import:all:compose`
1. Start the router `npm run start:dev`
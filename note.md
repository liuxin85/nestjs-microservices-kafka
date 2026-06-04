npx create-nx-workspace@latest nestjs-microservices

nx add @nx/nest

nx g @nx/nest:app apps/api-gateway

nx serve api-gateway

npm i @nestjs/microservices kafkajs
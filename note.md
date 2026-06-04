npx create-nx-workspace@latest nestjs-microservices

nx add @nx/nest

nx g @nx/nest:app apps/api-gateway

nx serve api-gateway

npm i @nestjs/microservices kafkajs


nx g @nx/nest:app apps/order-microservice
nx g @nx/nest:app apps/payment-microservice

### If nx serve failed, you might need reset
nx reset
nx show projects

nx serve api-gateway
nx serve order-microservice
nx serve payment-microservice


nx g @nx/nest:app apps/notification-microservice
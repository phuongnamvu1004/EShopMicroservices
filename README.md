# EShopMicroservices

This project is an implementation of [Mehmet Ozkaya's EShopMicroservices course](https://github.com/mehmetozkaya/EShopMicroservices).

## Installation

### Prerequisites
- [Docker Desktop](https://www.docker.com/products/docker-desktop)

### Running with Docker
To run the entire solution using Docker Compose, navigate to the `src` directory and execute:

```bash
docker-compose up -d
```

Once the containers are up and running, you can access the services at:
- **Shopping Web (UI):** [http://localhost:6005](http://localhost:6005) (or [https://localhost:6065](https://localhost:6065))
- **Yarp API Gateway:** [http://localhost:6004](http://localhost:6004)
- **Catalog API:** [http://localhost:6000](http://localhost:6000)
- **Basket API:** [http://localhost:6001](http://localhost:6001)
- **Discount gRPC:** [http://localhost:6002](http://localhost:6002)
- **Ordering API:** [http://localhost:6003](http://localhost:6003)
- **RabbitMQ Management:** [http://localhost:15672](http://localhost:15672) (guest/guest)
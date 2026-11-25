# CST8915 Lab 8: Algonquin Pet Store (On Steroids)

- **Student Name:** Tao Lu
- **Student ID:** 41284860
- **Course:** CST8915 Full-stack Cloud-native Development
- **Semester:** Fall 2026

## Demo Video

[Watch the demo on YouTube](https://youtu.be/XyKWRdBkhbs)

## Task 2: Findings on Azure Managed Services

## Task 2: Findings on Azure Managed Services

### MongoDB → Azure Cosmos DB for MongoDB (now called Azure DocumentDB)

MongoDB keeps data, so it is hard to scale in Kubernetes. If we add more pods, the data can get out of sync. Azure Cosmos DB for MongoDB is managed by Azure, so Azure scales it and keeps the data in sync for us.

### RabbitMQ → Azure Service Bus

RabbitMQ keeps messages, so it is also hard to scale in Kubernetes. If a pod restarts, messages can be lost. Azure Service Bus is managed by Azure, so Azure scales it and keeps the messages safe for us.

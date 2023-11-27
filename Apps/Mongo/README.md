# MongoDB

## Overview
MongoDB is a powerful, open-source, NoSQL database that stores data in flexible, JSON-like documents. It is designed for scalability and developer agility, allowing you to query and index data in a non-relational way.

## Features
- Document-oriented storage: JSON-style documents with dynamic schemas.
- Full index support, including on inner fields.
- Replication and high availability.
- Auto-sharding for horizontal scalability.
- Querying and real-time aggregation.

## Installation
- Deploy MongoDB using the provided `docker-compose.yml` file in CasaOS.
- The database will be accessible on port 27017.

## Configuration
- Data is stored in the volume `/DATA/AppData/mongo`.
- The service exposes port 27017 for database connections.

## Usage
- Connect to MongoDB using any standard MongoDB client using `mongodb://<your-host-ip>:27017`.

## Support
For more information and support, visit [MongoDB's official website](https://www.mongodb.com/).

# DB Docker Setup

Welcome to the DB Docker Setup! This setup provides a seamless environment to manage and interact with your databases using Docker. It includes three Docker containers that are essential for database management and development:

## Containers Overview

- **Portainer**: A lightweight management UI that allows you to easily manage your Docker environments. It provides a visual interface to monitor and control your Docker containers.
- **PostgreSQL**: A powerful, open-source object-relational database system. It is widely used for storing and managing structured data.
- **PGAdmin**: A popular, feature-rich management tool for PostgreSQL. It offers a graphical interface to interact with your PostgreSQL databases, making database management simpler.

## Installation

To get started with this setup, you'll need to have Docker and Docker Compose installed on your environment. Follow the steps below to set up the containers:

### Step 1: Install Docker

If Docker is not already installed on your system, you can follow the official [Docker installation guide](https://docs.docker.com/get-docker/) to install it.

### Step 2: Install Docker Compose

Docker Compose is a tool that allows you to define and manage multi-container Docker applications. To install Docker Compose, follow the instructions in the official [Docker Compose installation guide](https://docs.docker.com/compose/install/).

### Step 3: Run the Docker Compose File

Once Docker and Docker Compose are installed, navigate to the directory containing your `docker-compose.yml` file and run the following command to start the containers:

```bash
docker-compose up -d

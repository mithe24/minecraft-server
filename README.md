# Private PaperMC Server

This project sets up a private **PaperMC Minecraft server** using [itzg/docker-minecraft-server](https://github.com/itzg/docker-minecraft-server).  
It uses **Docker Compose** for easy deployment and management.

---

##  Features
- Runs the latest [PaperMC](https://papermc.io/) build.
- Configurable via environment variables.
- Persistent storage for world data and configs.
- Easy one-command start/stop with Docker Compose.

---

## Requirements
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

---

## Setup

1. **Clone this repository**
   ```bash
   git clone https://github.com/mithe24/minecraft-server.git
   cd minecraft-server
   ```

2. Start the server
    ```bash
    docker compose up -d
    ```

3. Stop the server
    ```bash
    docker compose down
    ```


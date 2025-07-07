## Docker Setup & Launch

### Prerequisites

* [Install Docker Engine](https://docs.docker.com/engine/install/)
* [Install Docker Compose](https://docs.docker.com/compose/install/)

### Configuration

1. Rename the environment file:

   * **Linux/macOS**:

     ```bash
     cp .env.example .env
     ```
   * **Windows (PowerShell)**:

     ```powershell
     Copy-Item .env.example .env
     ```

2. Edit `.env` to set required environment variables. Example values include:

### Launch with Docker Compose

Run the following command from the project root:

```bash
docker compose up --build
```

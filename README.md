## Project architecture
<img width="2406" height="1341" alt="QuantumStockpile Arch" src="https://github.com/user-attachments/assets/36d51ddd-d9fc-4293-861f-b886e16f6c7c" />

## Approximate database schema (history excluded)
<img width="4155" height="3656" alt="QuantumStockpile DB" src="https://github.com/user-attachments/assets/441defa1-eb72-4129-8fc8-7eb539229d62" />

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

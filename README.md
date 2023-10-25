# This repository contains a Docker Compose setup 

Docker compose will launches Jupyter Notebook, PostgreSQL, and pgAdmin services.
A demo Jupyter Notebook is provided to help you get started.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
```

1. Navigate to the repository:

```bash
cd your-repo
```

1. Start the services using Docker Compose:

```bash
docker-compose up
```

## Accessing the Services

Each service can be accessed through their respective URLs:

- Jupyter Notebook: `http://localhost:8888`
- pgAdmin: `http://localhost:5050`

## Initial Jupyter Notebook Setup

Follow the steps below:

1. Open your browser and go to `http://localhost:8888`.
2. Input `root` when prompted for a token.
3. Locate and open the demo notebook named `demo.ipynb`.

## General Information

The services are available at the following ports:

- Jupyter Notebook: `8888` and `8000`
- PostgreSQL: `5432`
- pgAdmin: `5050`

## Persistence Information

The data is stored in the `data` directory of this repository:

- Jupyter Notebook Data: `./data/jupyter`
- PostgreSQL Data: `./data/postgres`
- pgAdmin Data: `./data/pgadmin`
# python-postgres-demo

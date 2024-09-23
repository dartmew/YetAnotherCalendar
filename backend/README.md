# CalendarIT
Project template for [BlackSheep](https://github.com/Neoteroi/BlackSheep)
web framework to start Web APIs.

## Getting started

1. Install [poetry](https://python-poetry.org/docs/#installing-with-the-official-installer)
2. install dependencies
3. run the application

### For Linux and Mac

```bash
curl -sSL https://install.python-poetry.org | python3 -

poetry install

poetry run python dev.py
```

### Running with Docker Compose

```bash
docker compose up -d
```

If code was changed, rebuild images:

```bash
docker compose up --build -d
```

### Open [OpenAPI](http://localhost:44777/docs)
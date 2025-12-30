# PokéTrainer

Full-stack application for registering Pokémon trainers with their chosen Pokémon.

## How to set up and run the project

### Prerequisites
- Docker and Docker Compose installed
- Git with submodule support

### Running the Application

1. **Clone the repository with submodules**
```bash
git clone --recursive https://github.com/MarioPeperoni/poketrainer.git
cd poketrainer
```

2. **Run docker compose**
```bash
docker-compose up --build
```

This will start:
- **Frontend** at http://localhost:3000
- **Backend API** at http://localhost:8080
- **API Documentation** at http://localhost:8080/scalar/v1

3. **Stop the application**
```bash
docker-compose down
```

## Project Structure

```
poketrainer/
├── poketrainer-client/     # Next.js frontend (submodule)
├── Poketrainer-API/        # ASP.NET Core backend (submodule)
├── docker-compose.yml      # Docker orchestration
└── README.md
```

## License

This project is part of a coding assignment.
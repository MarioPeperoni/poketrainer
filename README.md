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
- **Backend API** at http://localhost:5017
- **API Documentation** at http://localhost:5017/scalar/v1

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

##  Development Setup

### Frontend Development
See [poketrainer-client/README.md](poketrainer-client/README.md)

### Backend Development
See [Poketrainer-API/README.md](Poketrainer-API/README.md)

## License

This project is part of a coding assignment.
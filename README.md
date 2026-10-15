# Gestor de Tareas Contenerizado
## Integrantes
- Gemima Cerpa
- Melany Tesillo
- Emily Monterrosa

## Servicios
| Servicio | Tecnología | Función |
|---|---|---|
| frontend | nginx | Página web, puerto 8080 |
| api | Python 3.12 + Flask | API de tareas |
| bd | MySQL 8.4 | Base de datos con volumen |

## Requisitos
- Docker Desktop abierto (Engine running)
- Git

## Cómo ejecutarlo
```
git clone https://github.com/emilymontec/app-respaldo
```
```
cd app-respaldo
```
```
Copy-Item .env.example .env
```
```
docker compose up -d --build
```

Abrir http://localhost:8080

## Cómo detenerlo
```
docker compose down
```

# project
php devolper test
# Recipes API
## Setup
1. Clone repository
2. Run `docker-compose up -d`
3. Run `docker exec -it php composer install`
4. Access API at http://localhost:8080

## Endpoints
- GET /recipes - List all recipes
- POST /recipes - Create recipe (protected)
- GET /recipes/{id} - Get recipe
- PUT /recipes/{id} - Update recipe (protected)
- DELETE /recipes/{id} - Delete recipe (protected)
- POST /recipes/{id}/rating - Rate recipe
- GET /recipes/search?q={query} - Search recipes

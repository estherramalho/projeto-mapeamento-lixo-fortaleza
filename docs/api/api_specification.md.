# Especificação de APIs

## Endpoints
- POST /api/reports: Enviar report (com autenticação).
  - Parâmetros: descrição (string), lat (float), long (float), foto (file).
  - Resposta: { "id": int, "status": "pendente" } (201 Created).
- GET /api/reports: Listar reports (somente admin, autenticado).
  - Parâmetros: ?status=pendente (opcional).
  - Resposta: [{ "id": int, "localização": { "lat": float, "long": float }, "status": string }, ...] (200 OK).

## Autenticação
- Usar token JWT no header Authorization.

## Exemplo
- POST: curl -X POST https://api.example.com/api/reports -H "Authorization: Bearer token" -d '{"descrição":"Lixo na rua", "lat":-3.717, "long":-38.543}'

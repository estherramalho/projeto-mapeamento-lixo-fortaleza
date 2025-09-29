# Especificação de APIs

## Endpoints
- POST /api/reports: Enviar report (com autenticação).
  - Parâmetros: descrição, lat, long, foto.
  - Resposta: ID do report.
- GET /api/reports: Listar reports (para admin).

## Autenticação
- Usar token JWT.

## Exemplo
- Chamada POST com dados de lixo.

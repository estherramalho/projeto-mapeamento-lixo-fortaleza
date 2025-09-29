# Modelo de Banco de Dados

## Entidades
- User: id, email, senha, role (cidadão/admin).
- Report: id, user_id, localização (lat/long), foto_url, status, data_criacao.

## Relacionamentos
- User 1:N Report (um usuário pode criar múltiplos reports).

## Diagrama ER
![Diagrama ER] diagrama_er.png (1).png)

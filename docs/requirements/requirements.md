# Requisitos

## Requisitos Funcionais
- RF01: Usuário realiza cadastro e login com email e senha.
- RF02: Usuário reporta ponto de lixo com geolocalização, foto e descrição.
- RF03: Admin visualiza reports em mapa interativo e atualiza status.
- RF04: Sistema gera relatórios mensais de pontos resolvidos.

## Requisitos Não-Funcionais
- RNF01: Tempo de resposta inferior a 2 segundos.
- RNF02: Suporte a até 1.000 usuários simultâneos.
- RNF03: Interface acessível conforme WCAG 2.1.

## Regras de Negócio
- Reports requerem aprovação do admin antes de publicação.
- Notificações push para atualizações de status.

## Histórias de Usuário
- Como cidadão, quero reportar lixo para promover limpeza urbana.
- Como admin, quero gerenciar e priorizar reports.

## Perfis de Usuários
- Cidadão: Acesso para reportar e ver próprios reports.
- Admin: Acesso total para gestão e geração de relatórios.

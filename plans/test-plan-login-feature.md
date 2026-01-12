# Plano de Teste — Funcionalidade de Login

## 1. Objetivo
Validar que o processo de autenticação funciona corretamente, com segurança e boa experiência do usuário.

## 2. Escopo
**Inclui**
- Login com credenciais válidas
- Mensagens de erro para credenciais inválidas
- Bloqueio/limite de tentativas (se aplicável)
- “Esqueci minha senha” (se aplicável)
- Sessão e logout básico

**Não inclui**
- Testes de carga/performance (fora do escopo deste plano)
- Testes de segurança avançados (pentest)

## 3. Riscos e Prioridades
| Risco | Impacto | Probabilidade | Prioridade |
|------|---------|---------------|-----------|
| Usuário não consegue logar com credenciais válidas | Alto | Médio | P0 |
| Mensagem de erro confusa ou sem orientação | Médio | Alto | P1 |
| Sessão expira de forma incorreta | Médio | Médio | P1 |

## 4. Tipos de Teste
- Funcional
- Exploratório
- Regressão

## 5. Ambiente
- Navegadores: Chrome / Edge
- Dispositivo: Desktop
- Massa de dados: 1 usuário ativo, 1 usuário bloqueado, 1 usuário inexistente

## 6. Critérios de Entrada
- Build publicado em ambiente de testes
- Requisitos definidos (ou critérios de aceite)

## 7. Critérios de Saída
- P0 sem falhas abertas
- Evidências anexadas nos cenários principais

## 8. Evidências
- Prints de mensagens e fluxos críticos
- Registro de bugs (ID/Link)

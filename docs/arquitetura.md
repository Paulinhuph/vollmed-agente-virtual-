# Arquitetura do Sistema

- O VollMed foi projetado utilizando uma arquitetura multiagente, onde diferentes agentes possuem responsabilidades bem definidas.

## 🔹 Fluxo Geral
Usuário
  ↓
Agente Orquestrador
  ↓
  ├── Base de conhecimento da Clínica
  └── Gerenciador de Consultas
        ├── Marcar consulta
        ├── Confirmar ou cancelar consulta
        ├── Listar consultas
        └── Fluxo de lembrete por e-mail
        
## 🔹 Agente Orquestrador

Responsável por:
- identificar a necessidade do usuário
- encaminhar para o agente correto
- evitar respostas especializadas
  
## 🔹 Separação de responsabilidades

O sistema separa claramente:
- Informação → Base de conhecimento
- Operação → Gerenciador de consultas
- Isso reduz complexidade e melhora a organização do fluxo.

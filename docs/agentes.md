## Agentes do Sistema

### 🧭 Agente Orquestrador

Função:
- Receber o usuário
- Identificar intenção
- Direcionar para especialista
  
Restrições:
- Não resolve tarefas
- Não responde profundamente


### 📚 Base de Conhecimento

Função:
- Responder perguntas sobre a clínica
Fonte:
informacoes-gerais.pdf ([informacoes-gerais.pdf](https://github.com/user-attachments/files/26318799/informacoes-gerais.pdf)

Regras:
- Não usar conhecimento externo
- Não inventar respostas
- Responder apenas com base no documento

  
### 📅 Gerenciador de Consultas

Função:
- Executar operações relacionadas à agenda
Ações permitidas:
- Marcar consulta
- Confirmar ou cancelar
- Listar consultas
  
Regras:
- Não responder fora do escopo
- Informar quando não encontrar consulta



---

# 🏥 VollMed - Agente Virtual para Clínica Médica

  <img         width="488" height="488" alt="image" src="https://github.com/user-attachments/assets/ef974995-467e-4d06-bd99-db12e62eed3e"        />

Sistema multiagente desenvolvido no Microsoft Copilot Studio para automatizar o atendimento e operações de uma clínica médica, incluindo gerenciamento de consultas, respostas institucionais e envio de lembretes por e-mail.

## 📌 Objetivo

O objetivo do projeto é simular um ambiente real de clínica médica, onde um agente virtual atua como recepcionista digital, direcionando o usuário para agentes especializados responsáveis por executar tarefas específicas.

## 🧠 Arquitetura Geral

O sistema é baseado em uma arquitetura multiagente com separação de responsabilidades:

- Um agente orquestrador responsável por entender a intenção do usuário
- Um agente de base de conhecimento para respostas institucionais
- Um agente de gerenciamento de consultas para operações da agenda
- Integração com Excel Online para persistência de dados
- Fluxo de envio de lembretes por e-mail

## ⚙️ Funcionalidades
- Agendamento de consultas
- Confirmação e cancelamento de consultas
- Listagem de consultas
- Respostas sobre a clínica (horários, convênios, etc.)
- Envio de lembretes por e-mail
  
## 🧩 Tecnologias Utilizadas
- Microsoft Copilot Studio
- Excel Online (Business)
- OneDrive
- Automação de fluxo (envio de e-mail)

---
## 📷 Demonstração
<img width="1830" height="887" alt="Captura de Tela (25)" src="https://github.com/user-attachments/assets/89f21913-14e0-494b-bd6c-0dd47e321bde" />

---
<img width="1762" height="752" alt="Captura de Tela (26)" src="https://github.com/user-attachments/assets/44d0da11-979b-4bde-8d88-d51363640c6d" />

---

<img width="1786" height="918" alt="Captura de Tela (27)" src="https://github.com/user-attachments/assets/2120c5d2-5d5b-4b6a-985f-e056ccbfff8c" />

---

<img width="1828" height="979" alt="Captura de Tela (28)" src="https://github.com/user-attachments/assets/438b87df-967d-4a3b-be63-8169d4ac508a" />

---

<img width="1633" height="684" alt="Captura de Tela (29)" src="https://github.com/user-attachments/assets/dcc3c269-0008-4922-b4cc-97e75d522919" />

---

## ⚠️ Limitações
- Este projeto foi desenvolvido como protótipo funcional. Algumas limitações incluem:
- Uso de Excel como base de dados
- Identificação de consultas por e-mail
- Ausência de validações complexas de agenda
- Fluxo de lembrete não automatizado por tempo

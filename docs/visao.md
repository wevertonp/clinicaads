# 📄 Documento de Visão – Sistema de Agendamento Médico

## 🎯 Objetivo
Otimizar o tempo e organizar os agendamentos de consultas médicas em uma clínica, garantindo eficiência no controle de horários, disponibilidade de profissionais e atendimento ao paciente.

---

## 📌 Escopo (Incluído)

- Cadastro de usuários (atendentes, médicos, pacientes)
- Definição de disponibilidade dos médicos
- Cadastro de pacientes
- Agendamento e cancelamento de consultas
- Exibição de mensagens de erro claras (ex: slot ocupado, fora do horário)

---

## ❌ Escopo (Fora)

- Agendamento domiciliar
- Envio de mensagens para médicos
- Funcionalidades de faturamento e convênios
- Prontuário eletrônico
- Relatórios e dashboards avançados

---

## 📐 Regras de Negócio

- **RB001:** Cada consulta ocupa um slot de horário.
- **RB002:** Consultas devem ocorrer dentro da janela de atendimento do profissional.
- Cancelamentos liberam o slot imediatamente.
- Duração padrão da consulta: **3 minutos**.

---

## 📎 Premissas

- Horário comercial base: **08h às 18h** (ajustável por profissional).
- MVP sem limitações de usuários, pacientes ou consultas.

---

## 👥 Stakeholders

- Atendentes
- Médicos
- Pacientes
- Gestor da clínica

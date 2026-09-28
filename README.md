# 🚲 CashBike — Recompensas e Mobilidade Sustentável

> **Pedale. Acumule pontos. Conquiste benefícios.**  
> Plataforma de gamificação voltada para incentivar o uso da bicicleta como meio de transporte e atividade física por meio de recompensas reais.

---

<p align="center">
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-ativo-orange?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/API-REST%20%2F%20OpenAPI-009688?style=for-the-badge" alt="API" />
  <img src="https://img.shields.io/badge/Database-SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Foco-Sustentabilidade%20%26%20ESG-2E7D32?style=for-the-badge" alt="Sustentabilidade" />
</p>

---

## 🎯 Proposta de Valor & Objetivos

O **CashBike** conecta ciclistas e estabelecimentos comerciais parceiros. Quanto mais o usuário pedala, mais pontos ele acumula, podendo resgatá-los por descontos e vantagens exclusivas, promovendo:

- 🚲 **Mobilidade Sustentável:** Incentivo ao deslocamento não poluente.
- 💚 **Redução de Emissões:** Contribuição direta para a descarbonização urbana.
- 🏃 **Saúde e Bem-estar:** Estímulo à prática constante de atividade física.
- 💰 **Economia para o Usuário:** Descontos e benefícios no comércio local.
- 🤝 **Fortalecimento de Parceiros:** Visibilidade e fidelização para estabelecimentos cadastrados.

---

## ⚙️ Fluxo da Aplicação

```mermaid
flowchart TD
    A[🚴 Usuário Cadastrado] --> B[Registra a Pedalada]
    B --> C[Coleta de Dados: Distância / Duração]
    C --> D[Motor de Regras: Cálculo de Pontos]
    D --> E[Pontos Creditados na Carteira Digital]
    E --> F{Resgate de Benefícios}
    F -->|Descontos| G[Lojas e Serviços Parceiros]
    F -->|Metas e Desafios| H[Recompensas Especiais]

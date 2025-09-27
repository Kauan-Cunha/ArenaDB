# 🏟️ ArenaDB

**ArenaDB** é um banco de dados relacional projetado para armazenar e organizar **estatísticas completas do universo do futebol**.  

---

## 📌 Escopo do Projeto

O modelo contempla diferentes dimensões do futebol, permitindo análises ricas e detalhadas:

- 👤 **Jogadores**  
  - Nome, idade, altura, nacionalidade, posição, peso, pé dominante  
  - Estatísticas: gols, assistências, passes certos, número de jogos  

- 🏆 **Times**  
  - Elenco, técnico, títulos conquistados  
  - Rivalidades e alianças entre clubes  

- 🎉 **Torcida**  
  - Informações sobre torcedores e associações com clubes  

- 🏟️ **Estádios**  
  - Nome, capacidade, localização, data de inauguração  

- 📅 **Partidas**  
  - Mandante, visitante, placar final, data, horário  
  - Estatísticas detalhadas de desempenho  

- 💰 **Patrocínios e Contratos**  
  - Empresas (CNPJ, patrimônio)  
  - Valores, duração, associações com clubes e atletas  

- 🏅 **Campeonatos**  
  - Temporadas, edições, divisões, títulos conquistados  

- 🌍 **Localização**  
  - Cidade, bairro, CEP, sub-região, país  

---

## 📐 Modelo Entidade-Relacionamento (ER)

O modelo ER define as principais entidades e relacionamentos, como:  
**Patrocina, Assina, Possui, Realiza, Rivaliza com, Alia com, Torce para, Campeão de**.  

📄 Confira o diagrama completo em [`DiagramaER.pdf`](DiagramaER.pdf).  

---

## 🎯 Objetivo

O **ArenaDB** serve como base para:  

- 🔎 Pesquisas acadêmicas sobre futebol  
- 💻 Desenvolvimento de sistemas e aplicativos esportivos  
- 📊 Análises estatísticas avançadas  
- 📈 Visualizações e dashboards interativos  

---

## 🚀 Tecnologias

- Banco de dados: *PostgreSQL*  
- Linguagem de modelagem: **SQL / ER**  
- Ferramenta de diagramas: **Draw.io**  

---

## 🛠️ Como Usar

1. Clone o repositório:  
   ```bash
   git clone https://github.com/SEU_USUARIO/ArenaDB.git
   cd ArenaDB

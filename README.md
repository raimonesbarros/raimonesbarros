<img align="right" width="150" alt="Raimones Barros" src="https://user-images.githubusercontent.com/104095836/214920922-ddaa4182-6a41-48bd-82a3-0f6171fa5d15.png"/>

# Raimones Barros

**Desenvolvedor Full Stack** • Tocantins, Brasil 🇧🇷
Integrações de sistemas e customizações de ERP na **Kothe SA**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raimones-barros)
[![Portfólio](https://img.shields.io/badge/raimones.dev-000000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.raimones.dev/)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:raimonesrsb@gmail.com)

---

## O que eu faço

Construo e mantenho **integrações entre sistemas** — o encanamento que faz o ERP conversar
com clientes, parceiros e bancos sem intervenção manual.

- **Integrações & APIs** — troca de dados entre ERP, clientes e parceiros; consumo e exposição de serviços REST/SOAP.
- **Backend** — regras de negócio em Java (Spring Boot) e rotinas em Oracle PL/SQL.
- **Automação financeira** — rotinas de pagamento, baixa e conciliação, com foco em precisão de cálculo e rastreabilidade.
- **Servidores MCP** — ferramentas que dão a agentes de IA acesso controlado e auditável aos dados do ERP, com trava de somente-leitura e mascaramento de dado pessoal.
- **Frontend** — telas e painéis em React/TypeScript para apoiar as rotinas de negócio.

> 🎯 **Disponível para trabalho remoto** — aberto a colaborações, projetos e parcerias.

<details>
<summary><b>🇺🇸 In English</b></summary>

<br>

Full Stack developer based in Tocantins, Brazil. I build and maintain **system integrations** —
the plumbing that lets an ERP talk to customers, partners and banks without manual work.
Day to day: Java/Spring Boot services, Oracle PL/SQL routines, REST/SOAP integrations,
**MCP servers** that give AI agents audited read-only access to ERP data, and
React/TypeScript interfaces. **Open to remote work** and new collaborations.

</details>

---

## 🛠️ Tecnologias

**Backend**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)

**Frontend**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

**Dados**
![Oracle](https://img.shields.io/badge/Oracle%20PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**IA & Agentes**
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)

**Ferramentas**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

📚 **Estudando agora:** arquitetura de integrações, IA & Agents, Oracle PL/SQL avançado e Docker.

---

## 📌 Projetos em destaque

| Projeto                                    | O que resolve                                                                                                                                                                                                                                                                                                              | Stack                               |
| ------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------- |
| **KTHDataBridge** 🔒 <br> _código fechado_ | Servidor **MCP** que dá a agentes de IA acesso **auditado e somente-leitura** ao banco do ERP Sankhya: fonte de views, packages e triggers, mapa de dependências (_o que quebra ao mexer_) e `SELECT` com bind, teto de linhas e mascaramento de dado pessoal. 12 ferramentas; as de escrita exigem confirmação explícita. | `TypeScript` `MCP` `Java` `Oracle`  |
| **KTHBanco** 🔒 <br> _código fechado_      | Conecta o ERP **Sankhya** à API de **Pagamentos do Banco do Brasil**. Envia lotes de transferências, boletos, guias e Pix a partir do contas a pagar, consulta situação de pagamentos e executa a **baixa financeira automática**. Elimina a digitação manual de pagamentos no internet banking.                           | `Java` `API REST` `OAuth2` `Oracle` |
| **KotheLog** 🔒 <br> _código fechado_      | **Portal web** de logística e armazenagem: agendamento de cargas, rastreamento de veículos, estoque, movimentações, devoluções e dashboards operacionais.                                                                                                                                                                  | `React` `TypeScript` `Redux`        |

---

## ⚙️ Como eu trabalho

Meu trabalho roda perto de dinheiro, estoque e dado pessoal. Isso molda como eu escrevo código:

- **Nada crítico executa duas vezes.** Rotinas de pagamento e baixa são protegidas contra
  execução concorrente — se um processamento ainda está em andamento, a chamada seguinte é
  recusada em vez de duplicar lançamento.
- **Escrita é sempre explícita.** Em ferramentas que um agente ou uma automação opera, o
  padrão é somente-leitura; toda operação que grava exige confirmação deliberada e fica
  separada do resto por design.
- **Dado pessoal não vaza por descuido.** Mascaramento na origem da consulta, não na tela.
- **Documento o que foi verificado — e o que não foi.** Prefiro registrar honestamente que
  um caminho ainda não foi exercitado contra o servidor a deixar a dúvida para quem vem depois.
- **Entrego pronto para rodar.** Docker e testes end-to-end fazem parte do projeto, não são
  um extra que fica para depois.

---

<div align="center">
  <i>"Comece a ser, hoje, quem você quer ser no futuro!"</i>
</div>

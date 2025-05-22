===============================
INFRA - TECH CHALLENGE
===============================

Este repositório contém os arquivos de infraestrutura responsáveis por orquestrar todos os microsserviços do sistema de pedidos do Tech Challenge, utilizando Docker e Docker Compose.

-------------------------------
📦 TECNOLOGIAS UTILIZADAS
-------------------------------
- Docker
- Docker Compose
- Java 17 (nos microsserviços)
- PostgreSQL (em cada microsserviço)

-------------------------------
📁 ESTRUTURA DO REPOSITÓRIO
-------------------------------
infra/
├── docker-compose.yml    -> Orquestração de todos os microsserviços
├── .env                  -> Variáveis de ambiente (opcional)
└── README.txt            -> Documentação da infraestrutura

-------------------------------
⚙️ COMO EXECUTAR O SISTEMA
-------------------------------
1. Certifique-se de que o Docker e o Docker Compose estão instalados.
2. No terminal, navegue até a pasta `infra` e execute:

   docker compose up --build

3. Aguarde a inicialização de todos os servi

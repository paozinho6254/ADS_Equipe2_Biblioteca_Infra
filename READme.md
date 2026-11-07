# UniBiblio — Infraestrutura & Orquestração (DevOps)

Repositório responsável por orquestrar a execução local do ambiente completo (Banco de Dados + API + Front-End).

## Como Clonar e Rodar

1. Crie uma pasta raiz (ex: `workspace`) e clone os 3 repositórios dentro dela:
   ```bash
   git clone <URL_DO_REPO_BACK>
   git clone <URL_DO_REPO_FRONT>
   git clone <URL_DESTE_REPO_DEVOPS>
   ```

2. Acesse a pasta deste repositório:
   ```bash
   cd ADS_Equipe2_Biblioteca_DevOps
   ```

3. Suba o ambiente completo:
   ```bash
   docker compose up --build
   ```

## Endereços de Acesso
- **Aplicação Web (Angular):** `http://localhost`
- **API (Spring Boot):** `http://localhost:8080/api`
- **MySQL:** `localhost:3306`
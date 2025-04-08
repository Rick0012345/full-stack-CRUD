# full-stack-CRUD

## Visão Geral
A aplicação full-stack CRUD é um projeto que combina um frontend construído com React e Vite e um backend que ainda não foi detalhado. O objetivo é fornecer uma interface de usuário dinâmica e um backend robusto para operações CRUD (Create, Read, Update, Delete).

## Estrutura do Projeto
A estrutura do projeto é organizada da seguinte forma:
- `frontend/`: Contém o código do frontend.
  - `package.json`: Contém as dependências e scripts para o frontend.
- `backend/`: usando uvicorn e pymysql para estabelecer a ligação com o database

## Frontend
O frontend é uma aplicação React configurada com Vite para um desenvolvimento rápido e eficiente. Aqui estão alguns detalhes importantes:

### Dependências Principais
- `axios`: ^1.8.4
- `react`: ^19.0.0
- `react-dom`: ^19.0.0
- `react-router-dom`: ^7.5.0

### Scripts Disponíveis
- `dev`: Inicia o servidor de desenvolvimento do Vite.
- `build`: Executa a build de produção.
- `lint`: Executa o ESLint para checar problemas de linting.
- `preview`: Inicia o servidor de preview do Vite.

### Configuração do ESLint
A configuração do ESLint inclui plugins para React e regras específicas para garantir a qualidade do código.

### Expansão da Configuração do ESLint
Para aplicações em produção, recomenda-se o uso de TypeScript e regras de linting cientes de tipos.

## Backend
(Dados não disponíveis. Por favor, forneça detalhes do backend para completar esta seção.)

## Instruções de Uso
### Desenvolvimento Local
1. Clone o repositório:
   ```bash
   git clone https://github.com/Rick0012345/full-stack-CRUD.git
   ```
2. Navegue até o diretório do frontend e instale as dependências:
   ```bash
   cd frontend
   npm install
   ```
3. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

### Build de Produção
Para criar uma build de produção, execute:
```bash
npm run build
```

### Preview da Build
Para visualizar a build de produção, execute:
```bash
npm run preview
```

## Contribuindo
Por favor, abra um pull request ou crie uma issue para sugerir melhorias ou reportar problemas.

## Licença
Este projeto é licenciado sob a [MIT License](LICENSE).

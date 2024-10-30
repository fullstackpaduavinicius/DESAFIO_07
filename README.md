Desafio: Testes de Integração para API com TypeScript e Jest
Descrição
Este projeto consiste na migração de uma API de JavaScript para TypeScript e na implementação de testes de integração robustos com Jest. O objetivo é tornar a API mais estável e escalável, reduzindo a possibilidade de erros e aprimorando o desempenho.

A aplicação faz parte de uma iniciativa da equipe de desenvolvimento da Escola DNC, que busca resolver problemas de estabilidade e alta demanda enfrentados por um projeto web de grande escala.

Etapas do Projeto
Etapa 1: Migração para TypeScript
Instalação do TypeScript:


npm install -g typescript
Configuração do TypeScript: Utilize o comando tsc --init para criar o arquivo tsconfig.json e configurar as opções do TypeScript.

Migração Gradual: Converta o código JavaScript para TypeScript, adicionando tipos para variáveis, funções e objetos. Garanta que a funcionalidade original da API seja mantida.

Etapa 2: Configuração do Jest
Instalação do Jest:


npm install --save-dev jest @types/jest
Configuração do Jest: Crie o arquivo jest.config.js e defina as configurações para o ambiente de teste.

Etapa 3: Testes de Integração
Estrutura de Diretórios: Organize os testes em uma estrutura clara e consistente. Separe-os por módulo ou funcionalidade.

Foco nos Testes de Integração: Implemente testes de integração para cobrir as principais funcionalidades, incluindo chamadas de API e interações com o banco de dados.

Cobertura de Cenários: Garanta que os testes verifiquem diferentes cenários, incluindo entradas válidas e inválidas.

Etapa 4: Criação e Organização do Repositório
API Base: Utilize a API em JavaScript fornecida para a migração. Caso necessário, crie seu próprio repositório e documente essa escolha.
Como Configurar o Projeto
Clone este repositório e acesse a pasta do projeto:


git clone <URL-do-repositório>
cd <nome-da-pasta>
Instale as dependências:


npm install
Compile o TypeScript:


tsc
Como Executar os Testes
Para rodar todos os testes de integração:


npm test
Para ver o relatório de cobertura:


jest --coverage
Critérios de Avaliação
Os principais critérios de avaliação do desafio incluem:

Migração correta para TypeScript.
Configuração adequada do ambiente de testes com Jest.
Implementação de testes de integração para as principais funcionalidades.
Qualidade e organização do código.
Clareza e completude do README.
Documentação e Recursos
Documentação do TypeScript
Documentação do Jest

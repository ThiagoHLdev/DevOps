# Jenkins Pipeline para Testes API e Web

Este projeto contém exemplos de pipelines Jenkins para automação dos testes de API (Cypress) e Web.

## Estrutura do projeto

- `api-project/` : Exemplo de projeto API com Jenkinsfile e package.json para testes Cypress
- `web-project/` : Exemplo genérico para projeto Web com Jenkinsfile e package.json

## Jenkinsfile para API (Cypress)

- Clona o repositório
- Instala dependências
- Executa testes Cypress
- Arquiva resultados (junit, screenshots, vídeos)

## Jenkinsfile para Web (exemplo genérico)

- Clona o repositório
- Instala dependências
- Executa testes (npm test)
- Arquiva relatórios JUnit

## Como usar

1. Configure seus jobs no Jenkins apontando para os repositórios dos seus projetos reais.
2. Coloque os Jenkinsfiles no repositório raiz de cada projeto.
3. Certifique-se que o agente Jenkins tenha Node.js e npm instalados.
4. Execute os jobs e verifique os relatórios.

## Personalização

- Ajuste os comandos de teste conforme o framework que estiver usando.
- Configure caminhos dos relatórios junit conforme a estrutura do seu projeto.
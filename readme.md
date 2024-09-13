# Projeto: Automação de Versões com Git Tags

Este projeto utiliza o Git e o npm para automatizar a criação de versões utilizando tags de versão (`major`, `minor`, `patch`). Cada script gerencia o incremento da versão e automaticamente faz o push para o repositório remoto.

## Pré-requisitos

Antes de iniciar, certifique-se de ter as seguintes ferramentas instaladas:

- [Node.js](https://nodejs.org/) (inclui o npm)
- [Git](https://git-scm.com/)

## Instalação

1. Clone o repositório e acesse o diretório do projeto:

   ```bash
   git clone <URL-DO-SEU-REPOSITORIO>
   cd <NOME-DO-SEU-PROJETO>
   ```

## Como Utilizar

Para incrementar a versão do projeto automaticamente, você pode utilizar os seguintes scripts disponíveis no package.json. Eles atualizam o número da versão, criam uma nova tag Git e fazem push da versão para o repositório remoto.

1. Incrementar uma versão patch
Use quando fizer pequenas correções de bugs ou melhorias que não adicionam novas funcionalidades:

npm run version:patch

2. Incrementar uma versão minor
Use quando adicionar novas funcionalidades ou melhorias que não quebrem a compatibilidade com versões anteriores:

npm run version:minor

3. Incrementar uma versão major
Use quando fizer mudanças que quebrem a compatibilidade com versões anteriores ou introduzir grandes alterações no projeto:

npm run version:major

## Contribuindo

- Faça um fork do projeto.
- Crie uma branch para sua feature ou correção (git checkout -b minha-feature).
- Faça commit das suas alterações (git commit -m 'Minha nova feature').
- Faça push para a branch (git push origin minha-feature).
- Abra um Pull Request.

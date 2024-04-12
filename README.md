# Projeto de Card Estilizado com TailwindCSS

🎨 Um projeto simples de card estilizado criado usando a biblioteca de estilos TailwindCSS e Jquery.

## Visão Geral

Este projeto é um exemplo simples de como criar um componente de card estilizado usando o TailwindCSS. O card inclui um cabeçalho com uma imagem, um título e uma breve descrição.

## Funcionalidades

- Layout responsivo para diferentes tamanhos de tela;

## Pré-requisitos

Antes de começar, você precisará ter somente o NodeJS (v10 ou superior).

## Instalação

Primeiro consulte se o `node` já está instalando usando o comando no terminal (para windows) `node -v` ou `node --version`. O mesmo segue para o npm. A documentação oficial é de fácil acesso e está disponível através do [link](https://tailwindcss.com/docs/installation).

Para instalar as dependências do projeto, execute o seguinte comando:
`npm install`

> **Versões utilizadas**
>
> - npm 9.5.1
> - node v18.16.0

## Execução

Para executar o projeto localmente primeiro faça a instalação das das dependências. Feito a instalação do tailwindcss você poderá fazer alterações, mas será necessário digitar no `bash` o seguinte comando:
> `npx tailwindcss -i ./dist/input.css -o ./dist/output.css -w
`   

O mesmo comando está no arquivo `setup.txt` contido no diretório docs/.
## Personalização

Para personalizar o card, você pode editar o arquivo `tailwind.config.js` que fica na raiz do projeto. Caso use o visua studio code, assim como eu, ao fazer alguma modificação nesse arquivo é necessário gerar um novo arquivo `./dist/output.css`. Para isso execute o comando no terminal disponível no diretório `./docs.setup.txt`.

## Contribuição

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar uma solicitação de **pull request**.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](https://mit-license.org/) para obter detalhes.

## Em produção

Este projeto está em produção.

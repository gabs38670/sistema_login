# Sistema de Login
Repositório faz uma simples aplicação de login desencolvida com Node.js em conjunto com banco de dados MySQl. para o front-end utilizamos o framework Bootstrap.

## Funcionalidades
 - Tela de login
 - Tela de registro

 ## Tecnologias
- [Node.js](https://nodejs.org/en/)
- [MySQL](https://www.mysql.com/)
- [Bootstrap](https://getbootstrap.com/)
- [jQuery](https://jquery.com/)
- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)


## Como usar
1. Clone este repositório para o seu computador: git clone
2. Navegue até o diretório do projeto: cd sistema_login
3. Abar o Visual Studio Coode e acesse o projeto
4. Acesse o terminal e digite: npm upgrade
5. Com o MySQL crie um banco de dados chamado dblogin, conforme abaixo:

```
CREATE DATABASE dblogin;

use dblogin;

CREATE TABLE users(
    id INTEREGER PRIMARY KEY AUTO_INCREMENT,
    username VARCHAR (100) NOT NULL,
    email VARCHAR (100) NOT NULL,
    idade INTEREGER NOT NULL,
    pass INTEREGER NOT NULL
);
```
6. Inicie a aplicação com Node.js

## Contribuição
1. Faça um fork deste repositório.
2. Crie uma branch para a sua contribuição: git checkout -b minha-contribuição
3. Faça as alterações desejadas e commit: git commit -m "Minha contribuição"
4. Envie al alterações para o seu repositório fork> git push origin minha-contribuição
5. Abra um pull request neste repositório

## Suporte
Se você tiver alguma dúvida ou sugestão para melhorar este proeto educacional, sinta-se á vontapa para entrar em contato conosco enviando um e-mail para rodolofo.
gsilva2@senacsp.edu.br

--------------
Este projeto é destinado apenas para fins educacionais e não está disponivel para venda. Espero que este projeto ajude no aprendizado em sistema de login. Sinta-se á vontade para personalizar e adaptar este projetto para suas necessidades educacionais.

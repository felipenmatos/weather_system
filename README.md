# Weather System

![project4](https://user-images.githubusercontent.com/82072640/206579047-3d327726-adc9-4614-ae62-01bd993a7bd7.jpg)

# Introdução:

O projeto consiste em um desenvolvimento do aplicativo Web e Mobile CLIMATEMPO, onde é possível efetuar o login e pesquisar o clima em determinada região, com regra de autocomplete e renderização de cards com detalhamento do tempo por data. O projeto em si tem como baixa/média escalabilidade no qual foi adaptado a algumas práticas de Clean Code para otimizar o resultado.

# Deploy do Projeto Front: https://meteorology-app.netlify.app/

# Deploy da API : https://api-weather-search.herokuapp.com/locales

# Inicialização do Projeto:

Para inicializar o projeto baixado pelo Github, primeiro deve executar no terminal o npm install e em seguida executar npm start ou pelo Docker criando a imagem.

# Desenvolvimento:

O projeto teve como arquitetura de desenvolvimento, React + Typescript, no qual foi implementado os componentes reutilizáveis com tipificação dos seus atributos para manter o padrão do projeto. Foi utilizado como teste dos componentes a biblioteca Storybook para garantir a estilização seguindo o Figma e sua funcionalidade, seria implementado também o teste utilizando Jest, que logo será incluído. A estilização foi criada utilizando o styled-components seguindo o Design System. A api foi desenvolvida em NodeJs, centralizando o banco de dados em um único deploy, fazendo assim o tratamento dos endpoints. No teste de usabilidade, vi que para garantir uma experiência mais fácil teria que reformular alguns padrões, dentre eles a exibição dos cards em carousel, utilizando a lib REACT-SLICK. O autocomplete foi criado com base nos conhecimentos básicos de javascript. As rotas foram autenticadas utilizando o localStorage, sendo necessário o registro na tela de Login. Por fim, foi configurado o Docker na raiz do projeto, como solicitado no teste.

# Imagem da arquitetura desenvolvida no MIRO:
(OBS: A arquitetura backend da imagem é antiga, no qual foi realocado para API externa.)

![architecture](https://user-images.githubusercontent.com/82072640/199833524-b67c925b-0f61-461b-b419-4a9ee48cb37f.jpg)

## Bibliotecas e pacotes utilizados no Projeto:

• NPM
• REACT-ROUTER-DOM
• STYLED-COMPONENTS
• STORYBOOK : https://storybook.js.org/docs/react/get-started/install/
• AXIOS : https://axios-http.com/ptbr/docs/intro
• REACT-SLICK: https://react-slick.neostack.com/

# Protótipo:

![Protótipo](https://user-images.githubusercontent.com/82072640/199833629-33b9afbb-87f6-417f-b7d6-0c76afbd2335.jpg)

O protótipo foi desenvolvido com base no exemplo informado no readme e recriado utilizando o Figma, mantendo um Design System para o projeto.

# Storybook:

![TestCard](https://user-images.githubusercontent.com/82072640/199833789-eddf4165-9755-4b22-a2e1-fa1f7056d672.jpg)

# Docker:

![Docker](https://user-images.githubusercontent.com/82072640/199834314-9a58cbfc-e5fd-47ae-9921-7a901f8bf7db.jpg)

# API:

![image](https://user-images.githubusercontent.com/82072640/200446586-391a1c29-4807-4a75-933d-43bed32b847b.png)

# Usabilidade WEB:

[Web.webm](https://user-images.githubusercontent.com/82072640/199834051-899d1324-5f16-44c3-bbf2-cfb5c83646ad.webm)

# Usabilidade MOBILE:

[mobile.webm](https://user-images.githubusercontent.com/82072640/199834119-88642527-3c20-4a8c-874d-fc129645cb50.webm)

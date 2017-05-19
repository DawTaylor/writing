# PWA de recados

## A situação

Atualmente temos profissionais de suporte para os diversos setores da agência.

Constantemente temos situações em que os profissionais atendem ligações de setor diferente do seu, muitas vezes o setor responsável está impossibilitado de atender aquele chamado naquele momento.

Nessas situações a pessoa que atende a ligação anota nome, empresa, telefone e setor, para que a pessoa receba retorno.

Tudo isso é alimentado em uma planilha do Google Drive.

Geralmente esses chamados são coisas simples e que, geralmente, não necessitam ser geridos por um sistema de tickets.

## O problema

- Os profissionais precisam verificar periodicamente por atualizações nessa planilha.
- Frequentemente informações acabam se perdendo por ter duas pessoas manipulando a planilha simultaneamente.
- Não há um registro confiável de quando a solicitação, de fato, aconteceu e nem de quando ela foi atendida.

## Por que?

Além de resolver os problemas, estudar novas tecnologias e fornecer uma prova de conceito.  
Divulgar de forma simples um guia para que iniciantes nessas tecnologias possam criar um projeto simples do começo ao fim.

## PWA, what!?

PWA, Progressive Web Apps, são aplicações web que utilizam de recursos avançados dos navegadores para oferecer uma experiência rica para seus usuários.

Uma PWA pode se comportar como um aplicativo nativo do sistema operacional. Pode ter acesso off-line, ser atualizada automaticamente, receber notificações PUSH, entre outras vantagens.

[Progressive Web Apps](https://developers.google.com/web/progressive-web-apps/)

## Por que PWA?

Um aplicativo nativo é custoso em termos de desenvolvimento e manutenção. É preciso desenvolver e testar versões distintas para cada plataforma suportada. Além disso, depende de aprovação e publicação em lojas de aplicativos como [Play Store](https://play.google.com/store/apps?hl=pt) e [App Store](https://itunes.apple.com/br/genre/ios/id36?mt=8).

Por outro lado, uma aplicação web é mais simples de se desenvolver e testar, pois é desenvolvida utlizando os padrões adotados para a web. Porém uma aplicação web comum não dispõe de diversos recursos que poderiam ser explorados em aplicativos nativos.

Então entra a PWA, um conjunto de especificações que permite adicionar diversos recursos como acesso off-line, PUSH notifications, aumento do engajamento de usuários e afins.

## Tecnologias

O backend utilizará os recursos de RealTime Database e Hosting do [Firebase](https://firebase.google.com/).  
O front-end será desenvolvido utilizando web-components utilizando a versão 2.0 do [Polymer](https://www.polymer-project.org/).  
O [Gulp](http://gulpjs.com/) será utilizado para automatizar o processo de builds e o [Bower](https://bower.io/) será usado como gerenciador de pacotes.

## Firebase?

Firebase é uma plataforma de desenvolvimento web e mobile recentemente adiquirida pela Google. Entre os serviços disponibilizados estão o [Firebase Reatime Database](https://firebase.google.com/products/database/), [Firebase Hosting](https://firebase.google.com/products/hosting/) e [Firebase Auth](https://firebase.google.com/products/auth/). Uma das maiores vantagens de se utilizar o Firebase é a sua característica serverless, permitindo que o desenvolvedor foque naquilo que é importante, o desenvolvimento.

> ## Firebase Realtime Database
> O Realtime Database é um serviço de banco de dados não relacional que permite que você armazene e sincronize dados no formato JSON entre diversos clientes.

> ## Firebase Hosting
> Serviço que permite hospedar arquivos estáticos sem a necessidade de se configurar servidores, permissões e regras de roteamento.

> ## Firebase Auth
> Oferece métodos de autenticação simples como Facebook, Google e Github, de forma simples e rápida, sem a necessidade de se implementar esses meios de autenticação.


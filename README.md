
## **1º Semestre - Horta Automatizada** :computer: 🌳

*Em 2020-1*

Durante o PI (Projeto Integrador) do 1º semestre tivemos como empresa parceira a FATEC. A Faculdade de Tecnologia de São José dos Campos é uma Faculdade Pública Estadual e todos os cursos oferecidos são gratuitos. Instalada no Parque Tecnológico, oferece cursos de  Análise e Desenvolvimento de Sistemas, Banco de Dados, Desenvolvimento de Software Multiplataforma, Gestão da Produção Industrial, Logística, Manufatura Avançada, Manutenção de Aeronaves e Projetos de Estruturas Aeronáuticas. Possui laboratórios de informática, medidas e máquinas elétricas, metrologia, e outros. Foi criada no dia 2 de março de 2006 conforme o Decreto Nº 50.580 publicado no Diário Oficial.

O Projeto tinha como objetivo utilizar dos conhecimentos adquiridos no curso e propor a busca por novos, com o propósito de integrar e desenvolver a aplicação. Temos como tema: **Automação 4.0** em que o foco consiste na criação de sistemas que se conectassem através de bluetooth, wifi ou outros, afim de gerar uma integração entre um software (app) e hardware (físico).

***Veja abaixo os hardwares utilizados:***

![Imagens](https://github.com/AnafGodoy/Portfolio-API/blob/main/imagens/imagens.PNG)

Dado esse tema, foi discutido o que poderia ser de grande utilidade no dia a dia do cliente além de melhorar sua qualidade de vida e possibilitar uma maior acessibilidade. Então, tomamos a decisão de criar o Aplicativo **Horta Automatizada**. Com ele, o cliente poderia inicar-se no ramo de cultivação do próprio alimento de maneira saúdavel tendo todo material de apoio com os detalhes mais básicos como: Sistema sendo capaz de regar no horário correto de acordo com sua preferência de configuração, mostrar as informações coletada pelos sensores, disponibilizar dicas e informações do plantio. Para seu funcionamento é necessário primeiramente a conexão com o bluetooth. Navegue pelas opções de plantações e escolha "Escolher para plantar", assim, as configurações serão ajustadas automaticamente. No menu Home, atualize para que seja feita a leitura dos sensores. Em configurações, faça sua escolha entre "regar manual" ou "automático".

**Funcionamento do Aplicativo**

![video do app funcionando](https://github.com/AnafGodoy/Portfolio-API/blob/main/gifs/video-funcionamento-do-app.gif)


**Funcionamento da Horta**

![video da horta funcionando](https://github.com/AnafGodoy/Portfolio-API/blob/main/gifs/video%20funcionamento%20da%20horta.gif)


*Para visualizar o repositório no GitHub [clique aqui](https://github.com/AnafGodoy/PI-HortaAutomatizada)*

## **Tecnologias Utilizadas:**
## Software:
•	Kodular para criar o aplicativo que controla a horta

•	Programação da nossa placa microcontroladora (Arduíno) em C++ na IDE própria

## Hardware:
•	Arduíno como microcontrolador

•	Sensores para captar informações do ambiente: DHT22(Temp./Umi. do ar), Módulo de Bluetooth, Sensores de Chuva e Umidade do Solo

•	Mini bomba de água para irrigação

•	Fonte 12v 3A para alimentação do circuito

## Contribuições Pessoais
Neste primeiro projeto fiquei encarregada de buscar todas as informações necessárias para compor o aplicativo, sendo elas sobre o solo, clima, germinação, colheita, irrigação e o principal: Classes de plantio. Também tive contato com o Kodular que permite a criação da lógica através de blocos, facilitando assim o melhor entendimento do processo. Com ele, os dados recebidos pelo usuários faziam com que levasse uma resposta para a porta serial do Arduino, por bluetooth.




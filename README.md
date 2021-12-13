
<h1 align="center"> Trabalho de Graduação </h1>
<p align="center">
Repositório destinado a matéria de "Trabalho de graduação - 1" do 5º semestre do curso de ADS da faculdade de tecnologia de São José dos Campos - FATEC SJC
</p>

<h1 align="center"> Projeto 1: 2019-2 </h1>

### Parceiro Acadêmico
>Fatec Prof. Jessen Vidal 

Tendo como idealizador do projeto o próprio docente responsável pela matéria.
### Visão do Projeto (Equipe)
Tema livre. Os próprios alunos puderam dar sugestões de temas e soluções, contanto que no desenvolvimento do projeto fosse usado como integração alguma placa de prototipagem eletrônica.

__*Tema escolhido para o projeto*__
Criar e apresentar um sistema de maquina automática de venda de alimentos, assim, desenvolvendo uma tela de interação com o cliente onde o mesmo poderia escolher e realizar a compra do produto.
__*Lógica*__
Assim que o produto fosse selecionado, o sistema enviaria um sinal remoto a placa(hardware) onde esta, desativaria o sistema de proteção dos produtos, liberando o acesso ao cliente. Um tempo especifico foi dado para que acontecesse a retirada dos produtos, após o fim do tempo, a máquina retornaria ao seu estado de inicio, desativando o acesso aos produtos.
### Tecnologias adotadas na solução (Equipe)
1. __App inventor__:
A simples aplicação de escolha de produtos foi desenvolvida usando a tecnologia [App inventor](https://appinventor.mit.edu/about-us). E com um simples smartphone simulando o display da vending machine, conseguimos facilmente gerir as telas de navegação para o usuário.
2. __Arduino__:
A decisão de uso do [arduino](https://www.arduino.cc) como placa de integração foi tomada de forma rápida e sucinta, visto sua facilidade de comunicação com softwares, módulos e outros componentes como por exemplo a __placa bluetooth__, responsável por estabelecer a comunicação entre a aplicação e o próprio hardware da maquina, e um __cervo motor__ que também conectada a placa arduino, tinha como tarefa permitir acesso ou não aos produtos, abrindo e fechando a porta da *vending machine*.

__Arquitetura do hardware utilizado__
![circuito](https://user-images.githubusercontent.com/29134051/133176431-4c3d50df-a717-401a-aab3-27e6d598e667.png)
### Contribuições pessoais (Individual)
Durante o desenvolvimento do projeto, contribuí com a criação das telas da aplicação, que por sua vez era responsável por interagir com o cliente mostrando todos os produtos a venda e também os disponíveis para compra.
### Aprendizados Efetivos HS (Individual)
- App Inventor: Desenvolver e automatizar telas: Sei fazer com autonomia
- Metodologia ágil Scrum: Conceitos aprendidos conforme o decorrer do projeto: Sei fazer com autonomia

<h1 align="center"> Projeto 2: 2020-1 </h1>

### Parceiro Acadêmico
> SPC Brasil com a FATEC de São José dos Campos.
### Visão do Projeto (Equipe)
O tema proposto nasceu partir na necessiade de gerar valor dados obtidos através da nova lei do cadastro positivo, que faz com que a enrtrada de pessoas físicas e juridicas seja feita de forma automatica, sem a necessidade de ampla escolha de participação, apenas para remoção do programa.
Assim, a equipe teve a ideia de criar o "Auxílio Emergencial Positivo". Programa que, através de uma leitura dos dados dos participantes o permite, se apto, adquirir o auxilio. Neste caso, O Score do cliente será congelado por 2 meses (60 dias) e os pagamentos desse período não influenciarão no cálculo da pontuação.
- Situações de emergência
  - Catástrofe natural;
  - Doenças graves;
  - Recisão sem justa causa;
  - Pandemia;

#### Sobre o projeto
Foi desenvolvido uma aplicação desktop para que os Assistentes de Atendimento verifiquem a viabilidade de inclusão do consumidor no Auxilio Emergencial Positivo.

### Link do repositório original do projeto
>Acesse o link do repositório origianl do projeto clicando __*[AQUI](https://github.com/marciosousa4/projeto-integrador)*__.

### Tecnologias adotadas na solução (Equipe)
Para que o projeto fosse desenvolvido da melhor maneira possível, a equipe optou por usar a linguagem de programação 1.__[Python](https://github.com/topics/python)__ por ser intuitiva e além disso, obter vários recursos necessários para o projeto tais como a biblioteca de interface gráfica  2.__[Tkinter](https://docs.python.org/3/library/tkinter.html)__ usada para a criação de telas além de 3.__[Pandas](https://pandas.pydata.org/docs/)__ e 4.__[matplotlib](https://matplotlib.org)__ para leitura, raspagem dos dados e criação de gráficos.

### Diagrama de caso de uso
![diagrama](https://raw.githubusercontent.com/marciosousa4/projeto-integrador/master/Sprint%206/Diagrama%20de%20caso%20de%20uso.jpeg)

### Demonstração do sistema
![](https://github.com/marciosousa4/projeto-integrador/raw/master/Sprint%205/RELACIONAMENTO%20sprint%205.gif?raw=true)

### Contribuições pessoais (Individual)

Neste projeto a equipe decidiu usar a metodologia ágil SCRUM, onde atuei DEV.
Durante todo o projeto contribuí com:
 - Leitura e raspagem de todos os dados utilizados ao longo do projeto;
 - Criação das telas da aplicação.
 - Testes
 
### Aprendizados Efetivos HS (Individual)
- Python: Usar da linguagem de programação para manipular dados: Sei fazer com autonomia;
- Tkinter: Criação de telas e módulos para auxiliar a interação com o cliente: Faço com ajuda;
- Pandas: Para leitura e raspagem de dados: Sei fazer com autonomia;
- Matplotlib: Para criação de gráficos: Sei fazer com autonomia;
- Metodologia ágil Scrum: Conceitos aprendidos conforme o decorrer do projeto: Sei fazer com autonomia;

<h1 align="center"> Projeto 3: 2020-2 </h1>

### Parceiro Acadêmico
> Visiona Tecnologia Espacial

### Sobre o Projeto (Equipe)
Foi desenvolvido um sistema GEOFPI(mini ETL)capaz de fazer a leitura, conversão, carregamento e manipulação de arquivos com dados georeferenciados com a intenção de aprimorar a análise de dados, suportar o processamento de grandes volumes de dados do tipo shapefilee e melhorar aplicações focadas na capacidade de gerenciar dados espaciais.
### Demonstração do sistema
![gif](https://github.com/marciosousa4/GEOFPI---Projeto-Integrador/raw/master/Loading%20images/GEOFPI(sprint%204).gif?raw=true)

### Link do repositório original do projeto
>Acesse o link do repositório origianl do projeto clicando __*[AQUI](https://github.com/marciosousa4/GEOFPI---Projeto-Integrador)*__.

### Tecnologias adotadas na solução (Equipe)

- Python: Para desenvolvimento do CRUD usado na aplicação.
- Figma: Modelagem do protótipo.
- ReactJS e Node.js: Desenvolvimento do frontend da aplicação.
- PostgreSQL e PostGis: Para armazenamento e manipulação de arquivos geográficos.
- Servidor Azure: Para deploy do banco de dados utilizado no sistema.

### Contribuições pessoais (Individual)
- Manipulação de todos os arquivos geográficos utilizados ao longo do projeto.
- Criação e manutenção do banco de dados utilizado pelo sistema.
- Desenvolvimento do prototipo.
### Aprendizados Efetivos HS (Individual)
- Desenvolvimento do CRUD usado na aplicação: Sei fazer com autonomia;
- Modelagem do protótipo: Sei fazer com autonomia;
- Desenvolvimento do frontend da aplicação: Sei fazer com ajuda;
- Armazenamento e manipulação de arquivos geográficos: Sei fazer com ajuda;
- Uso do servidor azure para deploy do banco de dados utilizado no sistema: Sei fazer com ajuda;
- Metodologia ágil Scrum: Conceitos aprendidos conforme o decorrer do projeto: Sei fazer com autonomia;

<h1 align="center"> Projeto 4: 2021-1 </h1>

### Parceiro Acadêmico
> IACIT

### Visão do Projeto (Equipe)
Desenvolver uma ferramenta capaz de criar e gerenciar atas de reunião, Focando em requisitos específicos da empresa parceira. Assim, possibilitando principalmente:

- Criar e editar atas de reunião:

- Exportar atas diferentes formatos:
  
- Usabilidade mobile.

A ferraemnta "Mitim" foi desenvolvida para suprir tal demanda. Com o sistema de gerenciamento de atas "Mitim", a tarefa de criar, gerenciar e analisar atas digitais deixou de ser algo complexo. A ferramenta também conta com funcionalidades extras como exportação do documento em PDF e disponibilização de atas para pessoas não necessariamente cadastradas na ferramentas.

### Tecnologias adotadas na solução (Equipe)

- MySQL
  
- ReactJS
  
- Java
  
- CSS

### Contribuições pessoais (Individual)
Atuei no desenvolvimento do backend do projeto como um todo. Fui responsável por criar a lógica das seguintes features:
- Login de usuário:
  
- Cadastro de usuário

- Cadastro de atas

- Impressão de atas

- Relatórios

### Aprendizados Efetivos HS (Individual)

- Desenvolvimento de serviços CRUD utilizando Java: Sei fazer com ajuda;
  
- Desenvolvimento utilizando Java: Sei fazer com ajuda;
  
- Utilização de ORM's com banco relacional: Sei fazer com autonomia;
  
- Metodologia ágil Scrum: Conceitos aprendidos conforme o decorrer do projeto: Sei fazer com autonomia;

<h1 align="center"> Projeto 5: 2021-2 </h1>

### Parceiro Acadêmico
> GSW

### Visão do Projeto (Equipe)

A empresa informou a necessidade de uma extensão de um produto que já existe, que consiste em um portal de anúncio e vendas de imóveis.
A extensão deveria consistir em um marketplace para anúncios e vendas de automóveis. Possibiltando também a negociação do produto dentro do próprio sistema.

Como solução a dor proposta, foi criada a plataforma "ByCar",que consiste em uma aplicação vasta, Web e mobile para anúncio e venda de veículos.
A ferramenta também contem outras funcionalidades tais como:

Cadastro de usuários e anúncios de forma automatizada;
App mobile com todas as funcionalidades presentes na versão web;
Busca pelos anúncios por meio de filtro e palavras-chaves:
### Tecnologias adotadas na solução (Equipe)

- Python
  
- MongoDB
  
- React native
  
- Expo

### Contribuições pessoais (Individual)
Atuei no desenvolvimento do backend do projeto como um todo. Fui responsável por criar a lógica das seguintes features:

- Criação de rotas;
  
- Criação de lógica para leitura de arquivos(.xls, .xlsx);
  
- Criação da lógica de envio de e-mail;
  
- Criação do CRUD de usuário;
  
- Criação do CRUD de anúncio;

### Aprendizados Efetivos HS (Individual)

- Desenvolvimento de serviços CRUD utilizando Python: Sei fazer com autonomia;
  
- Desenvolvimento utilizando Python: Sei fazer com autonomia;
  
- Utilização de ORM's com banco não relacional: Sei fazer com autonomia;
  
- Manipulação de arquivos .xls, .xlsx com python: Sei fazer com autonomia;
  
- Metodologia ágil Scrum: Conceitos aprendidos conforme o decorrer do projeto: Sei fazer com autonomia;

### Informações de contato
[Linkedin](https://www.linkedin.com/in/jodangalas/)

[Github](https://github.com/JodanGalas)
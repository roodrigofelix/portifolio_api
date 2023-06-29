# Aprendizagem por Projetos Integrados 2022-1
![logoraculum](https://user-images.githubusercontent.com/54710426/173154765-663752ba-20ba-476f-bdbb-2e141b32df22.PNG)


### Parceiro Acadêmico
O UOL é uma das empresas pioneiras em produtos de tecnologia e informação no Brasil, com uma trajetória de anos no mercado. Além de seu renomado portal de notícias, o UOL oferece uma ampla gama de serviços que incluem hospedagem, entre outros. A empresa se destaca pela sua presença diversificada no setor de tecnologia e pelo seu papel como referência no fornecimento de informações e soluções para os usuários.
Link:  [uol.com.br](http://www.uol.com.br/index.php).



***

### Visão do Projeto
O objetivo do produto é monitorar uma aplicação desenvolvida pelo time. Ele coleta dados em tempo real, prevê falhas iminentes e alerta o usuário. Isso permite uma atuação proativa e garante maior estabilidade do sistema.

![cadastro_rodando](https://user-images.githubusercontent.com/54710426/173150325-e2f3d64a-22f5-4c42-bc92-eb75bb6e155f.gif)

Imagem 1: Aplicação de cadastro de usuários desenvolvida em Java e em pleno funcionamento.



![grafana_show](https://user-images.githubusercontent.com/54710426/173150370-decd8e77-da58-436d-8fdc-bd9466be310f.gif)
Imagem 2 : Gráficos do Grafana exibindo métricas coletadas do sistema via Prometheus.



![analisesurv](https://user-images.githubusercontent.com/54710426/173150997-04031e53-0fa3-48eb-a9e8-31bb2bd8d345.PNG)

Imagem 3: Processo de análise de sobrevivência sendo efetuado com base nos dados coletados pelo nosso CSV. (Imagem ilustrativa, para página detalhada clique [aqui](https://github.com/Oraculum-Fatec/api-previsao-de-indisponibilidade-sites/blob/main/SurvivalAnalysis.ipynb)



![Slack_message](https://user-images.githubusercontent.com/54710426/173150382-3d062c22-b85d-4a0d-81aa-19c460708d71.png)
Imagem 4: Avisos via canal do Slack alertando queda iminente do sistema até eventual falha.


#### Lista de Requistos 

`Requisitos Funcionais`: 
1. Desenvolver um formulário de cadastro, com os campos: Nome, E-mail, Senha e Celular;
2. Prover uma forma de consulta dos cadastros realizados;
3. Monitorar e coletar dados do uso do cadastro pelos users;
4. Fazer análise de Sobrevivéncia da Aplicação;
5. A partir da análise prever via I.A. falhas iminentes no sistema e alertar os administradores.



`Requisitos não Funcionais`:
1. Desenvolver backend da aplicação formulário utilizando a linguagem java em conjunto do Framework Springboot
2. Tempo de resposta do backend de consulta de cadastros deve ser abaixo de 100ms;
3. Desenvolver o frontend da aplicação formulário utilizando a linguagem JavaScript em conjunto do Framework vue.
4. O tempo de resposta do backend de cadastros deve ser abaixo de 300ms.

***

#### Link do repositório no Github
[Repositório Oracullum](https://github.com/Oraculum-Fatec)


### Tecnologias adotadas na solução

`VueJS` Utilizado no front-end da aplicação de cadastro;

`Java` Utilizado para desenvolvimento do backend da aplicação de cadastro;

`Prometheus` Utilizado para raspagem de dados da aplicação;

`Grafana` Utilizado para transformas as métricas selecionadas em gráficos e como suporte para consumo de informações da I.A.;

`Python` Utilizado conforme método recomendado pelo cliente para desenvolvimento da I.A.;

`MySQL` Banco de dados utilizado para armazenas as informações das aplicações.


### Contribuições Pessoais
Product Owner, tive a oportunidade de desenvolver prazos e estabelecer uma comunicação constante com o cliente. Meu objetivo era entender e atender às demandas e necessidades, buscando soluções que estivessem alinhadas com os requisitos básicos do projeto. Foi uma experiência enriquecedora em termos de gestão e colaboração com o cliente, também ajudei de forma reduzida no desenvolvimento do backend.


### Hard Skills
`Java` Evolução nas práticas de programação, desenvolvimento de uma aplicação CRUD Web completa e integração com o MySQL; Sei fazer com autonomia;

`Python` Melhores práticas de programação, suporte no tratamento dos dados a serem consumidos e ajustes nos cálculos da I.A. e análise de sobevivência (Curva Kaplan Meier); Sei fazer com ajuda;

`Prometheus/ Grafana` Implementei a coleta de métricas em diferentes aplicações, definindo os parâmetros necessários para monitorar a saúde do sistema e visualizando-os através do Grafana; Sei fazer com ajuda.


### Soft Skills
O projeto foi considerado o mais complexo até o momento, mas a comunicação e cooperação contínuas entre os membros da equipe e a empresa parceira tornaram a jornada mais tranquila do que o esperado. Foi uma oportunidade de sair da zona de conforto e desenvolver um produto mais completo, exigindo um pensamento mais elaborado. Essa experiência enriqueceu nossas habilidades interpessoais e reforçou a importância de utilizá-las em seu máximo potencial devido à complexidade do projeto e às demandas do cliente.

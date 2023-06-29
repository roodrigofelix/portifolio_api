# Aprendizagem por Projetos Integrados 2020-2
![Logo](https://user-images.githubusercontent.com/56441534/138449995-c249e266-cdb5-4cdb-a018-45b64c0ae2c3.png)

O desenvolvimento do projeto foi em torno da necessidade da empresa parceira em ter uma ferramenta web que funcionasse como um mini-ETL, tendo como principais operações:
- Extrair dados de um arquivo `shapefile` e envia-los ao banco de dados; e
- Realizar o processo inverso convertendo os dados ingeridos no banco de dados em um novo arquivo `shapefile`.

### Parceiro Acadêmico
Visiona Tecnologia Espacial é uma empresa brasileira especializada em integração de sistemas espaciais. A empresa atua no desenvolvimento e fornecimento de soluções tecnológicas para o setor espacial, abrangendo desde o projeto e fabricação de satélites até o desenvolvimento de sistemas de controle de missão e infraestrutura terrestre.

Link:  [visionaespacial.com.br](https://www.visionaespacial.com.br/).


***

### Visão do Projeto
Neste projeto, a proposta oferecida pelos docentes participantes foi de uma solução Web que atuasse como um ETL (extract, transform, load) focado em arquivos do tipo Shapefile com dados geográficos, que efetuasse de forma simples e rápida o recebimento, tratamento e carregamento dos dados em um banco de dados estruturado pré-definido (PostgreSQL).

<img src="https://user-images.githubusercontent.com/58118956/100612612-05759b00-32f2-11eb-992a-c1380029209a.png" width="700"/>

O Shapeview tem como objetivo funcionar como um mini-ETL, visando suprir a necessidade do cliente o Shapeview realiza a ingestão dos dados contidos em arquivos `Shapefile` de forma personalizada, podendo retirar dados e metadados que não são necessários em seu contexto de negócio.
A ferramenta também permite realizar a extração de dados contidos no banco de dados para um novo arquivo `shapefile`.

#### Lista de Requistos 

`Requisitos Funcionais` requeridos pelo cliente foram:
1. Carga de dados geográficos (ponto, linha e polígono) e seus atributos alfanuméricos em tabelas existentes de banco de dados geográficos; e
2. Recuperação de dados geográficos (ponto, linha e polígono) e seus atributos alfanuméricos armazenados em banco de dados geográficos.

`Requisitos não Funcionais`:
1. Linguagem Java ou python; 
2. Banco de Dados Geográficos PostGIS; e
3. Documentações.

***

#### link do repositório no Github
[Repositório](https://github.com/Mateus-Prestes/ShapeView)


### Tecnologias adotadas na solução

**Python:** Em conjunto da biblioteca **Geopandas** para a análise dos dados geoespaciais e alcance dos indicadores propostos.

**Flask:** Micro framework do python para criação de aplicações web.

**HTML**, **CSS** e **JavaScript:** Para a criação e desenvolvimento do design da Interface do usuário.



### Contribuições Pessoais
Participei no desenvolvimento do backend da aplicação, dando suporte na criação das rotas para manuseio dos arquivos e armazenamento e requisição no banco, bem como pesquisa e uso da ferramenta PostGIS aliada ao PostgreSQL afim de possibilitar a inserção dos arquivos Shapefile.

### Hard Skills
**Python:** Melhora significativa na habilidade, tendo a possibilidade de unir a lógica de recebimento e tratamento de um arquivo em formato completamente diferente de experiências anteriores ao uso de um banco de dados totalmente funcional;

**Flask:** Primeira experiëncia de trabalho em conjunto com um time de frontend, podendo desenvolver conhecimento da biblioteca em questão com a criação de rotas na aplicação a serem usadas pelo front;

**SQL:** Primeiro contato com a tecnologia, permitindo adquirir noções básicas sobre a lógica por trás de um banco estruturado e também a efetuar comandos, podendo manipular dados de diferentes tabelas e organizá-los da forma desejada.

### Soft Skills
Mais uma vez, o projeto nos permitiu transitar entre áreas do mercado nas quais atuaremos futuramente, melhorando significativamente a comunicação interpessoal entre o grupo pela maior complexidade do projeto, bem como responsabilidades e flexibilidade para sobrepor os problemas encontrados durante o desenvolvimento.

 

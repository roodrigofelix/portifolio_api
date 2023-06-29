# Aprendizagem por Projetos Integrados 2021-1
<img src="https://user-images.githubusercontent.com/56441534/142959484-12836894-06f3-4346-91ce-1fb6891da026.png" width="300"/>

A empresa parceira identificou a necessidade de uma ferramenta para gerar Atas de Reunião eficientes e funcionais. Por isso, propôs o tema aos alunos do quarto Semestre de Análise e Desenvolvimento de Sistemas da FATEC São José dos Campos. O objetivo era desenvolver uma solução dinâmica que facilitasse a criação e organização das atas, garantindo sua praticidade e utilidade.
As principais funcionalidades da ferramenta deveriam ser:

- Funcionalidades de cadastro;
- Controle de acesso;
- Logs de execução; 
- Geração e monitoramento de ata de reunião; e 
- Assinatura digital.

### Parceiro Acadêmico
IACIT (Instituto de Aplicações de Computação em Infraestrutura Tecnológica) é uma empresa brasileira fundada em 1986, com expertise tecnológica no desenvolvimento de produtos e sistemas aplicados ao Auxílio e Controle do Tráfego Aéreo e Marítimo (CNS/ATM), Meteorologia Radar, Telemetria, Redes Integradas, Comunicação, Defesa e Segurança Pública. A empresa possui um amplo conhecimento nessas áreas e busca constantemente oferecer soluções inovadoras para atender às demandas de seus clientes.
Link:  [iacit.com.br](https://www.iacit.com.br/).


***

### Visão do Projeto
O projeto tem como objetivo principal oferecer uma solução para o gerenciamento de atas de reuniões no ambiente corporativo. Através do sistema, os usuários poderão criar e organizar atas de forma direta e estruturada, além de monitorá-las. O sistema também garantirá a segurança e privacidade dos usuários, com diferentes níveis de acesso controlados pelo administrador.


#### Lista de Requistos 

`Requisitos Funcionais`:
1. Cadastro de Usuários, Cadastro de Perfil de Acesso, Cadastro de modelo de ata de Reunião.
    - O cadastro de usuário deve conter os seguintes campos: Nome, Título/Cargo,Área/Empresa, E-mail e Telefone;
    - Todo usuário deve ter pelo menos um perfil de acesso;
    - O perfil de acesso define quais funcionalidades o usuário pode acessar, sendo: 
        - Administrador: Acesso total ao sistema;
        - Usuário: Acesso ao cadastro do modelo de ata de reunião, a geração de ata de reunião, ao monitoramento de ata de reunião e à imprimir ata de reunião em PDF e Excel;
        - Gerência: Acesso aos relatórios do sistema, à aprovação do modelo de ata de reunião e a imprimir ata de reunião em PDF e Excel;
        - A aplicação deve ter pelo menos um usuário administrador o qual não pode ser excluído;

2. Login; Logout;
3. Gerar Ata de Reunião;
4. Monitorar Ata de Reunião;
    - Deve ser exibida uma listagem com a situação es todas as atas de reunião. Esta listagem deve possuir filtros: Por Estado, Por Data de Criação da Ata e Por Pauta;
    - A listagem pode ser ordenada de forma crescente e decrescente;
    - Uma Ata de Reunião pode ter os seguintes estados: Nova, Revisada, Assinada e Enviada.

`Requisitos não Funcionais`:
1. Backend: Linguagem Java (sugestão); 
2. Frontend: HTMLS, CSS 3,15, Angular ou React;
3. Ser usual com dispositivos móveis;
4. Estar disponível no idioma Português do Brasil;
5. Manual de usuário com prints de telas e explicação das funcionalidades;
6. Registros de testes de todas as funcionalidades; e
7. Código fonte do sistema documentado.

***

#### Link do repositório no Github
[Repositório](https://github.com/DaviNeves0/EasyATA)


### Tecnologias adotadas na solução

**Java**: Em conjunto do framework `Spring` para criação do sistema web;

**Spring**: Framework java para criação de aplicações web.

**MySQL**: Sistema gerenciador de Banco de Dados Relacional. Utilizado para salvar os cadastros de usuários, seus níveis de acesso e o registro de novas Atas de Reunião, registrando todo o ciclo de vida de uma Ata de Reunião.

**HTML**, **CSS** e **JavaScript**: Criação e desenvolvimento do design da Interface do usuário.

**React**: Uma biblioteca JavaScript para criar interfaces de usuário


### Contribuições Pessoais
No desenvolvimento do projeto, atuei no Backend, sendo responsável pela criação da API utilizando o framework Spring Boot. Além disso, realizei a integração com o banco de dados e defini as permissões e níveis de acesso dos usuários no sistema.

### Hard Skills
- Criação de sistema web utilizando linguagem de programação `Java` e conjunto do Framework `Spring`:
    - Sei fazer com ajuda.
- Integração com banco de dados relacional utilizando ORM com `java` e `Hibernate`:
    - Sei fazer com ajuda.

### Soft Skills
Mantivemos uma estrutura semelhante ao grupo do projeto anterior, o que nos permitiu aprimorar ainda mais nossa comunicação e alinhamento de ideias. Isso facilitou o ritmo de trabalho e nos preparou para lidar com desafios maiores longo do caminho. Fomos obrigados a nos adaptar rapidamente a novas situações e demonstrar flexibilidade em diversos aspectos, tanto nas relações interpessoais quanto em questões relacionadas aos negócios.

 

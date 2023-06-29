# Aprendizagem por Projetos Integrados 2020-1
![metalogo](https://user-images.githubusercontent.com/54710426/143992128-c328db19-8d3d-4540-9356-c94ba34203ac.PNG)

O projeto foi desenvolvido com base na necessidade da nossa empresa parceira de aprimorar a gestão da informação, visando garantir a qualidade dos dados, promover o uso adequado dessas informações e gerar valor por meio delas. Essa necessidade surgiu devido à mudança no modelo de operação do Cadastro Positivo.

### Parceiro Acadêmico
SPC - Brasil: é uma empresa associada à Confederação Nacional de Dirigentes Lojistas (CNDL) e tem como função processar e armazenar todas as operações de crédito efetuadas pelas empresas afiliadas.

Link: [spcbrasil.org.br](https://www.spcbrasil.org.br/).

***

### Visão do Projeto
A proposta do projeto, determinada pelo corpo docente, consistia em desenvolver uma solução que permitisse aos usuários realizar análise de dados presentes em arquivos .CSV e gerar relatórios com indicadores de qualidade sobre os dados e os negócios com base nas informações de movimentações de crédito. A aplicação tinha como objetivo oferecer essas funcionalidades por meio de uma interface gráfica simples, permitindo que os relatórios gerados fossem salvos no diretório local do usuário. Todo o processo seria iniciado a partir de um executável, proporcionando facilidade e acessibilidade aos usuários.

![meta_app](https://user-images.githubusercontent.com/54710426/143992026-1d2d6a81-16cf-4d4e-8011-143ae8552221.png)


#### Lista de Requistos 
Os `Requisitos Funcionais` foram definidos com base nas seguintes métricas de qualidade fornecidas pela empresa parceira:

1. COMPLETUDE:
    - O campo de cadastro do estado referente a um endereço pode estar preenchido ou não, mesmo sendo obrigatório.

2. CONFORMIDADE:
    - Uma vez preenchido, o campo de estado pode seguir ou não as regras de negócio, como formato e tamanho.

3. CONSISTÊNCIA:
    - O campo de estado é compartilhado entre diversas bases de dados. Para um mesmo endereço, é importante que todas as bases tenham o mesmo estado cadastrado.

4. UNICIDADE:
    - Em cada base de dados com informações geoespaciais, é crucial que o mesmo endereço, no mesmo estado, não possua múltiplos registros.

5. ACURÁCIA:
    - Mesmo quando preenchido corretamente (completude) e seguindo o formato adequado (validade), o valor do campo de estado pode não corresponder a nenhum estado existente na federação. Por exemplo, "GG" é uma sigla no formato adequado, mas não representa um estado válido..


Requisitos não Funcionais:
1. A aplicação deve ser desenvolvida para a plataforma Desktop.
2. Deve ser capaz de realizar análise e tratamento de arquivos nos formatos xlsx e csv.

***

#### link do repositório no Github
[Repositório](https://github.com/diegosilva789/Projeto_SPC/tree/master)


### Tecnologias adotadas na solução
**HTML e CSS:** Utilizados para desenvolvimento de interface gráfica simples para o usuário;

**Python:** Utilizado para tratamento dos dados contidos em documentos .csv, efetuando a leitura, validação, correção e armazenamento no diretório local do usuário;

**Jupyter notebook:** Utilizado como ferramenta de desenvolvimento colaborativo para o time de devs, facilitando visuzliação e compartilhamento das atualizações do código de forma dinâmica.

### Funcionamento
**Executando o METAapp:**

![68747470733a2f2f692e696d6775722e636f6d2f534b77587a6d772e676966](https://user-images.githubusercontent.com/54710426/143992966-0c4c90c5-8e23-49ea-8156-73b48e029665.gif)

**Visualização do relatório:**

![68747470733a2f2f692e696d6775722e636f6d2f544776376946552e676966](https://user-images.githubusercontent.com/54710426/143992943-496fa056-c437-4778-9e15-a955d29c1372.gif)



### Contribuições Pessoais
No projeto, minha contribuição incluiu o desenvolvimento do backend, pesquisa e aplicação da biblioteca Pandas e Cx-Freeze para a criação do executável do software, bem como o tratamento do arquivo CSV contendo os dados e a geração posterior dos relatórios.

### Hard Skills

- Minha análise de dados com Python3 de arquivos xlsx e csv me permite trabalhar com autonomia nessa tarefa. Essa foi minha primeira experiência no desenvolvimento completo de uma aplicação, desde o início até o fim, utilizando metodologias ágeis e aplicando lógica para atender às necessidades do cliente, em vez de resolver problemas simples. Durante o projeto, aprendi especificamente sobre as bibliotecas Pandas e cx-freeze, além de utilizar o Jupyter Notebook como uma ferramenta essencial para o desenvolvimento e colaboração da equipe.

**Jupyter Notebook:** ferramenta fundamental no processo de desenvolvimento, permitindo fácil compartilhamento e visualização de informações em tempo real entre a equipe de desenvolvedores.

### Soft Skills

Participar desse projeto proporcionou uma valiosa experiência no relacionamento com o cliente, aprendendo a lidar com suas demandas e expectativas. Além disso, tive a oportunidade de me envolver em metodologias ágeis, em particular o Scrum, e aplicar essas metodologias no desenvolvimento efetivo de uma aplicação, do início ao fim. Isso me permitiu aprender a lidar com um cliente real e utilizar a lógica aplicada para atender às suas necessidades, em vez de apenas resolver problemas simples.

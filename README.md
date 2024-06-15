
<h1 align="center"> Projeto Disciplina: Requisitos de Software </h1>

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

# 1. Introdução

## 1.1.  Nome do Grupo

### Grupo 9 - Alcateia

|<sub>Abner do Nascimento</sub>|<sub>Augusto Thiago</sub>|<sub>Beatriz Lopes</sub>|<sub>Carlos Hereman</sub>|<sub>Letícia Marchioni</sub>|<sub>Luccas Hessel<sub>|<sub>Ana Cecília Santana de Oliveira</sub>
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|<sub>https://github.com/abnerns</sub>|<sub>https://github.com/thiagoatsl</sub>|<sub>https://github.com/beatriz-lopes</sub>|<sub>https://github.com/CarlosHereman</sub>|<sub>https://github.com/lemarchioni</sub>|<sub>https://github.com/LuccasHessel</sub>|<sub>https://github.com/anaceciliaso</sub>|



## 1.2.  Nome do Sistema

<h3 align="center"> 📚 LibraTech 📚 </h3>

 **`Padlet`**: https://padlet.com/augustothiago1/lista-de-tarefas-lumbxjnwhasxdgfc

## 1.3.  Propósito do Sistema

O objetivo da LibraTech é fornecer um registro de livros e documentos de uma biblioteca escolar, possibilitando gerenciar acervos híbridos com disponibilização de status (disponível, alugado ou para consulta), tanto físicos quanto digitais, além da busca especializada por arquivos, cadastro de usuários, catalogação, sistema de avaliações, facilidade para planejamento de aulas e possibilidade de realizar reservas pelo software. Sobretudo, busca otimizar a performance dos funcionários e facilitar a vida dos seus usuários, valorizando praticidade e eficiência.

## 1.2.  Público Alvo

Escolas públicas e particulares do país. 

## 1.3. Descrição dos usuários

### Perfil do Usuário
  
|<sub>PERFIL</sub>|<sub>A</sub>|<sub>B</sub>|
| :---: | :---: | :---: |
|<sub>Função</sub>|<sub>Alunos/Professores</sub>|<sub>Bibliotecários</sub>|
|<sub>Porcentagem de Usuários</sub>|<sub>95%</sub>|<sub>5%</sub>|
|<sub>Faixa Etária</sub>|<sub>[17, 40]</sub>|<sub>[35, 58]</sub>|
|<sub>Gênero</sub>|<sub>20% F, 80% M</sub>|<sub>60% F, 40% M</sub>|
|<sub>Afinidade com a Tecnologia</sub>|<sub>83%</sub>|<sub>70%</sub>|
|<sub>Frequência com que usará o sistema</sub>|<sub>Ocasionalmente</sub>|<sub>Diariamente</sub>|
|<sub>Objetivo ao usar o sistema</sub>|<sub>Encontrar material de estudo</sub>|<sub>Gerenciar os livros da biblioteca</sub>|

***

### Perfis

![Stephanny Smitthens](imagem1.png)

![João da Silva](imagem2.png)

![Sergio Marquina](imagem3.png)

***
  
### Cenário
**Antes**
<p>Stephanny Smitthens é uma bibliotecária recém-contratada que faz uso de um programa institucional pouco intuitivo e
deficiente de recursos úteis, o que vem dificultando o seu trabalho.

Stephanny recepciona o aluno João da Silva que procura pelo livro "Sistemas Operacionais Modernos" do autor Andrew S.
Tanenbaum. Por causa da interface complexa, lentidão e imprecisão do sistema, Stephanny não consegue entregar de imediato o
livro que João requisitava.</p>

**Depois**
<p>Stephanny Smitthens é uma bibliotecária recém-contratada que faz uso do programa LibraTech para a realização de seu trabalho. Tal programa vem auxiliado Stephanny em suas tarefas cotidianas, já que conta com uma interface rápida e intuitiva, sistema com controle integrado, ótimos recursos de busca e atualização do estoque automática, além da opção de reservar um determinado livro.

Stephanny recepciona o aluno João da Silva, que solicitou pelo livro "Sistemas Operacionais Modernos" do autor Andrew S. Tanenbaum utilizando a plataforma online. Por causa desse excelente sistema, Stephanny consegue atender à requisição de João velozmente e de maneira assertiva, tendo previamente avaliado o catálogo e reservado o livro procurado.</p>


# 2. Documentos gerais no repositório

## 2.1. Requisitos

|ID|Requisitos Funcionais|Prioridades|
|:---:|:---:|:---:|
|<sub>RF01</sub>|<sub>O sistema deve permitir que o bibliotecário cadastre usuários no sistema, como estudantes e professores, e monitore seus perfis.</sub>|<sub>ALTA</sub>|
|<sub>RF02</sub>|<sub>O sistema deve registrar a disponibilidade de um livro e permitir que um usuário consulte-a.</sub>|<sub>ALTA</sub>|
|<sub>RF03</sub>|<sub>O sistema deve manter um registro de todas as transações de empréstimo e devolução.</sub>|<sub>ALTA</sub>|
|<sub>RF04</sub>|<sub>O sistema deve conter um catálogo de todos os livros na biblioteca, junto com uma breve descrição de cada.</sub>|<sub>ALTA</sub>|
|<sub>RF05</sub>|<sub>O sistema deve ter um chat para tirar dúvidas sobre seu uso, disponível em todas as páginas e sempre acessível.</sub>|<sub>BAIXA</sub>|
|<sub>RF06</sub>|<sub>O sistema deve separar os livros e documentos físicos em seções de acordo com suas categorias.</sub>|<sub>BAIXA</sub>|
|<sub>RF07</sub>|<sub>O sistema deve ser desenvolvido usando os conceitos de orientação a objeto.</sub>|<sub>BAIXA</sub>|
|<sub>RF08</sub>|<sub>O sistema deve interagir com o sistema acadêmico da instituição e o acervo digital.</sub>|<sub>ALTA</sub>|
|<sub>RF09</sub>|<sub>O sistema deve permitir que os administradores alterem o nome, descrição, código e disponibilidade dos livros.</sub>|<sub>ALTA</sub>|
|<sub>RF10</sub>|<sub>O sistema deve permitir a reserva de um livro somente se ele estiver em estoque.</sub>|<sub>MÉDIA</sub>|
|<sub>RF11</sub>|<sub>O sistema deve permitir que o usuário consulte o status do livro que foi emprestado, bem como seus dados, data do empréstimo e devolução.</sub>|<sub>BAIXA</sub>|
|<sub>RF12</sub>|<sub>O sistema não deve permitir que mais de um usuário reserve o mesmo livro.</sub>|<sub>MÉDIA</sub>|
|<sub>RF13</sub>|<sub>O sistema deve possuir um algoritmo capacitado para dar recomendações de livros aos seus usuários, de acordo com suas áreas de interesse e histórico de leitura.</sub>|<sub>BAIXA</sub>|
|<sub>RF14</sub>|<sub>O sistema deve ter um sistema de busca especializado para facilitar a pesquisa de seus usuários, preferencialmente categorizando-a de maneira mais intuitiva.</sub>|<sub>ALTA</sub>|
|<sub>RF15</sub>|<sub>O sistema deve permitir que o usuário envie reclamações, elogios ou feedbacks para os bibliotecários.</sub>|<sub>BAIXA</sub>|

|ID|Requisitos Não-Funcionais|Prioridades|
|:---:|:---:|:---:|
|<sub>RNF01</sub>|<sub>Os bibliotecários devem ser capazes de utilizar todas as funcionalidades do sistema após um dia de uso.</sub>|<sub>ALTA</sub>|
|<sub>RNF02</sub>|<sub>Os estudantes e professores devem ser capazes de aprender a utilizar o sistema inteiramente com apenas alguns minutos de visualização.</sub>|<sub>ALTA</sub>|
|<sub>RNF03</sub>|<sub>As consultas e buscas pela disponibilidade dos livros devem ser respondidas em menos de 3 segundos.</sub>|<sub>MÉDIA</sub>|
|<sub>RNF04</sub>|<sub>O sistema deve possuir uma interface interativa.</sub>|<sub>MÉDIA</sub>|
|<sub>RNF05</sub>|<sub>O sistema deve suportar 500 usuários concorrentemente.</sub>|<sub>ALTA</sub>|
|<sub>RNF06</sub>|<sub>O sistema deve ser multiplataforma.</sub>|<sub>MÉDIA</sub>|
|<sub>RNF07</sub>|<sub>O sistema deve estar disponível 24 horas por dia, 7 dias por semana.</sub>|<sub>ALTA</sub>|
|<sub>RNF08</sub>|<sub>O sistema deve ter uma hospedagem robusta e confiável.</sub>|<sub>ALTA</sub>|
|<sub>RNF09</sub>|<sub>O sistema deve realizar atualizações e backups automáticos, num servidor financiado pelo próprio fornecedor.</sub>|<sub>ALTA</sub>|
|<sub>RNF10</sub>|<sub>O sistema deve suportar os sistemas operacionais Windows e Linux, e os navegadores mais famosos.</sub>|<sub>MÉDIA</sub>|
|<sub>RFN11</sub>|<sub>O sistema deve garantir a segurança e proteção dos dados contra acessos externos.</sub>|<sub>ALTA</sub>|
|<sub>RFN12</sub>|<sub>O sistema da biblioteca deve estar integrado com o sistema acadêmico da escola.</sub>|<sub>ALTA</sub>|


|ID|Histórias de Usuário|
|:---:|:---:|
|<sub>HU01</sub>|<sub>Como bibliotecário, eu quero cadastrar usuários no sistema, para ter maior controle sobre o gerenciamento de seus perfis.</sub>|
|<sub>HU02</sub>|<sub>Como um usuário do sistema, eu quero consultar a disponibilidade de um livro, para saber se ele pode ser emprestado ou não.</sub>|
|<sub>HU03</sub>|<sub>Como bibliotécario, eu quero registrar o status e a descrição de um livro, para estar ciente do histórico de transações dele e seu conteúdo.</sub>|
|<sub>HU04</sub>|<sub>Como bibliotecário, eu quero ter acesso ao catálogo completo dos títulos presentes na biblioteca, para não ter falta de informações em meu serviço.</sub>|
|<sub>HU05</sub>|<sub>Como usuário e bibliotecário, eu quero ter facilidade ao utilizar o sistema, para tornar o processo de aprendizado rápido e eficiente.</sub>|
|<sub>HU06</sub>|<sub>Como estudante, eu quero receber recomendações de livros com base nas minhas últimas leituras, para encontrar outros títulos semelhantes da minha área de interesse com mais facilidade.</sub>|
|<sub>HU07</sub>|<sub>Como usuário, eu quero ter acesso ao chat de suporte ao usuário e um espaço reservado para feedback, para que assim possa ter minhas dúvidas saciadas e opiniões validadas ao utilizar o sistema.</sub>|
|<sub>HU08</sub>|<sub>Como bibliotecário, eu quero um sistema altamente responsivo, para agilizar minhas tarefas manuais. </sub>|
|<sub>HU09</sub>|<sub>Como estudante ou professor, eu quero poder consultar livros com antecedência, para que possa reservá-lo e agilizar o processo de empréstimo. </sub>|
|<sub>HU10</sub>|<sub>Como bibliotecário, eu quero um sistema confiável com backup automático, para que não perca alterações feitas durante o meu trabalho. </sub>|

### Entrevistas
<h3 align="center">INFORMAÇÕES</h3>

⦁ `Por que?` Coletar dados sobre que melhorias e funções implemetar em nosso sistema

⦁ `Quem?` Bibliotecários e estudantes

⦁ `Quando?` Terça ou quinta

⦁ `Onde?` Biblioteca

⦁ `Como?` Será registrado através de GRAVAÇÃO e questões específicas, avaliativas e categóricas

<br>

<h3 align="center">PERGUNTAS PARA ESTUDANTES</h3>

1. Quais funcionalidades você considera essenciais em um sistema de gerenciamento de biblioteca escolar?
2. Qual é a sua experiência com o suporte ao usuário do sistema atual e o que poderia ser melhorado nesse aspecto?
3. Como você avalia a eficiência do sistema atual e o que poderia ser feito para melhorá-lo? Quais recursos adicionais você gostaria de ver no sistema que poderiam apoiar o aprendizado e a pesquisa?
4. O que você acha que precisa ser feito para atrair mais estudantes para as bibliotecas?
5. Como você descreveria a interface do usuário do sistema atual? Você acha prática e intuitiva, fácil de usar?
6. Você gostaria de fazer alguma reclamação ou crítica construtiva para a melhoria do sistema?

<br>

<h3 align="center">PERGUNTAS PARA BIBLIOTECÁRIOS</h3>

1. Quais funcionalidades você considera essenciais em um sistema de gerenciamento de biblioteca escolar?
2. Qual é a sua experiência com o suporte ao usuário do sistema atual e o que poderia ser melhorado nesse aspecto?
3. Tem algum trabalho manual que você acha imprático (tipo a catalogação e a gestão de recursos), que poderia ser automatizado?
4. Como você avalia a eficiência do sistema atual e o que poderia ser feito para melhorá-lo? Quais recursos adicionais você gostaria de ver no sistema que poderiam apoiar o aprendizado e a pesquisa?
5. O que você acha que precisa ser feito para atrair mais estudantes para as bibliotecas? Como você imagina a biblioteca do futuro e quais características do sistema atual você acredita que devem ser mantidas ou adaptadas para esse futuro?
6. Como você descreveria a interface do usuário do sistema atual? Ela é intuitiva e amigável para todos os usuários?
7. Você recebe ou já recebeu alguma reclamação ou crítica construtiva que queira compartilhar? Aqui ou da ouvidoria? Sem pressão

***   
**As entrevistas estão armazenadas como os arquivos [Entrevista Bibliotecária](https://github.com/abnerns/grupo9-biblioteca/blob/main/Entrevista%20Bibliotec%C3%A1ria.pdf) e [Entrevista Estudante](https://github.com/abnerns/grupo9-biblioteca/blob/main/Entrevista%20Estudante.pdf) aqui no repositório. Você pode encontrar as gravações nos links:**

- https://github.com/abnerns/grupo9-biblioteca/blob/main/entrevista_bibliotecaria.m4a
- https://github.com/abnerns/grupo9-biblioteca/blob/main/entrevista_estudante.m4a



## 2.2. Protótipos

- Ambiente Bibliotecário: https://ninjamock.com/s/T51ZKLx
- Ambiente Usuário (Mobile): https://ninjamock.com/s/XG43JLx

# Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.

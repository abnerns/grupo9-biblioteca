
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

O objetivo da LibraTech é fornecer um registro de livros e documentos de uma biblioteca escolar, possibilitando gerenciar acervos híbridos com disponibilização de status (disponível, alugado ou para consulta), tanto físicos quanto digitais, além da busca especializada por arquivos, cadastro de usuários, catalogação, sistema de avaliações, facilidade para planejamento de aulas e possibilidade de realizar empréstimos pelo software. Sobretudo, busca otimizar a performance dos funcionários e facilitar a vida dos seus usuários, valorizando praticidade e eficiência.

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

|Requisitos Funcionais|
|:---:|
|<sub>RF01 O software deve permitir que o bibliotecário cadastre usuários no sistema, como estudantes e professores, e monitore seus perfis.</sub>|
|<sub>RF02 O sistema deve registrar a disponibilidade de um livro.</sub>|
|<sub>RF03 O sistema deve manter um registro de todas as transações de empréstimo e devolução.</sub>|
|<sub>RF04 O sistema deve conter um catálogo de todos os livros na biblioteca, junto com uma breve descrição.</sub>|
|<sub>RF05 O software deve possuir uma interface interativa. </sub>|
|<sub>RF06 O sistema deve separar os livros e documentos físicos em seções de acordo com suas categorias.</sub>|
|<sub>RF07 O software deve garantir a segurança e proteção dos dados contra acessos externos.</sub>|
|<sub>RF08 O software deve ter compatibilidade com diversos dispositivos.</sub>|
|<sub>RF09 O sistema da biblioteca deve estar integrado com o sistema acadêmico da escola.</sub>|
|<sub>RF10 O acervo da biblioteca deve receber atualizações de seus arquivos em tempo real, com um backup automático.</sub>|
|<sub>RF11 O sistema deve permitir que os administradores alterem informações de livros.</sub>|
|<sub>RF12 O sistema deve permitir a reserva de um livro somente se ele estiver em estoque</sub>|
|<sub>RF13 O sistema deve permitir que o usuário consulte o status do livro que foi emprestado, bem como seus dados, data do empréstimo e devolução.</sub>|
|<sub>RF14 O sistema não deve permitir que mais de um usuário reserve o mesmo livro.</sub>|
|<sub>RF15 O software deve recomendar livros aos seus usuários, de acordo com suas categorias de interesse.</sub>| 

|Requisitos Não-Funcionais|
|:---:|
|<sub>RNF01 Os bibliotecários devem ser capazes de utilizar todas as funcionalidades do sistema após um dia de uso.</sub>|
|<sub>RNF02 Os estudantes e professores devem ser capazes de aprender a utilizar o sistema inteiramente com apenas alguns minutos de visualização.</sub>|
|<sub>RNF03 As consultas e buscas pela disponibilidade dos livros devem ser respondidas em menos de 3 segundos.</sub>|
|<sub>RNF04 O sistema deve ter um chat para tirar dúvidas sobre seu uso, disponível em todas as páginas e sempre acessível.</sub>|
|<sub>RNF05 O sistema deve suportar 500 usuários concorrentemente.</sub>|
|<sub>RNF06 O sistema deve ser multiplataforma.</sub>|
|<sub>RNF07 O sistema deve estar disponível 24 horas por dia, 7 dias por semana.</sub>|
|<sub>RNF08 O sistema deve ter uma hospedagem robusta e confiável.</sub>|
|<sub>RNF09 O sistema deve realizar atualizações e backups automáticos, num servidor financiado pelo próprio fornecedor.</sub>|
|<sub>RNF10 O sistema deve suportar os sistemas operacionais Windows e Linux, e os navegadores mais famosos.</sub>|
|<sub>RNF11 O sistema deve ser desenvolvido usando os conceitos de orientação a objeto.</sub>|
|<sub>RNF12 O sistema deve interagir com o sistema acadêmico da instituição e o acervo digital</sub>|

## 2.2. Protótipos

*<Link para a pasta com os protótipos.>*

# Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.

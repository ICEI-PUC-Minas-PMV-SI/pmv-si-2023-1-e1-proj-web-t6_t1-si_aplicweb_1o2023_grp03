# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

O objetivo do nosso projeto é desenvolver um site chamado "cofrinho", que ajuda os usuários a organizar suas finanças pessoais.
Um problema que muitos usuários enfrentam é a falta de organização financeira que dificulta o usuário alcançar seus objetivos financeiros.
Para solucionar este e outros problemas nosso site disponibiliza uma calculadora financeira para ajudar os usuários a definir metas
financeiras e traçar planos para alcançá-las, permitindo que os usuários meçam o desempenho simplesmente fazendo economias, ou
investimentos a longo prazo.
Manter as finanças pessoais em ordem é um aspecto essencial para garantir a estabilidade financeira e alcançar obejtivos a longo prazo,
o site "cofrinho" promete auxiliar nesse processo, fornecendo ferramentas e recursos úteis para criar orçamentos e planejar investimentos.
No nosso site os usuários podem estabelecer qualquer meta financeira, como economizar para uma viajem, saldar dívidas ou criar um fundo de
emergência. O recurso de rastreamento de progresso permite que o usuário acompanhe seu progresso em relação às metas estabelecidas.
Existem muitas ferramentas financeiras mas o diferencial do site "Cofrinho" é que ele promete atender todas todas as necessidades
específicas dos usuários. O nosso site também conta com uma solução personalizada e de fácil utilização, as sugestões de melhoria
incluem uma interface simples, instrutiva e amigável.

## Personas

Paulo Henrique tem 25 anos, é advogado, solteiro e sonha em fazer pós graduação em Direito Internacional na Universidade de Roma,
na Itália, pois quer sair da sua zona de conforto e viver essa experiência em outro país.
Para que isso aconteça Paulo Henrique precisa juntar no mínimo 50.000 reais, somando o valor da passagem, valor anual da pós graduação e
gastos pessoais, Paulo está ciente que precisa de um serviço que o ajude a atingir está meta estabelecida e depois de algumas pesquisas 
ele encontra o site "Cofrinho" e solicita o nosso serviço. Paulo é direcionado a nossa página introdutória e depois solicita o serviço do
formulário, onde ele informa na nossa calculadora financeira em quanto tempo ele levaria para atingir sua meta investindo 1.000 reais 
mensalmente e aplicando uma rentabilidade média de 20% ao ano, com as informações necessárias obtidas é mostrado que seriam necessários
38 meses para ele conseguir atingir sua meta financeira, é mostrado uma tabela para o caso de poupar dinheiro, e a outra tabela
para o caso de investir o dinheiro com o retorno de 1% ao mês.
Paulo Henrique por sua vez, achou um bom negócio e começa a investir o seu dinheiro no seu tão desejado sonho.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

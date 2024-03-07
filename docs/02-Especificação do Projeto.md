# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

1-Joana Oliveira Dos Santos

Joana tem 27 anos, formada em educação física e é dona de sua própria escola de artes marciais. Entusiasmada e positiva, gosta muito de leitura que estimulam sua mente,
e que ajudem ela aprimorar seus exercícios físicos. 

Motivação: 
Tem muito interesse em usar o APP para pode compartilhar com todos (principalmente seus alunos), 
resenhas sobre os livros de auto- ajuda, e instruções para melhorar suas técnicas em artes marciais. 

Necessidades:
Gostaria de uma forma rápida para selecionar seus livros favoritos, e também filtrar com um filtro que funcione bem para filtrar por gênero
(pois a mesma sempre vai estar procurando livros relacionados à esportes, e auto- ajuda).

2- Bernardo Silva Prado----Administrador do Sistema BookFlows

Bernardo tem 35 anos, é programador Full-Stack.  Trabalha a 10 anos como programador de sistemas, com foco em desenvolvimento de software web e mobile e criador do APP.

Motivação:
Contribuir para o desenvolvimento de ferramentas que auxiliem na pesquisa e análise de informações tecnológicas.
 Usar sua experiência em tecnologia para ajudar a melhorar a qualidade das resenhas e avaliações de livros, tornando mais fácil para os usuários encontrarem os livros que procuram.
Bernardo pode compartilhar suas próprias resenhas e insights sobre livros e tecnologia, ajudando outros usuários a tomar decisões de compra mais informadas.
Desenvolver novas funcionalidades para a plataforma BookFlows, como um sistema que auxilia na pesquisa e análise de informações.

Necessidades:

Acessar resenhas e avaliações de outros profissionais de tecnologia.
Usar um sistema de busca robusto e filtros específicos para o nicho tecnológico.
Encontrar livros relevantes de forma rápida e eficiente.

3- Gabriela Costa

Gabriela costa tem 22 anos, estudante de letras, mora em Ouro Preto, em Minas Gerais. Se interessa muito por literatura brasileira e estrangeira. Foca mais em livros de poesia e teoria literária.

Motivação: 
Leitora apaixonada, lê diversos gêneros, mas tem um carinho especial por clássicos e livros contemporâneos. Busca livros para aprofundar seus conhecimentos literários, 
encontrar novas leituras para seus estudos e descobrir autores desconhecidos.

Necessidades: 
Criar listas de leitura personalizadas por gênero, autor, época ou tema. Acessar informações detalhadas sobre os livros, como resumos, 
críticas literárias e trechos do texto. Conectar-se com outros estudantes de Letras para trocar ideias e discutir sobre suas leituras. 
Receber dicas de leitura personalizadas com base em seus gostos e histórico de leitura


## Histórias de Usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/DESEJO ... `O QUE` |PARA ... `PORQUE`                 |
|--------------------|------------------------------------|----------------------------------------|
|Joana Oliveira dos Santos (Usuária)| Aplicativo de livros para compartilhar e uso próprio| Aplicativo para facilitar o compartilhamento de livros com alunos e para uso próprio de leitura.|
|Bernardo Silva Prado (Desenvolvedor)| Um aplicativo para melhorar a qualidade das resenhas e avaliações de livros, tornando mais fácil para os usuários encontrarem os livros que procuram| Encontrar livros de forma eficiente e rápida.|
|Gabriela Costa (Usuária)| Uma ferramenta para personalizar livros por gênero, autor ou tema. Uma área de comentários para poder interagir com outros leitores| Para facilitar achar livros que despertem interesse nos leitores e troca de conhecimentos.|



Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Apresente aqui os problemas existentes que viabilizam sua proposta. Apresente o modelo do sistema como ele funciona hoje. Caso sua proposta seja inovadora e não existam processos claramente definidos, apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente, mesmo que não se utilize tecnologia computacional. 

### Descrição Geral da Proposta

Apresente aqui uma descrição da sua proposta abordando seus limites e suas ligações com as estratégias e objetivos do negócio. Apresente aqui as oportunidades de melhorias.

### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores. 

Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    |Descrição do Requisito| Prioridade |
|------|----------------------|------------|
|RF-001| O aplicativo deve permitir o cadastro de usuários. |ALTA|
|RF-002| O aplicativo deve permitir o login de clientes. |ALTA|
|RF-003| O aplicativo deve apresentar uma lista com os livros. |ALTA|
|RF-004| O aplicativo deve permitir que o usuário altere os seus dados. |ALTA|
|RF-005| O aplicativo deve apresentar uma barra de pesquisa. |ALTA|
|RF-006| O aplicativo deve ter avaliação e comentários. |ALTA|
|RF-007| O aplicativo deve ter opção de filtro. |MÉDIA|
|RF-008| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-009| Emitir um relatório de tarefas no mês   | MÉDIA |



### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

|ID  | Descrição do Requisito  |Prioridade |
|----|-------------------------|----|
|RNF-001| A aplicação deve estar disponível 24 horas por dia, todos os dias da semana  | ALTA ||ALTA|
|RNF-002| A aplicação deve ter bom nível de contraste entre os elementos da tela em conformidade |MÉDIA|
|RNF-003| O aplicativo deve processar requisições do usuário em no máximo 3s |BAIXA|
|RNF-004| A aplicação deve ser compatível com um dispositivos móvel.| MÉDIA |
|RNF-005| A aplicação deve ter uma linguagem simples e de fácil entendimento | ALTA |
|RNF-006| A aplicação deve ter uma boa navegabilidade e usabilidade, facilitando a experiência do usuário | ALTA |
|RNF-007| Por se tratar de uma aplicação com abrangência nacional, a mesma deve comportar grandes acessos simultâneos | ALTA |


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
|01| O projeto deverá ser entregue até o final do semestre. 
|02| Não será usada validação de dados back-end em uma linguagem separada (C#, JAVA, Python).        
|03| Será desenvolvido com a ferramenta React Native.       
|04| O projeto final para uso de fins pessoais não é permitido.
|05| Não será utilizada geração de código automáticos, gerados por IAs.     
|06|	O projeto deve ser compatível com navegadores antigos (IE11, Edge Legacy).
|07| O projeto deve ser testado em diferentes dispositivos (smartphones, tablets, desktops).
|08| O projeto deve ser aprovado pelos desenvolvedores antes de ser lançado.
|09| O projeto deve ser fácil de usar e entender.
|10| O projeto deve ser escalável para acomodar o crescimento futuro.


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)

# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)

> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)

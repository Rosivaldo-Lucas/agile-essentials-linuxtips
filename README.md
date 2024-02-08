# Agile Essentials

## Aula 2 - O Scrum, seus papéis, ritos e artefatos

O termo "Scrum" é derivado do esporte Rugby. O Rugby é um jogo onde os jogadores fazem uma formação com os braços entrelaçados, assim tendo que colaborarem como equipe para vencer-lo.

Portanto, o nome "Scrum" foi escolhido para destacar a natureza colaborativa, adaptável e ágil da metodologia, inspirada nas práticas e valores observados no esporte de Rugby.

#### Papéis
- Product Owner
- Scrum Master
- Member of the Team

### Ritos
- Daily
- Sprint
- Sprint Review
- Sprint Retrospective

### Artefatos
- Product Backlog
- Sprint Backlog
- Burndown Chart

![Scrum](/docs/scrum.png)

## Aula 3 - As práticas do Extreme Programming

O Scrum tem mais a ver com a atitude e o Extreme Programming, ou o XP, tem a ver com a prática.

![Scrum](/docs/scrum-xp.png)

O desenvolvimento de um projeto com XP tem um ciclo contínuo e com quatro fases:

* **Planejamento:**
  É onde se define o que deve ser feito. Aqui define e prioriza as fases de desenvolvimento (incluindo o que será o mínimo produto viável e suas possíveis versões futuras). Também é aqui que as histórias de usuários são escritas.

* **Projeto:** As histórias apresentadas são discutidas em mais detalhe e a palavra de ordem é KISS (Keep it Simple, Stupid), que em tradução é: mantenha as coisas simples, seu idiota. Aqui é verificado com a equipe o tamanho das histórias de usuário, caso muito longas, ela é chamada de épico e, quando chega o momento do desenvolvimento, ela será subdividida em histórias menores.
  
* **Codificação:** Dúvidas surgirão no desenvolvimento. Por isso, o usuário ou cliente devem estar sempre acessíveis para responder às perguntas. Fica a cargo da equipe em decidir como será o desenvolvimento das soluções. É recomendado que a codificação comece pelos testes, utilizando a abordagem Test Driven Development (TDD), mas não é uma regra.
  
* **Testes:** Por fim, os testes devem ser realizados. Aqui os bugs devem ser priorizados, a cada bug encontrado ele deve ser resolvido imediatamente e, a primeira coisa a ser feita, é criar um teste que detecte esse bug, depois a solução.

## Aula 4 - O Product Owner (Dono do Produto)

Preferencialmente o **Product Owner** deve ser alguém que seja o cliente ou o usuário do que será desenvolvido. Na maioria das vezes isso não é possível e o mais comum é termos o **Proxy Product Owner**: a pessoa que vai buscar entender as necessidades (e os possíveis desejos) dos clientes e usuários da solução desenvolvida. O Product Owner junto com usuários e os patrocinadores do projeto, irá criar a lista de histórias a serem desenvolvidas.

Exemplos de criação de histórias:

    Como {ator}, desejo {realizar ação} para {atingir objetivo}

---
    
    Como estudante, desejo consultar as opções de refeições em locais próximos para escolher onde vou almoçar, com base em pontuações de outros estudantes.

As histórias serão apresentadas à equipe de desenvolvimento, em um **Product Backlog**, que discutirá quais delas podem ser desenvolvidas no período do Sprint, que pode ser de uma, duas ou quatro semanas.

Junto com o time de desenvolvimento, o **Product Owner** irá discutir e refinar as histórias descritas no **Product Backlog**, afim de melhorar o entendimento da equipe.

## Aula 5 - O Scrum Master

O Scrum Master, o sacerdote do Scrum, o guardião-mor dos ritos e artefatos e, fundamentalmente, a pessoa responsável por propagar a palavra do Scrum até para além da equipe.

O Scrum Master é responsável por resolver impedimentos de qualquer natureza e, também deve trabalhar de forma que novos impedimentos de natureza similiar não aconteçam mais.

O Scrum Master também deve se manter atualizado. Ele deverá ser capaz de esclarecer, para a equipe, dúvidas sobre o próprio Scrum.

O rito mais importante do Scrum é a reunião diária. Essa reunião é tão efetiva que muitas organizações acabam nem implementando o Scrum além disso porque já se dão por satisfeitas, o que é um "mau cheiro". O Scrum vai muito além disso e o Scrum Master deve orientar todos quanto a necessidade do cumprimento dos demais ritos e o preenchimento dos artefatos (Product Backlog, Sprint Backlog, Burndown Chart).

O Scrum Master também deve atuar blindando a equipe de desenvolvimento contra interferências externas durante o período da Sprint.

Perguntas que devem ser respondidas na Reunião Diária:

* O que fiz no dia anterior para contribuir com o objetivo do Sprint (o período de desenvolvimento).
  
* O que pretendo fazer hoje para contribuir com o objetivo do Sprint.
  
* O que está atrapalhando o meu trabalho.

## Aula 6 - A equipe Scrum

O Product Owner está sempre presente para o caso da equipe ter dúvidas, mas fora as reuniões (ritos) de Sprint Planning e Sprint Review, ele só se junta à equipe quando for convidado.

O quadro Scrum é feito pela equipe, uma variação do KanBan, estará sempre visível e não só o Product Owner como todos os patrocinadores e potenciais usuários poderão ver o que está acontecendo, como o trabalho está evoluindo, mas ninguém interrompe o trabalho da equipe durante o Sprint.

Dentro da equipe temos entre três e sete membros (cinco, mais ou menos dois), sempre um número ìmpar. Dentro da equipe todos os talentos necessários para o desenvolvimento do projeto, solução ou produto devem ser do domínio das pessoas da equipe. É comum que nos primeiros Sprints, a equipe tenha dificuldade e seja necessário trazer um especialista para apoiar em algo que ninguém sabe direito.

A equipe Scrum é autogerenciável. No começo de cada Sprint, a equipe vai escolher quantas histórias será capaz de desenvolver. A equipe poderá até negociar com o Product Owner alguma repriorização, a re-escrita ou a divisão das histórias, mas sempre o Producr Owner que tem a palavra final sobre o Product Backlog.

A equipe escolheu as histórias que vai realizar durante o Sprint e as coloca, na forma de Post-Its, no quadro Scrum, que é baseado no KanBan, um quadro de progressão de tarefas. A parte esquerda do quadro ficam as tarefas que irão ser realizadas, no meio, o que está sendo feito e, na direita, o que está conclído.

Todos acompanham a progressão das histórias, verificam a definição de pronto antes de passá-las para a direita do quadro e a expectativa é que, ao final do Sprint, todas as hostórias desenvolvidas possam ser consideradas como entregues pelo Product Owner.

## Aula 7 - O Product Backlog

O Product Owner é o dono desse artefato (Product Backlog). O Product Owner não é um desenvolvedor, mas uma pessoa que entende do domínio do produto, que pode ser a pessoa que será beneficiada pelo produto ou uma empresa que acredita que o produto será útil para outras pessoas.

Para a criação das histórias, é recomendado seguir o seguinte modelo de descrição:

```
Como {autor}, desejo {realizar ação} para {atingir objetivo}
```

```
Como estudante, desejo consultar as opções de refeições em locais próximos para escolher onde vou almoçar, com base em pontuações de outros estudantes.
```

![Backlog](/docs/scrum-backlog-1.png)

![Backlog](/docs/scrum-backlog-2.png)

## Aula 8 - O Sprint e seu Planejamento (Sprint Planning)

O Product Owner apresenta para a equipe o produto, tudo que se deseja para ele, mas dando ênfase ao que já está priorizado para o Mínimo Produto Viável. É nessa reunião que a equipe tirará as dúvidas sobre as histórias dessa primeira versão, provavelmente subdividirá várias delas em histórias menores e, a partir dessas hostórias o mais definidas possível, escolherá quais se sente a vontade para desenvolver durante o Sprint. Não há obrigação da equipe desenvolver todas as histórias do MVP, apenas aquelas que ela acredita que conseguirá resolver.

Em um Sprint de uma semana, essa reunião de Sprint Planning dura cerca de uma hora. Havendo tempo, a equipe irá discutir com o PO também as histórias seguintes, que não fazem parte do MVP. Quanto mais perto do momento de entrarem no desenvolvimento, mais estas histórias estarão detalhadas, divididas em menores.

![Backlog](/docs/scrum-sprint-planning.png)

Se passado a primeira hora da reunião, a equipe tem mais uma hora para a discussão técnica, sobre como irá desenvolver cada uma das histórias. Bibliotecas, linguagens e técnicas de programação, prerrequisitos. Fica a critério da equipe pedir que o PO participe, ou não, dessa reunião. Mas a equipe poderá chamá-lo sempre que for necessário.

A equipe deve usar sempre um Post-It por histório, e no verso, poderá escrever as tarefas técnicas que resolverão a história. Caso necessário, novos Post-Its podem ser colados em conjunto com o da história original.

No primeiro dia, todas as histórias são colocadas na coluna "A Fazer (TO DO)" do quadro do Scrum.

Feito isso, as histórias deverão ser alocadas a seus resolvedores, e assim o trabalho começa!

No dia seguinte, com todos em frente ao quadro Scrum, as histórias são evoluídas (passam para a coluna "Feito (Done)", novas histórias são trazidas para a coluna "Em Progresso" (In Progress)). O Burndown Chart, é preenchido e a equipe têm todos os dados para acompanhar a evolução do seu trabalho.

## Aula 10 - A reunião de revisão do Sprint (Sprint Review)

Essa reunisão acontece no último dia, nas primeiras horas da tarde e dura uma hora. A duração pode aumentar proporcionalmente conforme a duração do Sprint.

A equipe escolhe a ordem em que as histórias serão apresentadas. A equipe, então, faz a demostração das histórias desenvolvidas. O Product Owner pode convidar outras pessoas para essa demostração. O Product Owner pode considerar que uma determinada história, considerada pronta pela equipe, de fato não está pronta. Então a equipe faz as devidas anotações, conversa com o PO e tenta entender se foi problema na especificação da história, na compreensão da equipe, se faltou incluir algo na definição de pronto (e isso será feito nesse exato momento). A equipe deve entender o que aconteceu de errado.

Histórias não consideradas prontas voltam para o próximo Sprint, a não ser que o PO tenha algo mais prioritário já colocado no topo do Product Backlog.

A partir daí há duas opções: a equipe já faz a Sprint Planning para o período seguinte, aproveitando a presença do Product Owner, ou parte para a Revisão do Sprint, a gentil lavagem de roupa suja.

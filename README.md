# GamIES: Um framework para Gamificação de Sala de Aula Invertida em Engenharia de Software

Bem-vindo ao GamIES! Este documento oferece uma visão geral e orientações sobre como aplicar nosso framework para integrar elementos de gamificação em suas aulas invertidas, potencializando a motivação e o engajamento dos alunos.

## Índice

- [Visão Geral](#visao-geral)
- [Principais Objetivos](#principais-objetivos)
- [Como Funciona](#como-funciona)
- [Estrutura](#estrutura)
- [Ferramentas de Apoio](#ferramentas-de-apoio)
- [Contato](#contato)

### Visão Geral

O **GamIES** é um framework desenvolvido para auxiliar professores de Engenharia de Software no planejamento e execução de suas aulas, promovendo um processo de ensino mais eficaz e envolvente. O framework visa transformar a abordagem tradicional, facilitando a criação e gestão de aulas invertidas de maneira integrada, combinando teoria, prática e elementos de gamificação.

### Principais Objetivos

- **Eficiência no Planejamento**: Fornecer uma estrutura que permita aos professores criar e gerenciar aulas invertidas com agilidade, otimizando o tempo de preparação de materiais e atividades.

- **Integração da Gamificação**: Integrar elementos de gamificação, como pontuação e recompensas, para aumentar o engajamento dos alunos e incentivar a participação ativa.

- **Avaliação Contínua**: Implementar mecanismos de avaliação que permitam monitorar o progresso dos alunos de forma contínua, permitindo adaptar o ensino conforme necessário para suprir lacunas no aprendizado.

- **Foco na Aplicação Prática**: Facilitar a realização de atividades práticas que complementem o conteúdo teórico estudado, promovendo a aplicação prática do conhecimento e a resolução de problemas reais.


## Como Funciona

Este framework oferece uma estrutura detalhada para orientar a elaboração dos materiais necessários para a implementação de aulas invertidas, integrando de forma eficaz elementos de gamificação para enriquecer o processo de ensino e aprendizagem. Esta integração permite criar um ambiente de aprendizagem mais envolvente e dinâmico, facilitando a aplicação prática dos conceitos e promovendo uma maior interação e motivação dos alunos.


## Estrutura

<div style="text-align: center;">
  <a href="#frame-1">
    <img src="Estrutura/estrutura-framework1.png" alt="Estrutura 1" style="width: 50%; display: block; margin: 20px auto;">
  </a>
  <a href="#frame-2">
    <img src="Estrutura/estrutura-framework2.png" alt="Estrutura 2" style="width: 50%; display: block; margin: 20px auto;">
  </a>
  <a href="#frame-3">
    <img src="Estrutura/estrutura-framework3.png" alt="Estrutura 3" style="width: 50%; display: block; margin: 20px auto;">
  </a>
  <a href="#frame-4">
    <img src="Estrutura/estrutura-framework4.png" alt="Estrutura 4" style="width: 50%; display: block; margin: 20px auto;">
  </a>
</div>



O framework GamIES é organizado em quatro componentes principais: **Planejamento e Preparação**, **Ciclo de Aprendizagem**, **Sistema de Gamificação**, e **Troca de Pontos**. As seções seguintes oferecem uma descrição detalhada de cada um desses componentes. A imagem abaixo ilustra a estrutura geral do framework.


<div style="text-align: center;">
  <a href="#frame-1">
    <img src="Estrutura/estrutura-framework1.png" alt="Estrutura 1" style="width: 50%; margin: 30px 0;">
  </a>
  <a href="#frame-2">
    <img src="Estrutura/estrutura-framework2.png" alt="Estrutura 2" style="width: 50%; margin: 30px 0;">
  </a>
  <a href="#frame-3">
    <img src="Estrutura/estrutura-framework3.png" alt="Estrutura 3" style="width: 50%; margin: 30px 0;">
  </a>
  <a href="#frame-4">
    <img src="Estrutura/estrutura-framework4.png" alt="Estrutura 4" style="width: 50%; margin: 30px 0;">
  </a>
</div>


<a name="frame-1"></a>
### 1. Planejamento e Preparação

Esta etapa é fundamental para garantir que o conteúdo seja apresentado de maneira clara e organizada. As principais atividades incluem:

- **Definição do Conteúdo**: O professor deve selecionar o tema principal que será ensinado aos alunos. Por exemplo, na disciplina de Engenharia de Software, o tema escolhido pode ser Engenharia de Requisitos.
  
- **Segmentação dos Tópicos**: Após definir o conteúdo, o professor deve dividir o material em tópicos menores e gerenciáveis, garantindo que o material de estudo não seja excessivamente longo ou denso. Por exemplo, o tema de Engenharia de Requisitos poderia ser subdividido em tópicos como Conceitos e Tipos de Requisitos, Elicitação de Requisitos, Especificação de Requisitos e Gerenciamento de Requisitos.

- **Elaboração do Material**: O material didático deve ser preparado de acordo com os tópicos definidos, garantindo que todos os recursos necessários para o aprendizado estejam disponíveis. Para isso, o professor deve seguir as instruções do ciclo de aprendizagem, que descrevem em detalhes cada material e orientam sua elaboração.

- **Definição do Cronograma**:
  - O cronograma deve detalhar as datas de liberação de cada material para os alunos, os prazos de entrega, e as datas dos encontros presenciais.
  - Para os roteiros de estudo, é recomendável um prazo mais extenso devido à sua complexidade e o tempo necessário para a conclusão.
  - Uma prática recomendada é indicar, no início do roteiro, o tempo médio estimado que o aluno precisará para completar o estudo.
  - **Diretrizes para a Disponibilidade dos Materiais**:
    - **Avaliação Diagnóstica**, **Roteiro de Estudos** e **Avaliação Pré-Aula**: Estes devem ser disponibilizados juntos, idealmente com pelo menos cinco dias de antecedência em relação ao encontro com a turma ([Atividade Prática](#atividade-prática)).
    - **Atividade Prática**: Deve ser realizada na data estabelecida no cronograma.
    - **Avaliação Pós-Aula**: Deve ser disponibilizada no mesmo dia da [Atividade Prática](#atividade-prática), após o encontro com a turma.

<a name="frame-2"></a>
### 2. Ciclo de Aprendizagem

O ciclo de aprendizagem no framework GamIES é inspirado na metodologia de sala de aula invertida e é dividido em cinco etapas:

- **Avaliação Diagnóstica**: Avaliação inicial para verificar o conhecimento prévio dos alunos sobre o tema. Detalhes sobre como realizar essa avaliação estão descritos na seção [Avaliação Diagnóstica](#avaliação-diagnóstica).

- **Roteiro de Estudos**: Material que orienta o estudo dos alunos, preparado com base nos tópicos definidos na etapa de planejamento. A elaboração e a estrutura do roteiro são abordadas na seção [Roteiro de Estudos](#roteiro-de-estudos).

- **Avaliação Pré-Aula**: Verificação do aprendizado obtido pelos alunos após a realização do [Roteiro de Estudos](#roteiro-de-estudos). Detalhes sobre como realizar essa avaliação estão descritos na seção [Avaliação Pré-Aula](#avaliação-pré-aula).

- **Atividade Prática**: Atividade realizada em sala de aula, focada na aplicação prática dos conceitos estudados. Instruções para a definição e execução das atividades são fornecidas na seção [Atividade Prática](#atividade-prática).

- **Avaliação Pós-Aula**: Avaliação realizada após o encontro prático, com o objetivo de consolidar o aprendizado e identificar pontos que ainda necessitam de reforço. Detalhes sobre como realizar essa avaliação estão descritos na seção [Avaliação Pós-Aula](#avaliação-pós-aula).

Este ciclo se repete para cada novo tópico abordado no conteúdo, com a quantidade de tópicos e o cronograma das atividades sendo definidos na fase de [Planejamento e Preparação](#1-planejamento-e-preparação).


### Avaliação Diagnóstica

#### Descrição

Instrumento utilizado para avaliar o conhecimento prévio dos alunos em relação ao assunto que será abordado a fim de identificar quais conteúdos ele já domina e quais apresenta dificuldades.

#### Elementos de gamificação associados


<div style="display: flex; justify-content: space-between;">
  <a href="#game-dig">
    <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 12%; margin-right: 60px; pointer-events: none;">
    <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 12%; pointer-events: none;">
  </a>
</div>

#### Por que Fazer?

Isso permite identificar lacunas de aprendizado e ajustar o material de estudo de acordo com as necessidades individuais e coletivas dos estudantes. Além disso, também é uma oportunidade para que os estudantes se envolvam ativamente no processo de aprendizagem e reflitam sobre seus conhecimentos.

#### Como Fazer?

Geralmente, é realizada por meio de testes, questionários ou atividades que possibilitam ao professor ter um panorama sobre o nível de conhecimento do aluno.

<a name="game-dig"></a>
Adoção de elementos de Gamificação, como **pontuação** e **recompensas**, para incentivar os estudantes a se empenharem mais no estudo, criando um ambiente divertido e desafiador. A competição saudável entre os estudantes também pode aumentar a motivação e o engajamento na aprendizagem.

Em uma abordagem de ensino adaptativa, em que o conteúdo do material de estudos pode ser personalizado, é possível fazer ajustes no material, focando nas áreas que precisam ser aprimoradas e explorando assuntos que o estudante não possui um nível de conhecimento elevado.

#### Exemplos

- Questionário com questões objetivas e com pontuações associadas às questões
- Questionário auto declarativo

### Roteiro de Estudos

#### Descrição

Serve como guia para os alunos, no momento de preparação para as atividades em sala. Materiais de estudos são disponibilizados pelo professor para que o aluno estude e aprenda o conteúdo em casa.

#### Elementos de gamificação associados

<div style="display: flex; justify-content: space-between;">
    <img src="Elementos de gamificação/Desafios.png" alt="Desafios" style="width: 12%; margin-right: 60px; pointer-events: none;">
    <img src="Elementos de gamificação/Missoes.png" alt="Missões" style="width: 12%; pointer-events: none;">
    <img src="Elementos de gamificação/Narrativa.png" alt="Narrativa" style="width: 12%; pointer-events: none;">
</div>

#### Por que Fazer?

Para que os alunos possam estudar o conteúdo abordado e se preparar para as aulas práticas na sala de aula. Esse momento é importante para que os alunos aprendam a parte teórica do conteúdo ministrado e consiga ter um bom desempenho nas atividades que serão realizadas com base no conteúdo estudado.

#### Como Fazer?

Esse roteiro pode incluir assistir aulas em vídeo, leitura de materiais, pesquisas, entre outras atividades, com o objetivo de facilitar a aprendizagem e direcionar o estudo dos estudantes.

Alguns elementos de gamificação podem ser incluídos no roteiro de estudos, como desafios e missões, com o objetivo de motivar e engajar os estudantes.

Outro elemento de gamificação que pode ser utilizado é o de progressão, incluindo componentes como uma barra de progresso ou sistema de níveis.

#### Exemplos

- Vídeo aulas
- Artigos científicos
- Capítulos de livros
- Sites

### Avaliação Pré-Aula

#### Descrição

Instrumento de avaliação que deve ser aplicado antes da aula prática, com o propósito de verificar o conhecimento adquirido pelos alunos sobre o tema abordado no roteiro de estudo disponibilizado pelo professor.

#### Elementos de gamificação associados

<div style="display: flex; justify-content: space-between;">
    <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 12%; margin-right: 60px; pointer-events: none;">
    <img src="Elementos de gamificação/Feedback.png" alt="Feedback" style="width: 12%; pointer-events: none;">
    <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 12%; pointer-events: none;">
</div>

#### Por que Fazer?

O objetivo da avaliação pré-aula é identificar as lacunas do conhecimento do aluno e orientá-lo sobre quais tópicos precisam ser revistos ou reforçados durante o estudo. Além disso, essa avaliação também é importante para que o aluno formule dúvidas relacionadas ao assunto que podem ser direcionadas ao professor durante o momento em sala de aula.

#### Como Fazer?

Pode ser feita por meio de um questionário online, com questões de múltipla escolha, ou um exercício prático que estimule a reflexão sobre o assunto.

Uma opção de elemento de gamificação é o uso de uma barra de progresso ou pontuação que demonstre o desempenho do estudante enquanto ele responde às questões. À medida que o usuário acerta as perguntas, a barra de progresso aumenta ou a pontuação vai aumentando, demonstrando um feedback positivo. Por outro lado, quando uma resposta é incorreta, a barra de progresso pode diminuir ou a pontuação pode ser reduzida, oferecendo um feedback negativo e incentivando o usuário a melhorar seu desempenho.

Outro elemento de gamificação que pode ser adicionado são as conquistas ou medalhas. Ao acertar um certo número de perguntas, o usuário pode receber uma medalha ou conquista que será exibida em seu perfil ou em um placar. Essas medalhas funcionam como recompensas virtuais e motivam o usuário a continuar respondendo às questões.

Utilizar elementos visuais para fornecer um feedback imediato. Quando o usuário acertar uma questão, a resposta correta pode ser marcada em verde e o usuário pode visualizar uma animação positiva. Em contrapartida, ao errar, a resposta correta pode ser marcada em vermelho e o usuário pode ver uma animação indicando que a resposta está incorreta.

#### Exemplos

- Questionário com questões de múltipla escolha
- Feedback indicando uma resposta incorreta e uma resposta correta
- Elemento que mostre o desempenho e progresso do usuário
- Recompensas para incentivar o usuário

### Atividade Prática

#### Descrição

Atividades práticas realizadas na sala de aula ou no encontro da turma com o professor. Essas atividades podem envolver a resolução de problemas, simulações, jogos educacionais, quizzes, entre outras atividades relacionadas ao assunto abordado nos materiais disponibilizados anteriormente.

#### Elementos de gamificação associados

<div style="display: flex; justify-content: space-between;">
    <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 12%; margin-right: 60px; pointer-events: ;">
    <img src="Elementos de gamificação/Desafios.png" alt="Desafios" style="width: 12%; pointer-events: none;">
    <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 12%; pointer-events: none;">
    <img src="Elementos de gamificação/Competicao.png" alt="Competição" style="width: 12%; pointer-events: none;">
    <img src="Elementos de gamificação/Equipes.png" alt="Equipes" style="width: 12%; pointer-events: none;">
</div>

#### Por que Fazer?

Para que os alunos possam exercitar o conhecimento adquirido durante os estudos em casa. Durante este momento, o professor também pode responder às dúvidas dos alunos e avaliar o nível de compreensão da turma e ajustar suas explicações de acordo com as necessidades dos alunos.

#### Como Fazer?

O professor(a) deve marcar um encontro com a turma a ser realizado após a conclusão das etapas anteriores. No primeiro momento, o professor pode aproveitar para sanar dúvidas dos alunos com relação ao conteúdo abordado. Em seguida, deve ser realizada uma atividade prática em grupo sobre o assunto abordado. A atividade fica a critério do professor, e esta deve ser planejada antes do encontro com a turma.

Para promover a participação e melhor interação entre os alunos, alguns elementos de gamificação podem ser incluídos na atividade, como:

- **Pontuação**: Pontuar as atividades realizadas pelos alunos, criando um ranking ou tabela de classificação.
- **Recompensas**: Oferecer recompensas aos alunos que alcançarem determinados objetivos ou atingirem um número específico de pontos.
- **Desafios**: Propor desafios aos alunos, incentivando-os a resolver problemas utilizando o conhecimento adquirido.
- **Competições**: Promover competições em sala de aula, como quizzes ou jogos, estimulando a participação e a colaboração entre os alunos.
- **Premiações**: Premiar os alunos com melhores desempenhos ou que mais se destacarem durante as atividades gamificadas.

#### Exemplos

- Fornecer materiais das atividades que já realizamos
- Demonstrar o uso dos elementos de gamificação na prática

### Avaliação Pós-Aula

#### Descrição

Instrumento de avaliação que deve ser aplicado após a realização da aula prática, com o intuito de verificar o grau de compreensão e assimilação dos conteúdos pelos estudantes.

<div style="display: flex; justify-content: space-between;">
    <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 12%; margin-right: 60px; pointer-events: none;">
    <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 12%; pointer-events: none;">
    <img src="Elementos de gamificação/Badges.png" alt="Badges" style="width: 12%; pointer-events: none;">
</div>

#### Por que Fazer?

A avaliação pós-aula permite ao professor identificar se os objetivos de aprendizagem foram alcançados e se é necessário reforçar algum conteúdo. Também oferece aos alunos a oportunidade de revisar o conteúdo aprendido.

#### Como Fazer?

Pode ser feita por meio de testes, provas, trabalhos individuais ou em grupo, apresentações orais, entre outros.

#### Exemplos

- Questionário com questões de múltipla escolha
- Recompensa associada ao desempenho com relação a nota obtida ao responder o questionário

Aqui está uma versão aprimorada do texto com links para imagens, descrições e exemplos ilustrativos:

---

### Avaliação Diagnóstica

#### Descrição

A avaliação diagnóstica é uma ferramenta crucial para avaliar o conhecimento prévio dos alunos em relação ao conteúdo a ser abordado. Ela ajuda a identificar áreas de domínio e dificuldades, permitindo ajustes no material didático conforme as necessidades individuais e coletivas dos estudantes.

#### Elementos de Gamificação Associados

<div style="text-align: center;">
  <a href="#game-dig">
    <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 15%; margin-right: 30px;">
    <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 15%;">
  </a>
</div>

#### Por que Fazer?

Realizar uma avaliação diagnóstica é essencial para identificar lacunas no conhecimento dos alunos e adaptar o material de estudo. Além disso, envolve os alunos ativamente no processo de aprendizagem e estimula a reflexão sobre seu conhecimento.

#### Como Fazer?

A avaliação pode ser feita através de testes, questionários ou atividades que proporcionem uma visão geral do conhecimento dos alunos.

Adoção de elementos de gamificação, como **pontuação** e **recompensas**, pode aumentar a motivação dos alunos, criando um ambiente de aprendizagem mais dinâmico e envolvente. Estes elementos incentivam uma competição saudável e o engajamento dos estudantes.

#### Exemplos

- **Questionário com questões objetivas**: Inclui pontuações associadas às respostas.
- **Questionário auto declarativo**: Permite aos alunos avaliar seu próprio conhecimento.

### Roteiro de Estudos

#### Descrição

O roteiro de estudos é um guia que orienta os alunos na preparação para as atividades em sala de aula. Este material é disponibilizado pelo professor para auxiliar no estudo do conteúdo teórico em casa, preparando-os para as aulas práticas.

#### Elementos de Gamificação Associados

<div style="text-align: center;">
  <img src="Elementos de gamificação/Desafios.png" alt="Desafios" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Missoes.png" alt="Missões" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Narrativa.png" alt="Narrativa" style="width: 15%;">
</div>

#### Por que Fazer?

O roteiro de estudos é fundamental para que os alunos absorvam o conteúdo teórico e se preparem para as atividades práticas. Ele ajuda a garantir um bom desempenho nas atividades realizadas com base no material estudado.

#### Como Fazer?

O roteiro pode incluir diversos tipos de materiais, como vídeos, leituras e pesquisas. A inclusão de desafios e missões como elementos de gamificação pode motivar os alunos e engajar mais efetivamente no processo de aprendizagem.

#### Exemplos

- **Vídeo aulas**: Fornecem uma introdução visual ao conteúdo.
- **Artigos científicos**: Aprofundam o conhecimento teórico.
- **Capítulos de livros**: Fornecem uma base sólida de informações.
- **Sites**: Oferecem recursos adicionais e atualizados.

### Avaliação Pré-Aula

#### Descrição

A avaliação pré-aula é aplicada antes da aula prática para verificar o conhecimento adquirido pelos alunos com base no roteiro de estudo. Seu objetivo é identificar áreas que precisam de revisão e possibilitar o direcionamento de dúvidas para o professor.

#### Elementos de Gamificação Associados

<div style="text-align: center;">
  <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Feedback.png" alt="Feedback" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 15%;">
</div>

#### Por que Fazer?

A avaliação pré-aula ajuda a identificar lacunas no conhecimento e a preparar os alunos para o que será abordado na aula prática. Além disso, incentiva os alunos a refletirem sobre o que já aprenderam e a prepararem perguntas para a aula.

#### Como Fazer?

Pode ser feita através de questionários online, exercícios práticos ou atividades que promovam a reflexão. Elementos de gamificação, como barras de progresso, pontuação e conquistas, podem proporcionar feedback imediato e motivar os alunos.

#### Exemplos

- **Questionário com questões de múltipla escolha**: Avalia o conhecimento prévio.
- **Feedback visual**: Indica respostas corretas ou incorretas.
- **Conquistas**: Medalhas ou recompensas virtuais para desempenho.

### Atividade Prática

#### Descrição

Atividades práticas realizadas durante as aulas ou encontros com o professor. Estas atividades podem envolver a resolução de problemas, simulações, jogos educativos e quizzes, aplicando o conhecimento adquirido nas etapas anteriores.

#### Elementos de Gamificação Associados

<div style="text-align: center;">
  <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Desafios.png" alt="Desafios" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Competicao.png" alt="Competição" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Equipes.png" alt="Equipes" style="width: 15%;">
</div>

#### Por que Fazer?

As atividades práticas permitem que os alunos apliquem o conhecimento adquirido e recebam feedback imediato. Elas ajudam a identificar áreas de dificuldade e ajustam o material didático conforme necessário.

#### Como Fazer?

O professor deve organizar um encontro após as etapas anteriores, resolver dúvidas e realizar uma atividade prática em grupo. Elementos de gamificação, como pontuação, recompensas, desafios e competições, podem ser incorporados para aumentar o engajamento e a interação entre os alunos.

#### Exemplos

- **Atividades práticas em grupo**: Resolução de problemas e simulações.
- **Competição**: Quizzes ou jogos para estimular a participação.

### Avaliação Pós-Aula

#### Descrição

A avaliação pós-aula é realizada após a aula prática para medir o grau de compreensão e assimilação do conteúdo pelos alunos. Serve para avaliar se os objetivos de aprendizagem foram atingidos.

<div style="text-align: center;">
  <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Badges.png" alt="Badges" style="width: 15%;">
</div>

#### Por que Fazer?

A avaliação pós-aula permite identificar se os objetivos foram alcançados e se é necessário reforçar algum conteúdo. Também oferece uma oportunidade para os alunos revisarem o que aprenderam.

#### Como Fazer?

Pode ser realizada por meio de testes, provas, trabalhos individuais ou em grupo. O uso de elementos de gamificação, como pontuação e badges, pode proporcionar feedback adicional e incentivar a revisão do conteúdo.

#### Exemplos

- **Questionário com questões de múltipla escolha**: Avalia o conhecimento pós-aula.
- **Recompensas e badges**: Reconhece o desempenho e a assimilação do conteúdo.


<a name="frame-3"></a>
### Sistema de gamificação


<a name="frame-4"></a>
### Troca de pontos


## Ferramentas de Apoio

Nesta seção, apresentamos as principais ferramentas que auxiliam na implementação do framework **GamIES**, proporcionando suporte para a gamificação e o planejamento de aulas invertidas. Cada uma dessas plataformas desempenha um papel fundamental na condução das atividades, desde a criação de ambientes gamificados até a coleta e visualização de dados para oferecer feedback contínuo aos alunos.

### Classcraft

[**Classcraft**](https://www.classcraft.com) é uma plataforma de gamificação especialmente projetada para o ambiente educacional. Ela transforma a sala de aula em um jogo de RPG (Role-Playing Game), onde os alunos podem criar avatares personalizados, ganhar pontos de experiência, completar missões e trabalhar em equipes.

No **GamIES**, essa ferramenta é essencial para fornecer um ambiente gamificado em que os alunos percorrem fases usando os roteiros de estudo e as avaliações. As pontuações são atribuídas automaticamente, alinhando-se à experiência gamificada, criando um cenário envolvente que apoia a jornada educacional dos alunos.

### Google Forms

[**Google Forms**](https://www.google.com/forms/about/) é uma ferramenta gratuita e poderosa do Google que permite criar formulários, questionários e pesquisas online com facilidade. Ela é amplamente utilizada em ambientes educacionais para coletar dados, realizar avaliações, e obter feedback de alunos de forma eficiente.

No **GamIES**, o Google Forms é essencial para criar avaliações (avaliação diagnóstica, avaliação pré-aula, e avaliações pós-aula) e roteiros de estudo que compõem as fases da aula invertida. As respostas coletadas são automaticamente organizadas em planilhas do Google Sheets, facilitando a análise dos dados e o acompanhamento do progresso dos alunos.

### Google Data Studio

[**Google Data Studio**](https://marketingplatform.google.com/about/data-studio/) é uma ferramenta de visualização de dados que permite a criação de relatórios e dashboards interativos a partir de várias fontes de dados, como Google Sheets, Google Analytics, entre outras.

No **GamIES**, o Google Data Studio é usado para fornecer feedback visual aos alunos sobre suas pontuações e progresso, permitindo que eles acompanhem sua evolução ao longo das fases de maneira clara e personalizada. Os relatórios criados podem ser facilmente compartilhados, contribuindo para uma melhor compreensão do desempenho individual e coletivo.


### 3. Sistema de Gamificação

O **Sistema de Gamificação** é uma componente essencial do framework GamIES, projetado para aumentar a motivação e o engajamento dos alunos por meio da introdução de elementos lúdicos no processo de aprendizagem. 

Os elementos de gamificação são integrados em cada etapa do ciclo de aprendizagem, com o objetivo de recompensar os alunos pelo desempenho nas tarefas realizadas. O foco principal está na atribuição de pontuações que refletem tanto a participação quanto o engajamento dos alunos ao longo do processo. Assim, os alunos podem ser recompensados pela participação contínua em cada fase do ciclo de aprendizagem. Por exemplo, ao concluir todas as etapas, o aluno recebe uma pontuação de 100 pontos.


Neste ponto, são definidos os critérios de avaliação e validação das atividades realizadas, além das pontuações atribuídas a cada fase, considerando a possibilidade de inclusão ou não dessas pontuações. Também são determinadas as recompensas que podem ser distribuídas, seja em cada fase ou ao final do ciclo de aprendizagem. Os elementos de gamificação empregados em cada etapa podem ser consultados nas subseções dedicadas aos elementos de gamificação associados, descritos para cada fase do ciclo de aprendizagem.


A gamificação do ciclo de aprendizagem inclui a utilização de:

- **Pontuação**: Os alunos acumulam pontos ao completar atividades e atingir metas de aprendizagem, incentivando a competição saudável e a progressão contínua.
- **Recompensas**: Recompensas virtuais, como badges e títulos, são concedidas para reconhecer o esforço e as conquistas dos alunos.
- **Ranking**: Tabelas de classificação que permite visualizar o desempenho relativo dos alunos, estimulando a participação ativa e o engajamento.


### 4. Troca de Pontos

A **Troca de Pontos** é uma funcionalidade que permite aos alunos utilizarem os pontos acumulados no sistema de gamificação para obter recompensas específicas. Essas recompensas podem variar desde vantagens acadêmicas até prêmios simbólicos, proporcionando uma experiência mais envolvente e motivadora. Este mecanismo inclui:

- **Conversão de Pontos**: Os pontos adquiridos podem ser trocados por itens úteis, como dicas extras em avaliações, acesso antecipado a materiais, ou até mesmo benefícios na pontuação final, incentivando os alunos a se empenharem ainda mais em suas atividades.
- 
- **Premios**: Além das vantagens acadêmicas, os alunos podem receber prêmios simbólicos, como certificados de conquista, medalhas digitais, ou itens personalizados. Esses prêmios são projetados para reconhecer e valorizar os esforços e realizações dos alunos, promovendo um ambiente de aprendizado mais dinâmico e recompensador.


Dessa forma, o professor deve estabelecer regras específicas para a troca de pontos e definir os momentos em que essa troca poderá ser realizada. Por exemplo, a cada 100 pontos acumulados, o aluno pode optar por anular uma questão da prova. Também é possível definir quantas vezes essa opção pode ser utilizada.


A troca de pontos promove a autonomia dos alunos, incentivando a autorregulação e a responsabilidade pelo próprio aprendizado, além de reforçar o valor das conquistas obtidas ao longo do curso.


### Contato

O framework GamIES é um projeto desenvolvido como parte de um mestrado, com o objetivo de auxiliar na implementação de aulas invertidas utilizando elementos de gamificação. Para mais informações sobre o projeto, para discutir possíveis colaborações ou para fornecer feedback, entre em contato com o autor através do seguinte e-mail: [elannemendes@alu.ufc.br](mailto:elannemendes@alu.ufc.br). Agradecemos seu interesse e contribuições para o avanço da pesquisa.








### Avaliação Diagnóstica

#### Descrição

A avaliação diagnóstica é uma ferramenta crucial para avaliar o conhecimento prévio dos alunos em relação ao conteúdo a ser abordado. Ela ajuda a identificar áreas de domínio e dificuldades, permitindo ajustes no material didático conforme as necessidades individuais e coletivas dos estudantes.

#### Elementos de Gamificação Associados

<div style="text-align: center;">
  <a href="#game-dig">
    <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 15%; margin-right: 30px;">
    <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 15%;">
  </a>
</div>

#### Por que Fazer?

Realizar uma avaliação diagnóstica é essencial para identificar lacunas no conhecimento dos alunos e adaptar o material de estudo. Além disso, envolve os alunos ativamente no processo de aprendizagem e estimula a reflexão sobre seu conhecimento.

#### Como Fazer?

A avaliação pode ser feita através de testes, questionários ou atividades que proporcionem uma visão geral do conhecimento dos alunos.

Adoção de elementos de gamificação, como **pontuação** e **recompensas**, pode aumentar a motivação dos alunos, criando um ambiente de aprendizagem mais dinâmico e envolvente. Estes elementos incentivam uma competição saudável e o engajamento dos estudantes.

#### Exemplos

- **Questionário com questões objetivas**: Inclui pontuações associadas às respostas.
- **Questionário auto declarativo**: Permite aos alunos avaliar seu próprio conhecimento.

### Roteiro de Estudos

#### Descrição

O roteiro de estudos é um guia que orienta os alunos na preparação para as atividades em sala de aula. Este material é disponibilizado pelo professor para auxiliar no estudo do conteúdo teórico em casa, preparando-os para as aulas práticas.

#### Elementos de Gamificação Associados

<div style="text-align: center;">
  <img src="Elementos de gamificação/Desafios.png" alt="Desafios" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Missoes.png" alt="Missões" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Narrativa.png" alt="Narrativa" style="width: 15%;">
</div>

#### Por que Fazer?

O roteiro de estudos é fundamental para que os alunos absorvam o conteúdo teórico e se preparem para as atividades práticas. Ele ajuda a garantir um bom desempenho nas atividades realizadas com base no material estudado.

#### Como Fazer?

O roteiro pode incluir diversos tipos de materiais, como vídeos, leituras e pesquisas. A inclusão de desafios e missões como elementos de gamificação pode motivar os alunos e engajar mais efetivamente no processo de aprendizagem.

#### Exemplos

- **Vídeo aulas**: Fornecem uma introdução visual ao conteúdo.
- **Artigos científicos**: Aprofundam o conhecimento teórico.
- **Capítulos de livros**: Fornecem uma base sólida de informações.
- **Sites**: Oferecem recursos adicionais e atualizados.

### Avaliação Pré-Aula

#### Descrição

A avaliação pré-aula é aplicada antes da aula prática para verificar o conhecimento adquirido pelos alunos com base no roteiro de estudo. Seu objetivo é identificar áreas que precisam de revisão e possibilitar o direcionamento de dúvidas para o professor.

#### Elementos de Gamificação Associados

<div style="text-align: center;">
  <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Feedback.png" alt="Feedback" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 15%;">
</div>

#### Por que Fazer?

A avaliação pré-aula ajuda a identificar lacunas no conhecimento e a preparar os alunos para o que será abordado na aula prática. Além disso, incentiva os alunos a refletirem sobre o que já aprenderam e a prepararem perguntas para a aula.

#### Como Fazer?

Pode ser feita através de questionários online, exercícios práticos ou atividades que promovam a reflexão. Elementos de gamificação, como barras de progresso, pontuação e conquistas, podem proporcionar feedback imediato e motivar os alunos.

#### Exemplos

- **Questionário com questões de múltipla escolha**: Avalia o conhecimento prévio.
- **Feedback visual**: Indica respostas corretas ou incorretas.
- **Conquistas**: Medalhas ou recompensas virtuais para desempenho.

### Atividade Prática

#### Descrição

Atividades práticas realizadas durante as aulas ou encontros com o professor. Estas atividades podem envolver a resolução de problemas, simulações, jogos educativos e quizzes, aplicando o conhecimento adquirido nas etapas anteriores.

#### Elementos de Gamificação Associados

<div style="text-align: center;">
  <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Desafios.png" alt="Desafios" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Competicao.png" alt="Competição" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Equipes.png" alt="Equipes" style="width: 15%;">
</div>

#### Por que Fazer?

As atividades práticas permitem que os alunos apliquem o conhecimento adquirido e recebam feedback imediato. Elas ajudam a identificar áreas de dificuldade e ajustam o material didático conforme necessário.

#### Como Fazer?

O professor deve organizar um encontro após as etapas anteriores, resolver dúvidas e realizar uma atividade prática em grupo. Elementos de gamificação, como pontuação, recompensas, desafios e competições, podem ser incorporados para aumentar o engajamento e a interação entre os alunos.

#### Exemplos

- **Atividades práticas em grupo**: Resolução de problemas e simulações.
- **Competição**: Quizzes ou jogos para estimular a participação.

### Avaliação Pós-Aula

#### Descrição

A avaliação pós-aula é realizada após a aula prática para medir o grau de compreensão e assimilação do conteúdo pelos alunos. Serve para avaliar se os objetivos de aprendizagem foram atingidos.

<div style="text-align: center;">
  <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 15%; margin-right: 30px;">
  <img src="Elementos de gamificação/Badges.png" alt="Badges" style="width: 15%;">
</div>

#### Por que Fazer?

A avaliação pós-aula permite identificar se os objetivos foram alcançados e se é necessário reforçar algum conteúdo. Também oferece uma oportunidade para os alunos revisarem o que aprenderam.

#### Como Fazer?

Pode ser realizada por meio de testes, provas, trabalhos individuais ou em grupo. O uso de elementos de gamificação, como pontuação e badges, pode proporcionar feedback adicional e incentivar a revisão do conteúdo.

#### Exemplos

- **Questionário com questões de múltipla escolha**: Avalia o conhecimento pós-aula.
- **Recompensas e badges**: Reconhece o desempenho e a assimilação do conteúdo.

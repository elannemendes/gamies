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

- **Elaboração do Material**: O material didático deve ser preparado de acordo com os tópicos definidos, garantindo que todos os recursos necessários para o aprendizado estejam disponíveis. Para isso, o professor deve seguir as instruções do [Ciclo de Aprendizagem](#ciclo-de-aprendizagem), que descrevem em detalhes cada material e orientam sua elaboração.

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

Com a avaliação diagnóstica é possível identificar lacunas de aprendizado e ajustar o material de estudo de acordo com as necessidades individuais e coletivas dos estudantes. Além disso, também é uma oportunidade para que os estudantes se envolvam ativamente no processo de aprendizagem e reflitam sobre seus conhecimentos.

#### Como Fazer?

Geralmente, é realizada por meio de testes, questionários ou atividades que possibilitam ao professor ter um panorama sobre o nível de conhecimento do aluno.

<a name="game-dig"></a>
Adoção de elementos de Gamificação, como **pontuação** e **recompensas**, para incentivar os estudantes a se empenharem mais no estudo, criando um ambiente divertido e desafiador. A competição saudável entre os estudantes também pode aumentar a motivação e o engajamento na aprendizagem.

Nesta etapa do ciclo de aprendizagem, é recomendado utilizar **recompensas** exclusivamente para reconhecer a participação ou o engajamento dos alunos. A **pontuação** deve ser empregada unicamente para monitorar o progresso dos alunos ao longo do processo de aprendizagem.

Em uma abordagem de ensino adaptativa, em que o conteúdo do material de estudos pode ser personalizado, é possível fazer ajustes no material, focando nas áreas que precisam ser aprimoradas e explorando assuntos que o estudante não possui um nível de conhecimento elevado.

#### Exemplos

- [**Questionário com questões objetivas**](https://forms.gle/MaAK6jHv2FkN35SM7): Inclui pontuações associadas às respostas.
- **Questionário auto declarativo**: Permite aos alunos avaliar seu próprio conhecimento.


### Roteiro de Estudos

#### Descrição

Atua como um guia para os alunos durante a preparação para as atividades em sala de aula. Este material, fornecido pelo professor, tem o objetivo de apoiar o estudo do conteúdo teórico em casa, preparando os alunos para as atividades práticas a ser realizadas na sala de aula.

#### Elementos de gamificação associados

<div style="display: flex; justify-content: space-between;">
  <a href="#des-miss-rot">
    <img src="Elementos de gamificação/Desafios.png" alt="Desafios" style="width: 12%; margin-right: 60px; pointer-events: none;">
    <img src="Elementos de gamificação/Missoes.png" alt="Missões" style="width: 12%; pointer-events: none;">
  </a>
  <a href="#narr-rot">
    <img src="Elementos de gamificação/Narrativa.png" alt="Narrativa" style="width: 12%; pointer-events: none;">
  </a>
</div>

#### Por que Fazer?

Para que os alunos possam estudar o conteúdo abordado e se preparar para as atividades práticas em sala de aula. Esse momento é importante para que os alunos aprendam a parte teórica do conteúdo ministrado e consiga ter um bom desempenho nas atividades que serão realizadas com base no conteúdo estudado.

#### Como Fazer?

O roteiro pode incluir diversos tipos de materiais, como vídeos, materiais para leitura, realização de pesquisas, entre outras atividades, com o objetivo de facilitar a aprendizagem e direcionar o estudo dos estudantes.

<a name="des-miss-rot"></a>
A inclusão de elementos de gamificação, como **desafios** e **missões**, pode aumentar a motivação dos alunos e promover um engajamento mais eficaz no processo de aprendizagem.

<a name="narr-rot"></a>
Outra possibilidade é a utilização de **narrativa**. Incorporar narrativa no roteiro de estudos pode enriquecer a experiência de aprendizagem ao oferecer contextos envolventes e relevantes para o conteúdo. Essa abordagem facilita a criação de uma conexão emocional com o material, tornando o aprendizado mais significativo e memorável.

Além disso, elementos relacionados à progressão, como barras de **progresso** ou **sistemas de níveis**, podem ser utilizados para monitorar o avanço dos alunos e incentivar a continuidade do estudo.

#### Exemplos

- **Vídeo aulas**: Fornecem uma introdução visual ao conteúdo.
- **Artigos científicos**: Aprofundam o conhecimento teórico.
- **Capítulos de livros**: Fornecem uma base sólida de informações.
- **Sites**: Oferecem recursos adicionais e atualizados.

O roteiro de estudos pode incluir um ou mais dos itens listados acima. Veja um exemplo de [roteiro de estudos](https://forms.gle/Q7anb8BdcyZF8uMP7) sobre Requisitos de Software. Este roteiro, criado no Google Forms, integra a abordagem de sala de aula invertida com elementos de gamificação, aplicados ao conteúdo de Engenharia de Requisitos na disciplina de Engenharia de Software.


### Avaliação Pré-Aula

#### Descrição

Instrumento de avaliação que deve ser aplicado antes da aula prática, com o propósito de verificar o conhecimento adquirido pelos alunos com base no roteiro de estudo disponibilizado pelo professor.

#### Elementos de gamificação associados

<div style="display: flex; justify-content: space-between;">
  <a href="#pont-pre">
    <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 12%; margin-right: 60px; pointer-events: none;">
  </a>
  <a href="#feed-pre">
    <img src="Elementos de gamificação/Feedback.png" alt="Feedback" style="width: 12%; pointer-events: none;">
  </a>
  <a href="#rec-pre">
    <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 12%; pointer-events: none;">
  </a>
</div>

#### Por que Fazer?

O objetivo da avaliação pré-aula é identificar as lacunas do conhecimento do aluno e orientá-lo sobre quais tópicos precisam ser revistos ou reforçados durante o estudo. Além disso, essa avaliação também é importante para que o aluno formule dúvidas relacionadas ao assunto que podem ser direcionadas ao professor durante o momento em sala de aula.

#### Como Fazer?

Pode ser feita por meio de um questionário online, com questões de múltipla escolha, ou atividade que estimule a reflexão sobre o assunto.

<a name="pont-pre"></a>
Em questionários online, uma alternativa de gamificação é a implementação de uma **barra de progresso** ou **atribuição de pontuações** que demonstre o desempenho do estudante enquanto ele responde às questões. À medida que o usuário acerta as perguntas, a barra de progresso aumenta ou a pontuação vai aumentando, demonstrando um feedback positivo. Caso o aluno responda incorretamente, a barra de progresso pode não avançar ou a pontuação pode permanecer inalterada, fornecendo um feedback negativo e incentivando o usuário a melhorar seu desempenho. 

<a name="rec-pre"></a>
Outra possibilidade é a utilização de **conquistas** ou **medalhas**. Ao alcançar certos marcos, como acertar um número específico de perguntas, o aluno pode receber uma medalha ou conquista que será exibida em seu perfil ou em um placar. Essas recompensas virtuais servem como motivação adicional para que o aluno continue participando.

<a name="feed-pre"></a>
Além disso, é recomendável usar elementos visuais para fornecer **feedback** imediato. Quando o aluno responder corretamente uma questão, a resposta pode ser destacada em verde, acompanhada de uma animação positiva. Em contrapartida, respostas incorretas podem ser destacadas em vermelho, acompanhadas de uma animação que sinaliza o erro, facilitando a identificação.

#### Exemplos

- [**Questionário com questões de múltipla escolha**](https://forms.gle/sx8cLX2wxaMNmGfw8): Avalia o conhecimento adquirido.
- **Feedback visual**: Indica respostas corretas ou incorretas.
- **Conquistas**: Medalhas ou recompensas virtuais para desempenho.
  


### Atividade Prática

#### Descrição

Atividades práticas realizadas na sala de aula ou no encontro da turma com o professor. Essas atividades podem envolver a resolução de problemas, simulações, jogos educacionais, quizzes, entre outras atividades relacionadas ao assunto abordado nos materiais disponibilizados anteriormente.

#### Elementos de gamificação associados

<div style="display: flex; justify-content: space-between;">
  <a href="#game-pratica">
    <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 12%; margin-right: 60px; pointer-events: ;">
    <img src="Elementos de gamificação/Desafios.png" alt="Desafios" style="width: 12%; pointer-events: none;">
    <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 12%; pointer-events: none;">
    <img src="Elementos de gamificação/Competicao.png" alt="Competição" style="width: 12%; pointer-events: none;">
    <img src="Elementos de gamificação/Equipes.png" alt="Equipes" style="width: 12%; pointer-events: none;">
  </a> 
</div>

#### Por que Fazer?

Para que os alunos possam exercitar o conhecimento adquirido durante os estudos em casa. Durante este momento, o professor também pode responder às dúvidas dos alunos e avaliar o nível de compreensão da turma e ajustar suas explicações de acordo com as necessidades dos alunos.

#### Como Fazer?

O professor(a) deve marcar um encontro com a turma a ser realizado após a conclusão das etapas anteriores. No primeiro momento, o professor pode aproveitar para sanar dúvidas dos alunos com relação ao conteúdo abordado. Em seguida, deve ser realizada uma atividade prática em grupo sobre o assunto abordado. A atividade fica a critério do professor, e esta deve ser planejada antes do encontro com a turma.

Para promover a participação e melhor interação entre os alunos, alguns elementos de gamificação podem ser incluídos na atividade, como:

<a name="game-pratica"></a>
- **Pontuação**: Pontuar as atividades realizadas pelos alunos, criando um ranking ou tabela de classificação.
- **Recompensas**: Oferecer recompensas aos alunos que alcançarem determinados objetivos ou atingirem um número específico de pontos.
- **Desafios**: Propor desafios aos alunos, incentivando-os a resolver problemas utilizando o conhecimento adquirido.
- **Competições**: Promover competições em sala de aula, como quizzes ou jogos, estimulando a participação e a colaboração entre os alunos.
- **Premiações**: Premiar os alunos com melhores desempenhos ou que mais se destacarem durante as atividades gamificadas.


#### Exemplos

- **Atividades práticas em grupo**: Resolução de problemas e simulações.

Um exemplo de atividade prática relacionada ao conteúdo de Requisitos é a **Classificação de Requisitos**. Esta atividade prática pode ser realizada em grupo. Na atividade, os alunos receberam cartas contendo Requisitos Funcionais, Não Funcionais e Regras de Negócio e são desafiados a classificá-los em uma das três categorias. As cartas foram retiradas de um jogo desenvolvido em um Trabalho de Conclusão de Curso, disponível no [Repositório UFC](http://repositorio.ufc.br/handle/riufc/58824).

- **Competição**: Quizzes ou jogos para estimular a participação.

Um ótimo exemplo de atividades práticas são os quizzes. A ferramenta [**Quizzizz**](https://quizizz.com) é altamente recomendada para essa finalidade, pois permite criar quizzes interativos e envolventes que podem ser utilizados para revisar conteúdos, avaliar o aprendizado e promover a competição saudável entre os alunos. O Quizzizz oferece uma variedade de recursos, como questões com múltipla escolha, feedback instantâneo e opções de personalização, além de disponibilizar diversos quizzes prontos sobre diferentes assuntos.

### Avaliação Pós-Aula

#### Descrição

Instrumento de avaliação que deve ser aplicado após a realização da aula prática para medir o grau de compreensão e assimilação do conteúdo pelos alunos. Serve para avaliar se os objetivos de aprendizagem foram atingidos.

<div style="display: flex; justify-content: space-between;">
   <a ref="pont-pos">
    <img src="Elementos de gamificação/Pontuacao.png" alt="Pontuação" style="width: 12%; margin-right: 60px; pointer-events: none;">
    <img src="Elementos de gamificação/Recompensas.png" alt="Recompensas" style="width: 12%; pointer-events: none;">
  </a>
  <a ref="badges-pos">
    <img src="Elementos de gamificação/Badges.png" alt="Badges" style="width: 12%; pointer-events: none;">
  </a>
</div>

#### Por que Fazer?

A avaliação pós-aula permite ao professor identificar se os objetivos de aprendizagem foram alcançados e se é necessário reforçar algum conteúdo. Também oferece aos alunos a oportunidade de revisar o conteúdo aprendido.

#### Como Fazer?

Pode ser feita por meio de testes, trabalhos individuais ou em grupo, apresentações orais, entre outros. 

<a name="pont-pos"></a>
Incorporar elementos de gamificação, como **pontuação** e **recompensas**, pode motivar os estudantes a se dedicarem mais ao estudo e a participarem ativamente das atividades práticas, visando um bom desempenho no pós-aula. 

<a name="badges-pos"></a>
Os alunos podem ser recompensados com **badges** de acordo com o desempenho e as notas obtidas ao responder o questionário. A pontuação necessária para ganhar esses badges pode ser previamente estabelecida no [Sistema de Gamificação](3-sistema-de-gamificacao).


#### Exemplos

- [**Questionário com questões de múltipla escolha**](https://forms.gle/jhAoYbatZgHnVojD9): Avalia o conhecimento pós-aula.
- **Recompensas e badges**: Reconhece o desempenho e a assimilação do conteúdo.

Exemplos de badges de personalidade da Engeharia de Software utilizados no conteúdo de Engenharia de Requisitos:

<div style="display: flex; justify-content: space-between;">
  <a ref=""></a>
    <img src="Badges/1.png" alt="1" style="width: 15%; margin-right: 150px; pointer-events: none;">
    <img src="Badges/2.png" alt="2" style="width: 15%; margin-right: 150px; pointer-events: none;">
    <img src="Badges/3.png" alt="3" style="width: 15%; margin-right: 150px; pointer-events: none;">
    <img src="Badges/4.png" alt="4" style="width: 15%; pointer-events: none;">
  </a>
</div>

<a name="frame-3"></a>
### 3. Sistema de Gamificação

O **Sistema de Gamificação** é uma componente essencial do framework GamIES, projetado para aumentar a motivação e o engajamento dos alunos por meio da introdução de elementos lúdicos no processo de aprendizagem. 

Os elementos de gamificação são integrados em cada etapa do ciclo de aprendizagem, com o objetivo de recompensar os alunos pelo desempenho nas tarefas realizadas. O foco principal está na atribuição de pontuações que refletem tanto a participação quanto o engajamento dos alunos ao longo do processo. Assim, os alunos podem ser recompensados pela participação contínua em cada fase do ciclo de aprendizagem. Por exemplo, ao concluir todas as etapas, o aluno recebe uma pontuação de 100 pontos.


Neste ponto, são definidos os critérios de avaliação e validação das atividades realizadas, além das pontuações atribuídas a cada fase, considerando a possibilidade de inclusão ou não dessas pontuações. Também são determinadas as recompensas que podem ser distribuídas, seja em cada fase ou ao final do ciclo de aprendizagem. Os elementos de gamificação empregados em cada etapa podem ser consultados nas subseções dedicadas aos elementos de gamificação associados, descritos para cada fase do ciclo de aprendizagem.


A gamificação do ciclo de aprendizagem inclui a utilização de:

- **Pontuação**: Os alunos acumulam pontos ao completar atividades e atingir metas de aprendizagem, incentivando a competição saudável e a progressão contínua.
- **Recompensas**: Recompensas virtuais, como badges e títulos, são concedidas para reconhecer o esforço e as conquistas dos alunos.
- **Ranking**: Tabelas de classificação que permite visualizar o desempenho relativo dos alunos, estimulando a participação ativa e o engajamento.


<a name="frame-4"></a>
### 4. Troca de Pontos

A **Troca de Pontos** é uma funcionalidade que permite aos alunos utilizarem os pontos acumulados no sistema de gamificação para obter recompensas específicas. Essas recompensas podem variar desde vantagens acadêmicas até prêmios simbólicos, proporcionando uma experiência mais envolvente e motivadora. Este mecanismo inclui:

- **Conversão de Pontos**: Os pontos adquiridos podem ser trocados por itens úteis, como dicas extras em avaliações, acesso antecipado a materiais, ou até mesmo benefícios na pontuação final, incentivando os alunos a se empenharem ainda mais em suas atividades.
- **Premios**: Além das vantagens acadêmicas, os alunos podem receber prêmios simbólicos, como certificados de conquista, medalhas digitais, ou itens personalizados. Esses prêmios são projetados para reconhecer e valorizar os esforços e realizações dos alunos, promovendo um ambiente de aprendizado mais dinâmico e recompensador.


Dessa forma, o professor deve estabelecer regras específicas para a troca de pontos e definir os momentos em que essa troca poderá ser realizada. Por exemplo, a cada 100 pontos acumulados, o aluno pode optar por anular uma questão da prova. Também é possível definir quantas vezes essa opção pode ser utilizada.


A troca de pontos promove a autonomia dos alunos, incentivando a autorregulação e a responsabilidade pelo próprio aprendizado, além de reforçar o valor das conquistas obtidas ao longo do curso.



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



### Contato

O framework GamIES é um projeto desenvolvido como parte de um mestrado, com o objetivo de auxiliar na implementação de aulas invertidas utilizando elementos de gamificação. Para mais informações sobre o projeto, para discutir possíveis colaborações ou para fornecer feedback, entre em contato com o autor através do seguinte e-mail: [elannemendes@alu.ufc.br](mailto:elannemendes@alu.ufc.br). Agradecemos seu interesse e contribuições para o avanço da pesquisa.

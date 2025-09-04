# **Nome do Robô:** Aplicação do robô

Trabalho de Interação Humano-Robô (IHR) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interação Humano-Robô (IHR) (CCR230) do curso de Engenharia de Robôs, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo

- Thomas Ay Casa Grande
- Rafael Felix Rovina
- Enzo Figari Guillaumon
- Enzo Rodrigues Tofoli
- Gustavo Rodrigues Santos
- Matheus Kenji 

## Pensamentos - plateia - personas (apresentadores e plateia) - vai ter uma camera global e vai ter microfone para comunicação verbal (barulho de rato?)


## Resumo

O projeto propõe a utilização de um robô Micromouse adaptado para fins de interação humano-robô (IHR). Tradicionalmente desenvolvido para resolver labirintos em competições, o Micromouse neste contexto assume uma função lúdica e educativa, aproximando o público dos conceitos de robótica e automação. A aplicação contará com uma câmera global, responsável por acompanhar os movimentos do robô e transmitir sua visão em tempo real para a plateia, além de um sistema de áudio que permitirá tanto a emissão de sons característicos de um rato (guinchos ou ruídos curtos), quanto a recepção de estímulos verbais ou sonoros da plateia. Dessa forma, o robô torna-se capaz de interagir diretamente com o público, reforçando a proposta de engajamento.

A dinâmica da apresentação envolve duas personas principais: os apresentadores, responsáveis por conduzir a explicação técnica e contextualizar o funcionamento do robô, e a plateia, que poderá interagir por meio de comandos simples ou estímulos sonoros. Essa configuração transforma o Micromouse em uma ferramenta de demonstração participativa, ampliando seu valor além da competição tradicional.

Em termos construtivos, o robô possui uma estrutura mecânica compacta e leve, adequada para movimentos ágeis em espaços delimitados. Seu sistema de locomoção diferencial, composto por dois motores independentes, garante precisão no deslocamento e nas curvas. O robô também é equipado com sensores de proximidade para identificar obstáculos, um módulo de processamento embarcado para controle de movimento e interpretação de dados, além da interface de interação formada por microfone e atuadores sonoros. Esses elementos garantem não apenas a execução de tarefas de navegação, mas também a capacidade de comunicação e resposta a estímulos externos.

Assim, o Micromouse deixa de ser apenas um robô de exploração de labirintos e se apresenta como uma plataforma interativa, educativa e envolvente, promovendo maior aproximação entre tecnologia, ciência e sociedade.

## Introdução

A interação humano-robô (IHR) vem se consolidando como um campo fundamental no desenvolvimento de tecnologias voltadas não apenas para a automação de tarefas, mas também para a comunicação, educação e engajamento social. Em um contexto onde a robótica está cada vez mais presente no cotidiano, é essencial criar soluções que despertem o interesse do público em geral, promovendo a compreensão de conceitos técnicos de forma acessível e lúdica. Nesse sentido, robôs que interagem diretamente com pessoas tornam-se ferramentas valiosas para divulgação científica, ensino de tecnologia e aproximação entre sociedade e inovação.

O robô desenvolvido neste projeto é baseado no conceito do Micromouse, tradicionalmente utilizado em competições de exploração de labirintos. Contudo, sua aplicação foi adaptada para um contexto interativo, no qual ele se torna uma plataforma de demonstração capaz de se comunicar com o público. O robô conta com locomoção autônoma em ambientes delimitados, sensores de proximidade para detecção de obstáculos, uma câmera global para acompanhamento de seus movimentos e um sistema de áudio que possibilita tanto a emissão de sons característicos de um rato quanto a recepção de estímulos verbais ou sonoros. Dessa forma, ele transforma uma aplicação originalmente competitiva em uma experiência educativa e envolvente.

O objetivo central do robô é: proporcionar uma experiência interativa e lúdica que aproxime o público da robótica por meio da exploração autônoma e da comunicação sonora.

Para os usuários, a experiência oferecida deve ser de curiosidade, engajamento e aprendizado prático, despertando interesse em tecnologia e ciência através de uma interação divertida, acessível e memorável.
## Publico Alvo

- Determine o seu público alvo: Plateia e Apresentador 

### Personas

*Persona Primária – Integrante da Plateia*

*O que o usuário vê*

* Um auditório ou espaço de apresentação.
* O robô micromouse se movimentando de forma demonstrativa.
* Os apresentadores conduzindo a atividade.
* Outros espectadores reagindo com entusiasmo, curiosidade ou distração.
* A câmera global transmitindo a visão geral em uma tela.

*O que o usuário ouve*

* A voz dos apresentadores explicando o funcionamento do robô.
* Reações da plateia (risadas, comentários, aplausos).
* Sons do robô: motores, rodinhas e eventualmente efeitos sonoros (como barulho de rato).
* Sons ambiente do auditório.

*O que o usuário diz e faz*

* Comenta com colegas ao lado (“Nossa, ele é rápido!”, “Será que vai fazer mais alguma coisa?”).
* Ri ou reage às falhas/diversões.
* Usa o celular para filmar/fotografar o robô.
* Acompanha atentamente a demonstração.

*O que o usuário pensa e sente*

* Curiosidade sobre como o robô funciona.
* Surpresa e expectativa a cada movimento.
* Desejo de se divertir com a experiência.
* Admiração pela tecnologia aplicada em algo lúdico.
* Sente-se engajado quando há interação direta (perguntas, brincadeiras, sons).

*Dores*

* Pode se sentir entediada se a apresentação for lenta ou pouco envolvente.
* Dificuldade de enxergar/acompanhar se não houver boa visibilidade.
* Frustração caso o robô não funcione bem (travando, não respondendo).

*Ganhos*

* Experiência divertida e memorável.
* Aprende de forma leve sobre robótica.
* Satisfação em ver o robô funcionando corretamente.
* Entretenimento coletivo (dividir reações com os outros).



*Persona Secundária - Apresentador*

*O que o usuário vê*

* O público observando e reagindo.
* O micromouse em funcionamento demonstrativo.
* Os colegas apresentadores ajudando na condução.
* A câmera global e o microfone captando a cena.

*O que o usuário ouve*

* Murmúrios, risadas e comentários da plateia.
* Sons do robô (movimento, barulho de rato se houver).
* Feedback de colegas (sussurros, instruções rápidas).
* O retorno do próprio microfone.

*O que o usuário diz e faz*

* Explica o funcionamento do robô de forma clara.
* Faz piadas ou comentários para engajar a plateia.
* Incentiva o público a prestar atenção ou reagir.
* Coordena o início da demonstração.
* Responde perguntas feitas pelo público.

*O que o usuário pensa e sente*

* Ansiedade em manter a apresentação interessante.
* Orgulho em mostrar o projeto funcionando.
* Preocupação com possíveis falhas do robô.
* Confiança crescente à medida que percebe a reação positiva da plateia.

*Dores*

* Estresse caso o robô apresente erros ou pare de funcionar.
* Dificuldade em prender a atenção do público por muito tempo.
* Preocupação em transmitir informações técnicas de forma acessível.

*Ganhos*

* Satisfação ao ver o público engajado.
* Reconhecimento pelo esforço e dedicação ao projeto.
* Orgulho em apresentar algo inovador de forma lúdica.
* Experiência em comunicação e interação humano-robô.

### Mapa de empatia

![Mapa de empatia](empatia.png)

- Determine o mapa de empatia[^1] de pelo menos uma persona primária e uma sercundária.
  - O que o usuário vê: aqui estamos falando do ambiente visual em que o usuário se encontra. Ou seja, o que ele efetivamente enxerga, as pessoas e objetos que estão ao seu redor. Isso ajuda a entender o contexto em que o usuário está inserido e as influências visuais que está recebendo.
  - O que o usuário ouve: neste quadrante, buscamos entender o que o usuário está ouvindo, os sons que o cercam e como eles influenciam suas ações.
  - O que o usuário diz e faz: aqui consideramos ações e comportamentos que o usuário apresenta durante sua interação com o robô.
  - O que o usuário pensa e sente: neste quadrante, buscamos entender os pensamentos, sentimentos, emoções e percepções que o usuário tem em relação robô. Quais expectativas o usuário cria sobre o robô?
  Que tipo de robô mais agrada essa persona?
  - Dores: quando falamos sobre dores do usuário, estamos fazendo referência a quaisquer obstáculos, necessidades ou frustrações que o usuário possa experimentar ao tentar realizar uma tarefa ou alcançar um objetivo. Isso inclui, por exemplo, problemas de usabilidade, dificuldades de acesso ou outros desafios que podem afetar a experiência do usuário.
  - Ganhos: nesse caso estamos falando de quaisquer benefícios ou recompensas que o usuário possa experimentar ao utilizar o robô. Isso pode incluir economia de tempo ou facilidade de uso, por exemplo. Que desejos do usuário o robô satisfaz?

## Contexto de uso

O robô será utilizado em ambientes de apresentação e demonstração, como feiras de ciência, eventos acadêmicos, salas de aula e atividades de divulgação tecnológica. Nesses espaços, a interação entre pessoas e robôs desempenha um papel fundamental para despertar a curiosidade do público e aproximar conceitos complexos de robótica de forma prática e divertida. O ambiente é projetado de maneira controlada, geralmente com um espaço delimitado semelhante a um pequeno labirinto ou arena, onde o Micromouse pode se movimentar com segurança.

O contexto social, econômico e cultural está fortemente associado à popularização da tecnologia e da robótica como ferramentas de aprendizado. Em um cenário em que a sociedade busca constantemente soluções inovadoras, o robô cumpre uma função educativa, estimulando o interesse de crianças, jovens e adultos em ciência, engenharia e programação. Do ponto de vista cultural, sua aplicação promove a democratização do acesso ao conhecimento tecnológico, permitindo que diferentes perfis de público tenham contato direto com conceitos de automação de forma lúdica e acessível. Do ponto de vista econômico, iniciativas como essa contribuem para formar futuros profissionais capacitados em áreas de alta demanda, como tecnologia e inovação.

Antes de iniciar a tarefa, o robô deve possuir informações básicas sobre o ambiente, incluindo:

Delimitação da área de atuação, evitando ultrapassar limites de segurança.

Posição inicial de onde será iniciado o percurso.

Presença e disposição de obstáculos que possam interferir na navegação.

Condições de iluminação e captação sonora, garantindo que a câmera global e o microfone funcionem adequadamente durante a interação.

Com esses elementos, o robô consegue realizar sua função de forma autônoma e interativa, proporcionando ao público uma experiência segura e envolvente.

## Jornada do usuário

- Criar uma narrativa para o o seu robô e o usuário.
- Determine o passo a passo que o usuário realiza desde o primeiro até o último encontro com robô na realização da tarefa.
- O que está acontecendo com o ambiente quando o robô está interagindo com o usuário?
  - Descreva o que acontece ou pode acontecer passo a passo
  - Como a tarefa começa? Como a tarefa evolui? Como a tarefa termina?
- Enfatize todos os momentos em que acontece uma interação verbal, não-verbal e espacial.

## Análise de concorrência

- Pesquise robôs existentes atualmente que possam fazer a tarefa deste projeto.
- Selecione pelo menos 3 robôs diferentes que podem fazer essa tarefa.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Quais plataformas sua equipe acha mais interessantes? Qual a justificativa?

## Design

- Pense nas características de Affordances do seu robô. Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto de um robô. Qual a importância e pontos a serem considerados se você quiser vender esse robô  seu robô?
- O seu robô tem um padrão com mais ou menos características antropomórficas? Qual padrão é mais aceito pela sociedade dentro do projeto que você está desenvolvendo?
- Quais o design mais apropriado para o robô deste projeto? Modele o seu robô com desenhos de formas primitivas (caixas, cilindros, esferas)

<!-- ![Partes do robô](partes_do_robo.png) -->
<!-- ![Robô](robo.png) -->
<img alt="Partes do robô" src="partes_do_robo.png" height="200"/>
<img alt="Robô" src="robo.png" height="200"/>

## Ações do robô

- Para cada ação:
  - Descreva a ação.
  - Determine os pré-requisitos para que a ação aconteça
  - Determine o que se espera que seja modificado no ambiente quando a ação é finalizada

## Interações do robô

### Espacial

- Para cada interação:
  - Descreva a interação.
  - Determine os pré-requisitos para que a interação aconteça
  - Determine espera de resposta emocional do usúario quando a interação é finalizada

### Verbal

- Para cada interação:
  - Descreva a interação.
  - Determine os pré-requisitos para que a interação aconteça
  - Determine espera de resposta emocional do usúario quando a interação é finalizada

### Não-verbal

- Para cada interação:
  - Descreva a interação.
  - Determine os pré-requisitos para que a interação aconteça
  - Determine espera de resposta emocional do usúario quando a interação é finalizada

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->

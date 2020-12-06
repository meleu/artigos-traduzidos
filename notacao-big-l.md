# Notação Big L

---

Artigo original: <https://www.swyx.io/big-l-notation/>\
Traduzido por [meleu](https://github.com/meleu)

---

Neste post eu esboço a notação `Big L`, que representa seu aprendizado em função deo `N` anos com `P` parceiros.

se você é um [aprendiz infinito](aprendiz-infinito.md)/contínuo, você quer obter o máximo do tempo dedicado ao aprendizado. Quais são os determinantes e o quanto você aprende com o tempo?

No estudo formal de algoritmos, a notação [Big O](https://pt.wikipedia.org/wiki/Grande-O) é frequentemente usada para afirmar sucintamente como os custos aumentam em função da quantidade de trabalho para fazer. Eu acredito que também podemos usar essa notação para falar sobre diferentes formas de aprendizado com o tempo.

Big O é útil pois permite engenheiros conversarem em termos ordem de magnitude (o que é mais importante para decisões de arquitetura) ao invés de se preocupar com minúcias (que são difíceis de predizer e não importam em escala).

Neste post eu esboço a notação `Big L`, que representa seu aprendizado em função deo `N` anos com `P` parceiros. Observe que enquanto o `Big O` é uma curva de custo (quanto mais alto é pior), `Big L` é uma curva de benefício (quanto mais alto é melhor).

![]()


## Aprendendo em Privado

### L(1) - O Pônei de Um Truque

Essa pessoa aprende uma coisa e escolhe fazer isso repetidamente pelo resto da sua carreira. Você pode considerar trabalhos como operador de empilhadeira, ou motorista de longos percursos, ou motorista de táxi, ou arquivador de [relatórios TPS](https://en.wikipedia.org/wiki/TPS_report) como compatíveis com isso, mas também pode obter atitudes `L(1)` em trabalhos de alta variação, como ensino de programação. Suas competências não aumentam notavelmente com os anos de experiência.

**Você conhece pessoas assim.** Eles podem estar presos em uma rotina devido a circunstâncias infelizes, mas também devido a limitações na ambição pessoal.

### L(log N) - O Aprendiz Com Perdas

A função de aprendizado dessa pessoa possui perdas - ele aprende coisas e esquece coisas e precisa reaprendê-las novamente, re-cometer os erros cometidos. eles não têm curiosidade - aprendem relativamente como resultado de eventos distribuídos aleatoriamente, em vez de terem um objetivo de aprendizagem autodirigido.

**Esse é o aprendiz normal.**

### L(N) - O Aprendiz Infinito

Esta pessoa aprende algo novo todo ano e mantem o aprendizado. Errors não são repetidos. Esso requer constantemente ultrapassar os limites e construir um sistema ([princípios](https://www.principles.com/), [hábitos](https://jamesclear.com/habits) ou um [segundo cérebro](https://www.buildingasecondbrain.com/)) para as coisas que a mente humana naturalmente esquece.

**Esta é a ideia que maioria das pessoas faz de um aprendiz ideal.**


### L(N^2) - O Aprendiz Profundo

Isso pode não ser um objetivo realista para um humano alcançar, mas é um experimento interessante a se pensar. O que é necessário para que alguém escale *mais rápido* quanto mais anos de experiência ele tem em algo?

Eu concordo com a [divisão largura vs profundidade proposta pelo Preet](https://twitter.com/preetster/status/1226768072343638021). Você pode ser difuso nos seus esforços, ou você pode concentrar seus esforços todo dia construindo no que você fez no dia anterior. Dê um passo em direção a cada um dos 360 graus e ainda esteja no mesmo ponto, ou dê 360 passos em uma direção para chegar até os lugares.

A escolha pode parecer óbvia, mas se você for 360 passos na direção *errada* isso pode ser um desperdício de tempo. É por isso que eu escolho o term neutro [Marchas de Aprendizagem](marchas-de-aprendizagem.md) para os diferentes modos de aprendizagem.

Eu acho que para a verdadeira aprendizagem `L(N^2)`, alguma introspecção também precisa ser feita. Você deve olhar par os seus anos anteriores e articular algo que seja mais do que a soma das partes. Escrever uma referência compreensiva técnica/histórica, vindo com um grande modelo explanatório de Como As Coisas Acontecem, isso tudo é atividade de aprendizagem `L(N^2)`.

A aprendizagem pode compor tanto *adiante* quanto para trás. Se o um aprendiz `L(N)` constrói sistemas para evitar a repetição de erros, o aluno `L(N^2)` automatiza para salvar o trabalho futuro e constrói modelos mentais que *antecipam* necessidades futuras, inferindo de ciclos anteriores.


## Aprendizagem em Público

Quando se trata de aprendizagem em público, introduzimos uma outra variável `P` à aprendizagem. Isso significa qualquer coisa que você queira que signifique - "Pessoas", "Pares", "Possívei Mentores", ou Comunidade.

Claro, eles existem quando você está aprendendo em privado. O conhecimento precisa *vir de* alguém. A maioria do `P` das pessoas são constantes e eles não prestam atenção a isso.

Mas você também poderia aprender *com* alguém. Quando você Aprende em Público, aumentar `P` torna-se um meta explícita e monitorada com marcos que você toma nota assim como faz na véspera de Ano Novo.

Você deveria também mentalmente escalar isso pra cima ou pra baixo de acordo com com o quanto você acha que um `P` adiciona contribui vs. um `N` adicional.

### L(PN) - O Aprendiz em Rede

O Aprendiz em Rede aprende com um grupo de pares, compartilhando notas a medida que seguem, se esbarrando quando estão empacados, e aprendendo enquanto respondem questões que eles nunca pensariam em perguntar. Esa habilidade de aprender de pessoas atrás de você, um pouco a frente de você, ou onde você está, é profundamente multiplicativo.

Provavelmente há um [limite de Dunbar](https://pt.wikipedia.org/wiki/N%C3%BAmero_de_Dunbar) para até onde esse `P` pode crescer, mas eu acho que relações ativas aumentam e diminuem de tal forma que adicionar pares de aprendizagem ainda é sempre aditivo.

Na verdade é *mais difícil* ser um Aprendiz em Rede, porém Com Perdas, ou `L(P log N)`. Se você faz corretamente, as pessoas mantêm você comprometido.


### L(PN^2) - O #AprendaEmPublico de Sucesso

Tudo bem, estamos firmemente fora dos limites da realidade humana aqui. Mas como será o `L((PN)^2)`?

Primeiro de tudo, você é um Aprendiz Profundo. Isso é certo.

Mas você também está combinando o aprendizado de pessoas proporcionalmente ao *quadrado* do número de pessoas (também conhecido como [Lei de Metcalfe](https://pt.wikipedia.org/wiki/Lei_de_Metcalfe)). A única maneira de obter isso é ter as pessoas aprendendo umas das outras independentemente de você, **E** você ainda ser beneficiado disso.

Eu acho que isso significa ativamente cultivar Comunidade que o ajude a servir a um maior objetivo/missão. Isso também pode tomar a forma de [Open Source Knowledge](https://www.swyx.io/speaking/sedaily-nocode) (Conhecimento com Fonte Aberta). Wikipedia ultrapassa as Enciclopédias tradicionais com uma fração do mesmo orçamento por que ela é apta a crescer a `L((PN)^2)` vs `L(N)` ou `L(PN)`.

Existem fatores de crescimento de pessoas além do `N^2` - [a lei de Reed (em inglês)](https://en.wikipedia.org/wiki/Reed%27s_law) cresce até `2^N`. Mas isso é novamente uma função da comunidade.


## P(N) - Reflexividade na Aprendizagem

Claro, o "Big L" é apenas um modelo da realidade, ele não é uma realidade verdadeira. Uma das maneiras que ele se desfaz é fingir que `N` e `P` são variáveis independentes. Elas não são. `P` provavelmente crescerá com `N` com uma função de sua senioridade e influência - ser um bom Aprendiz em rede cresce na ordem de `L(N^2)` o que é muito bom. Mas se você pode descobrir como crescer `P` superlinearmente con `N` - escrevendo, falando, ensinando, etc - você pode fazer sua carreira explodir em possibilidades.


## Little L

Eu já faalei muito sobre aprendizagem, mas também reconheço que aprender não é tudo. Você precisa estar fazendo, e você precisa estar vivendo. [Como você medirá sua vida?](https://hbr.org/2010/07/how-will-you-measure-your-life). Isso também provavelmente é uma função do número de pessoas que você conhece e dos anos que você vive produtivamente. Quais sacadas podemos ter aqui?

Talves *esse* seja o *verdadeiro* Big L que deveríamos estar perseguindo no final das contas.


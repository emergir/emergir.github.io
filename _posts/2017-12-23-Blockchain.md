---
title: "Blockchain"
permalink: /blockchain/
header:
  image: "/img/postagens/blockchain/capa.png"
  teaser: "/img/postagens/blockchain/capa.png"
categories:
  - Artigos
tags:
  - Blockchain
  - Tecnologia
  - Descentralização
  - Peer-to-peer
author:
  Danilo Vaz
toc: true
toc_label: "Navegando"
toc_icon: "compass"
---

Este é um artigo bastante detalhado sobre a Tecnologia de Blockchain através de uma perspectiva de evolução de sistemas de contabilidade. Investigamos como diferentes sistemas contábeis foram criados como resposta a crescentes níveis de complexidade comercial e como o Blockchain se encaixa neste contexto. Também é apresentada uma explicação em vídeo sobre o funcionamento do primeiro blockchain (o do Bitcoin), e as evoluções desta tecnologia que prometem trazer grandes mudanças na maneira em que nos organizamos socialmente.
Para melhor navegação, utilize o index ao lado -->


## Sistemas de Contabilidade

Você provavelmente realizou alguma transação comercial hoje, certo? Naquele momento, você parou para pensar no mecanismo tecnológico que possibilitou isso? Mecanismo que, na verdade, possibilitou todas as transações que 1) antecederam e 2) aconteceram em paralelo a sua? Pelo bem da sua sanidade eu espero que a sua resposta seja não. Felizmente, tal tecnologia é sofisticada o suficiente para que as pessoas possam viver suas vidas sem se preocupar com ela. Mas isso não muda o fato de que ela já tem cerca de 700 anos. E pior, que está começando a mostrar sua idade. Estamos falando da Contabilidade de Entrada Dupla (CED).

Antes de explorar o que é a CED e como ela revolucionou a história do comércio, vale a pena dar um passo atrás e entender um pouco mais sobre a história da contabilidade em geral. Imagine que estamos vivendo por volta do ano 10000 AC - quando a humanidade acabou de entrar no período que hoje é conhecido como Revolução Agrícola. Gradualmente, os seres humana deixam de caçar e juntar e começam a plantar e domesticar animais. E consequentemente novas necessidades surgem. Uma delas é a necessidade de realizar a contabilidade dos novos “bens” de uma pessoa, uma vez que antes deste período poucas coisas precisavam ser contabilizadas. A maneira mais fácil de realizar esta tarefa é através da criação de uma simples lista que contém informações sobre todos os grãos e animais de uma “fazenda”. Ou seja, a Contabilidade de Entrada Única (CEU).

> "Before that (Single Entry Accounting) we were running around the forest chasing animals, following the moon or farming. Our prospects were limited. You lived with your tribe or clan and you hunted and gathered. Your parents before you did the same thing and theirs before them and theirs before them in an endless cycle down through the years." [^1]

De maneira geral. é razoável assumir que processos similares deram origem aos primeiros sistemas de contabilidade pós-revolução agrícola. Afinal, é fácil de imaginar como a ausência de um sistema como este impossibilitaria o planejamento de plantações futuras e, mais importante, formas embrionárias de comércio ([Escambo](https://pt.wikipedia.org/wiki/Escambo)). Além disso, registros históricos como escrituras Sumerias [cuneiforme](https://pt.wikipedia.org/wiki/Escrita_cuneiforme) datadas de mais de 5000 AC, contém evidências que reforçam a ideia de que a CEU foi desenvolvida e utilizada por civilizações e impérios agrícolas para o gerenciamento de bens e comércio. Tal sistema foi mantido praticamente inalterado ao longo de muitos anos, aumentando apenas em escala (e nível de centralização) para acomodar os processos civilizatórios que deram origem aos diversos impérios e reinos. E a partir destes momentos, a CEU passa a ser uma atividade coordenada pelas elites imperiais, como coroa ou alguém de sua confiança (geralmente um membro familiar). Porém…

> “But single-entry accounting isn’t very good. It can only take you so far. The only accountants back then were the king’s brother because you really had to trust that guy. All he had to do was wipe away a line in the ledger and that money no longer existed. There was no way to verify, no way to audit, no way for two people to agree.” [^1]

Contabilidade de entrada única é muito simples de ser fraudada. Afinal, quando a economia de um reino depende de um único registro de entrada e saída de bens, é fácil imaginar como a pessoa sob controle desse registro pode fazer alterações para seu benefício próprio. E enquanto essa solução pode funcionar bem em sociedades com sistemas de organização social simples, ela começa a mostrar suas limitações conforme a complexidade social aumenta. Isto é, conforme os sistemas sociais começam a depender mais e mais das interações que são estabelecidas de maneira “peer-to-peer” (pessoa para pessoa), ao invés das interações impostas institucionalmente de cima para baixo.

“Mas o que tudo isso tem a ver com a transação comercial que eu realizei hoje?” Ótima pergunta. Imagine as diversas transações que ocorreram para que você tivesse acesso ao produto que você adquiriu hoje. Desde a aquisição de matéria-prima pelos fabricantes deste produto, até os processos de transporte que trouxeram o mesmo até a loja em que você o adquiriu, foram muitas as relações comerciais. E você pode ter certeza que isso não seria possível se não fosse a primeira revolução em contabilidade que aconteceu por volta do século XV e que nos permitiu atuar em um nível de complexidade maior do que aquele permitido pela CEU.

> “Double Entry bookkeeping is one of the greatest discoveries of commerce, and its significance is difficult to overstate. Historians think it to have been invented around the 1300s AD, although there are suggestions that it existed in some form or other as far back as the Greek empire. The earliest strong evidence is a 1494 treatise on mathematics by the Venetian Friar Luca Pacioli. In his treatise, Pacioli documented many standard techniques, including a chapter on accounting. It was to become the basic text in double entry bookkeeping for many a year.” [^2]

O [Frei Luca Pacioli](https://en.wikipedia.org/wiki/Luca_Pacioli) vivia em Veneza, nexo do comércio na Europa no final do século XV. Assim, seu trabalho ([Summa de arithmetica, geometria. Proportioni et proportionalita](https://en.wikipedia.org/wiki/Summa_de_arithmetica), 1494) teve grande relevância histórica para o continente e, consequentemente, para o mundo. Apesar de hoje parecer intuitiva, a sua grande sacana, conhecida como Contabilidade de Entrada Dupla (CED), permitiu aos mercantes europeus realizar transações de forma mais rápida e com um número de fraudes muito menor. A partir daquele momento, ambos os lados de uma transação mantiam uma cópia do registro que especifica as trocas que aconteceram entre elas. Cada registro era dividido entre dois grupos (ativos e passivos) e uma equação de balanço geral, dando controle a ambas as partes. Assim esses registros poderiam ser verificados por um terceiro em caso de desacordo sobre algum item. E mais importante, fraudes podiam ser rastreadas até a sua raíz (uma entrada em um registro que não condiz com a entrada em outro só pode ser um erro ou uma fraude).

E felizmente o contexto histórico também era propício para a disseminação das ideias de Pacioli, uma vez que outra revolução aconteceu durante o mesmo período. Com a invenção da impressora na metade do século XV por Johannes Gutenberg, os tratados escritos por Pacioli se espalharam de forma imprescindível. E com eles, o comércio marítimo auxiliado pela CED.

Avançando rapidamente para o final do século XX, é razoável afirmar que pouco mudou no mundo da contabilidade desde as contribuições do matemático Italiano. Obviamente, muito foi feito para a elaboração de processos burocráticos que acompanhassem todas as grandes transformações e eventos que aconteceram durante esse período (como a exploração do novo mundo, a revolução industrial, as duas grande guerra, etc). Porém, em sua essência, a CED como mecanismo tecnológico permaneceu relativamente inaltera.

Isso foi verdadeiro até o momento em que os avanços computacionais permitiram a materialização de processos contábeis mais ágeis e seguros. Afinal, apesar da grande vantagem em relação a CEU, a Contabilidade de Entrada Dupla também apresenta sérios problemas. Em economias com um alto número de participantes realizando diversas transações simultaneamente (alta complexidade), processos que verificam a veracidade das declarações financeiras são extremamente custosos e frágeis. Tanto é que, atualmente, casos de corrupção são comuns dentro do cenário econômico mundial. Para impossibilitar este mal que corrói economias inteiras como a do Brasil, novas soluções contábeis são necessárias, uma vez que pouco pode ser feito com a melhora da já velha CED.

Para nossa sorte, a partir do pioneirismo de pesquisadores da contabilidade e informação como o Professor Ijiri’s da [Universidade de Carnegie Mellon](https://via.hypothes.is/https://www.cmu.edu/piper/news/archives/2017/january/yuji-ijiri-obituary.html) e o empreendedor Ian Grigg[^2], uma nova revolução começou. A Contabilidade de Entrada Tripla (CET).

> “Most people missed Professor Ijiri’s breakthrough because it straddles two equally obscure and poorly understood fields: cryptography and accounting.” [^1]

Utilizando mecanismos de registros transacionais com identificação, armazenamento e verificação baseados em algoritmos, Ijiri e Grigg definiram as bases para um sistema contábil que transcende as limitações e pontos fracos da CED. Na prática, o que a CET ofereceu de vantagem em relação aos modelos anteriores foi a possibilidade de dois lados de uma transação concordarem sobre uma versão de eventos passados. Mais especificamente, eventos financeiros. Esse acordo, na visão de Grigg, se daria através da emissão de um recibo digital (a terceira entrada), contendo as informações sobre a troca entre as partes. Tal recibo, sendo assinado criptograficamente por ambas as partes, confere veracidade à transação e tem uma importância maior do que os registros individuais mantidos pelas partes envolvidas. Assim, caso haja algum desacordo relacionado a esta transação (ou caso ela precise ser auditada em algum momento), o recibo é a fonte a ser consultada. Dada suas configurações técnicas, este recibo é inalterável e ele apresenta acesso público - permitido pela criptografia que proteje as identidade.

> “The cryptographic invention of the digital signature gives powerful evidentiary force to the receipt, and in practice reduces the accounting problem to one of the receipt's presence or its absence. This problem is solved by sharing the records - each of the agents has a good copy.” [^2]

Desde a publicação do trabalho de Grigg em 199 5 até a primeira aplicação real de suas ideias (e das ideias do Prof. Ijiri), passaram-se 13 anos e duas bolhas financeiras - uma com um impacto tremendo na economia mundial. [Potencialmente por conta disso](https://analyticsindiamag.com/origin-bitcoin-brief-history/), o gênio de pseudônimo Satoshi Nakamoto publica, em 2008, [Bitcoin: A Peer-to-peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf).

O protocolo Bitcoin agrega as ideias centrais sobre a Contabilidade de Entrada Tripla e é muito razoável assumir que Satoshi Nakamoto foi bastante influenciado pelos pesquisadores aqui citados. Porém, Bitcoin: A Peer-to-peer Electronic Cash apresentou ao mundo muito mais do que isso. O artigo conta com a descrição de um ecosistema para a manutenção de um sistema financeiro descentralizado e, mais importante ainda, um **modelo de banco de dados caracterizado pela disposição de blocos de dados em cadeia, cada um contendo vários recibos digitais inalteráveis, públicos e encriptografados sobre transações realizadas por elementos de uma rede**. E isso tudo ficou conhecido como Blockchain. Neste sentido, a tecnologia de Blockchain é uma versão aprimorada (para o uso em escala) do sistema de Contabilidade de Entrada Tripla, oferecendo grande vantagens de segurança e veracidade em relação à CED.


> “Triple-entry accounting and by extension blockchains and crypto are a way of agreeing on objective reality. It's not the objective reality, but it's an objective reality (...) The third entry in the system, entered into the blockchain, is both a receipt and a transaction. It’s proof that something happened between two parties, which goes beyond the receipts that each party holds in double entry." [^1]

## Mas o que é, de fato, o Blockchain

Ao afirmar que blockchain é uma versão aprimorada da CET estamos pensando na função que esta tecnologia desempenha - função esta que tem um caráter econômico na aplicação de Bitcoin. Porém, como veremos, os detalhes sistêmicos e técnicos por trás desta tecnologia vão além disso. Assista ao vídeo que produzimos para uma boa introdução às tecnicalidades desta tecnologia.

> “A blockchain is a list of transactions—a ledger—maintained by a community of users, rather than a central authority. It’s called a blockchain because new transactions are bundled into “blocks” of data and written onto the end of a “chain” of existing blocks describing all prior transactions.” [^3]

### Vídeo Explicativo

<iframe width="560" height="315" src="https://www.youtube.com/embed/az9_gdgHdpI" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## Bitcoin, a Primeira Aplicação

A criação de Sathoshi Nakamoto representa um marco histórico para o sistema financeiro mundial. Pela primeira vez viabilizou-se a realização de transações entre pares de forma completamente descentralizada e segura. Isto é, sem a necessidade de uma instituição fiscalizadora determinando a validade da transação e atualizando os registros e balanços das partes envolvidas. Porém, a ideia de um terceiro registro que é aberto, protegido por criptografia e atualizado de maneira automática passou despercebida por muito tempo.
Bitcoin pode ser entendido como um token digital (um símbolo digital) que também é chamado de moeda cripto por conta dos mecanismos de criptografia que permitem a sua criação. E assim como a maioria das moedas atuais, o seu valor vem da percepção que as pessoas têm sobre a moeda, ao invés de um bem no mundo real que dê suporte a mesma.

Apesar de hoje Bitcoin estar nos jornais e noticiários por conta da sua crescente valorização, ele permaneceu estagnado por muito tempo. E muito do que se vê atualmente em relação ao seu preço é o resultado de movimentos especulativos  - por conta dos altos retornos até o momento - ao invés de um real interesse na tecnologia e suas possíveis aplicações. O que, por sua vez, gera uma preocupação em relação ao futuro desta moeda, já que a história mostra que bolhas especulativas tendem a estourar, deixando grande sequelas econômicas nos envolvidos.[^4]

> “From the tulip craze to the South Sea and dotcom bubbles, the past teaches us to beware too strong a dose of irrational exuberance.” [^5]

Porém, para além da especulação, existem outros desafios no caminho de Bitcoin - e do sistema de contabilidade de entrada tripla - rumo à adoção em escala. Como vimos durante o vídeo explicativo sobre o funcionamento da tecnologia de blockchain, existem procedimentos complexos que devem ser adotados para que ela realmente funcione como um terceiro registro de contabilidade. Tais procedimentos, apesar de necessários, têm certos custos com a adoção em massa. Mais especificamente, estes custos estão associados com o valor das taxas que os mineradores recebem para validar as transações efetuadas na rede, e o alto custo energético por traz do processo de mineração de blocos. Se você não entende o que está sendo dito aqui, assista ao vídeo mencionado. As provas de trabalho que garantem a integridade da cadeia de blocos (blockchain) têm dificuldade crescente, o que faz com que os mineradores tenham que utilizar cada vez mais e mais poder computacional para a criação de novos blocos. E conforme mais pessoas adotam o sistema - e enviam transações pela rede de blockchain - maior é a competição para que as mesmas sejam incluídas em novos blocos. O que, por sua vez, aumenta o tempo de confirmação e o valor das taxas que incentivam os mineradores a realizar estas atividade. Tais efeitos colaterais geram alguns impactos indesejáveis:

> "Bitcoin “miners” are electromagnetic alchemists, effectively turning megawatt-hours of electricity into the world’s fastest-growing currency. Their intensive computational activity cryptographically secures the virtual currency, approves transactions, and, in the process, creates new bitcoins for the miners, as payment." [^6]

### Transações por Segundo

![transações](/img/postagens/blockchain/transacoes.png)

Este gráfico demonstra um dos maiores desafios de escalabilidade de Bitcoin. Quando pensamos nesta tecnologia como uma alternativa às atuais formas de transações financeiras - que são centralizadas e portanto invariavelmente burocráticas - é necessário considerar se esta tecnologia oferece um serviço superior aos seus usuários finais. E como podemos ver, quando a métrica é transações por segundos, Bitcoin ainda fica muito atrás das opções convencionais. Em outras palavras, transações com Bitcoin acabam sendo mais lentas do que o pagamento com cartão. Tal fato foi inclusive uma das razões que fizeram com que alguns membros da comunidade Bitcoin optassem por uma outra versão do protocolo - o chamado [fork](https://guiadobitcoin.com.br/tag/fork-bitcoin/) que deu origem ao Bitcoin Cash, uma moeda que é muito parecida com o Bitcoin mas que apresenta melhores resultados em transações por segundo.

{: .box-note}
**Ressalva**: A Comunidade de desenvolvedores do Bitcoin têm trabalhado intensamente para encontrar soluções para o problema de escalabilidade. Uma das mais esperadas é a [Lightning Network](https://lightning.network/), um protocolo que permite que dois nós da rede possam realizar transações entre si sem precisar transmitir-las para a rede toda. O que acontece através da criação de uma nova camada de comunição com intermediários minimamente confiáveis em cima do protocolo original, garantindo assim um menor tempo de transação. Este projeto encontra-se em fase avançada de desenvolvimento.

### Consumo de Energia

![energia](/img/postagens/blockchain/energia.png)

Já este gráfico diz respeito a uma grande controvérsia a respeito da manutenção da infraestrutura de blockchain que suporta o Bitcoin. Ele tem um caráter comparativo, já que os valores exatos de consumo energético das opções listada não são tão simples de estimar. Porém, o gráfico ainda é útil para demonstrar a grande quantidade de energia necessária para manter a rede Bitcoin com os atuais mecanismos de incentivo. Como é comentado no vídeo acima, para transmitir um novo bloco ao registro compartilhado, um minerador deve resolver um problema matemático que confere uma prova de trabalho ao bloco. E estes problemas matemático têm uma dificuldade crescente para garantir que novos blocos sejam gerados a cada 10 minutos na rede. Assim, conforme o número de mineradores aumenta - devido à crescente adoção do sistema - é fácil de imaginar que mais e mais computadores estarão tentando resolver os mesmos problemas (com apenas um ganhador), gerando assim um alto consumo energético por parte da rede. Até recentemente, tal fator não era uma preocupação para o funcionamento da criptomoeda. Porém, conforme mais pessoas passam a utilizar-la, esse aspecto se torna mais importante. Principalmente por conta das estimativas que argumentam que a quantidade de energia utilizada para manter o Bitcoin é equivalente à energia necessária para alimentar centenas de milhares de casas por um ano. Isto é, uma cidade inteira.

{: .box-note}
**Ressalva:** Existe muita controvérsia ao redor do real custo energético do Bitcoin, principalmente quando comparado a toda a infraestrutura necessaria para o funcionamento dos atuais meios de transferência de quantias, como dinheiro, cartões e bancos. Para mais informações neste tópico recomenda-se esta [série de postagens](https://blog.gridplus.io/money-vs-cryptocurrency-the-real-costs-part-1-33c09dfea671).

Os lados negativos mencionados devem ser definitivamente considerados quando pensamos na utilização desta tecnologia em escala. Principalmente quando eles são comparados com as opções já existentes para o sistema financeiro. Porém, eles não devem ser vistos como obstáculos insuperáveis. Até porque o potencial de transformação do conceito de Entrada Tripla é imenso.

## Contabilidade/Registro Público de Entrada Tripla

Até o momento discutimos a relevância da tecnologia de blockchain a partir de uma perspectiva histórica dos sistemas contábeis que provocaram revoluções no comércio. Através deste olhar, Bitcoin - e outras moedas criptográficas existentes - podem ser vistas como um símbolo que marca o início de um processo de descentralização do mercado financeiro mundial. Principalmente pelo fato de que tais moedas tornam questionável a existência de instituições financeiras burocrática, possibilitando um maior fluxo de informação entre os elementos de um sistema hiperconectado. Porém, a possibilidade de aumento de fluxo de informação não está limitada apenas ao sistema financeiro. **E esta é a maior promessa apresentado pela tecnologia de blockchain**.

Se extrapolarmos a ideia de um sistema de CET para o campo mais abstrato de registro de informações, chegamos ao conceito de Registro Público de Entrada Tripla. Para entender o que isto significa, imagine um cartório e as funções que ele desempenha. De maneira geral, como cidadãos brasileiros, confiamos aos cartórios a habilidade de validar a identidade e/ou posse de bens de uma pessoa. E tal validação tem certo valor apenas porque existe um conjunto de regras sociais (conhecidas como leis) que estabelece que os documentos pertencentes aos registros de um cartório podem ser utilizados como instrumentos legais para a resolução de disputas. Ou seja, o Cartório, como instituição, desempenha o papel de um Registro Centralizado de Entrada Tripla para transações de bens e informações pessoais dos cidadãos de um país. Os participantes de uma transação mantém uma cópia da mesma, enquanto a versão com poder legal é conferida aos registros do Cartório. A partir deste olhar, é possível identificar os paralelos que podem ser feitos entre registros gerais de informação e a tecnologia de blockchain.

Qualquer pessoa que já precisou pisar em um cartório sabe da ineficiência desta instituição. Não são poucos os processos burocráticos que devem ser realizados para que qualquer atividade em cartório seja concluída, o que invariavelmente adiciona tempo e custo às diversas transações que acontecem entre pessoas físicas ou jurídicas. Muito desse problema deriva do fato de que apenas o cartório tem acesso às informações em seu registro. Isto é, este registro é fechado. O que é de certa forma compreensível, dada a importância de tais informações. Porém, como vimos com Bitcoin, a tecnologia de blockchain fornece soluções que permitem a realização de serviços transacionais muito semelhantes ao de um cartório, mas de forma aberta (Pública), menos burocrática e mais segura, já que os donos de certa informação detém total controle sobre ela através da posse da Chave Privada. Em outras palavras, os dados em um banco de dados do blockchain são públicos, simplificando processos de verificação. Mas ao mesmo tempo, eles são protegidos por uma camada de criptografia que garante a realização de transações e a proteção da identidade dos envolvidos. Ou seja, não existe a necessidade de uma instituição regularizadora para garantir estes aspectos em troca de altos custos burocráticos.

Fora do campo financeiro, tais transações podem ser entendidas como a transferência de posse de bens entre duas pessoas ou a utilização de informações cívicas para a comprovação de identidade ou estado conjugal. Junto a isso, está o fato de que as informações registradas em um blockchain são imutáveis por definição (veja o vídeo para entender o porquê). Assim…

{: .box-note}
A tecnologia de blockchain pode ser utilizada para o armazenamento e validação descentralizada de informações cívicas e jurídicas como certidões de nascimento e casamento, comprovantes de identidade, comprovantes de posse de bens ou ações, registros de acordos e muito mais.

Essa é a grande promessa desta tecnologia. A descentralização de serviços de registros que hoje são burocráticos e tornam processos simples em maratonas custosas e demoradas. E se pensarmos bem, apesar de não percebermos, praticamente tudo relacionado à vida em sociedade passa por algum sistema de registro. Alguns são reais e físicos - como os registros de um cartório - e outros vivem no imaginário coletivo - como os registros de interações sociais que regem a reputação de um indivíduo em uma comunidade. Portanto, se conseguirmos tornar estes sistemas de registro mais eficazes - em detrimento da burocracia - criamos espaço para um fluxo maior de informação entre as pessoas, permitindo maiores atividades econômicas, políticas e culturais. Isto é, damos espaço à Complexidade.

Por esta razão, muitas pessoas veem a tecnologia de blockchain como uma solução de alto potencial. E felizmente algumas destas pessoas têm trabalhado muito para o aprimoramento da tecnologia de forma que os seus lados negativos (como discuto acima) sejam minimizados. Tal processo tem originado versões aprimoradas da blockchain e, mais além, protocolos que tornam esta tecnologia obsoleta.

## Evolução do Blockchain

Para que a tecnologia de blockchain possa cumprir com a sua “promessa”, os desafios mencionados acima devem ser resolvidos de alguma maneira. Isto é, os problemas de energia e números de transações por segundo precisam de soluções. Nos gráficos apresentados, observamos a presença do Ethereum, solução que apresenta valores para o consumo de energia e transações por minuto muito superiores ao do Bitcoin. Logo, é natural que surja a pergunta, o que é este Ethereum.

> Ethereum is an open-source, public, blockchain-based distributed computing platform featuring smart contract (scripting) functionality. It provides a decentralized Turing-complete virtual machine, the Ethereum Virtual Machine (EVM), which can execute scripts using an international network of public nodes. Ethereum also provides a cryptocurrency token called "ether", which can be transferred between accounts and used to compensate participant nodes for computations performed. "Gas", an internal transaction pricing mechanism, is used to mitigate spam and allocate resources on the network.[^7]

### Ethereum

Criando em 2013 e implementado em 2014 pelo russo-canadense [Vitalik Buterin](https://en.wikipedia.org/wiki/Vitalik_Buterin), o Ethereum é uma outra infraestrutura de blockchain que utiliza os insights de Satoshi Nakamoto mas com algumas modificações em relação às informações armazenadas no registro e à prova que garantem a sua segurança. E por conta deste último, ele acaba tendo resultados superiores à infraestrutura de blockchain - tanto de energia quanto de transações por minuto. Não entraremos muito em detalhes sobre como o blockchain do Ethereum funciona, mas vale a pena falar sobre algumas das suas principais características.

Primeiro, as informações registradas oa blockchain Ethereum não são puramente transações financeiras como no blockchain do Bitcoin. Ao invés disso, elas são o que ficou conhecido como contratos inteligentes (smart contract).

> A smart contract is a computer protocol intended to facilitate, verify, or enforce the negotiation or performance of a contract. Smart contracts were first proposed by Nick Szabo in 1996.[1] Proponents of smart contracts claim that many kinds of contractual clauses may be made partially or fully self-executing, self-enforcing, or both. The aim with smart contracts is to provide security that is superior to traditional contract law and to reduce other transaction costs associated with contracting.[^8]

De maneira resumida, um contrato inteligente é um algoritmo computacional que rege interações específicas entre duas partes, de maneira que ambas têm a garantia de que vão receber aquilo que foi previamente estipulado. Se formos traçar uma analogia com contratos normais, podemos pensar nas pessoas e instituições responsáveis por reforçar o cumprimento do contrato. Estas geralmente fazem uso de instrumentos legais ou da força para que um determinando acordo entre duas partes seja cumprido. A ideia por trás dos contratos inteligentes é que este intermediário não seja necessário, já que o algoritmo que compõe o contrato estaria a cargo dessa função. Por exemplo, imagine que você concorde em alugar a sua casa para uma pessoa mediante um determinado pagamento. Um contrato inteligente associado à uma porta inteligente na sua casa e à sua carteira digital, poderia garantir que a porta só seria aberta quando a sua carteira recebesse a quantia acordada de um endereço específico. O único detalhe é que, obviamente, estas transações devem acontecer através de alguma moeda crypto, como o Ether. Este exemplo é ilustrativo mas ele não dá a ideia completa do que pode ser alcançado com o Ethereum, já que tais contratos inteligentes podem ser configurados para a especificação de qualquer tipo de interação entre dois ou mais pares.

Uma outra característica específica do blockchain Ethereum é o seu mecanismo de confirmação de transações e criação de Ether. Até recentemente, o Ethereum utilizava um mecanismo de prova de trabalho aos moldes do mecanismo que explicamos para o Bitcoin. Porém, isso este foi substituído por um mecanismo de Prova de Participação (Proof of Stake). De maneira simplificada, este mecanismo dá aos mineradores o poder de verificar transações - e receber recompensas em cripto-moeda - de maneira proporcional à quantidade de moedas que este minerador está disposto a investir em uma rodada de mineração. Isto é, ao invés de ter que resolver desafios matemáticos, os mineradores devem separar parte de seus ethers para adquirir poderes de votação em um processo de validação de transações e montagem de blocos que é coordenado pelo protocolo Casper - um contrato inteligente registrado no blockchain do Ethereum. Se tudo ocorrer como planejado, durante a mineração os mineradores são recompensados pela criação de novos blocos de maneira proporcional à parte que eles separaram para a sua participação.

E finalmente, o projeto Ethereum também apresenta uma máquina virtual (Ethereum Virtual machine) capaz de realizar qualquer tipo de cálculo matemático de forma descentralizada. Isso acontece porque os mineradores também recebem recompensas em ether para rodar os algoritmos por trás dos contratos inteligentes armazenados na blockchain Ethereum, o que é feito de maneira distribuída pela rede.

> "To put this into a language everyone can understand, the Ethereum Virtual Machine is designed to serve as a runtime environment for smart contracts based on Ethereum. As most cryptocurrency enthusiasts are well aware of, smart contracts are very popular these days. This technology can be used to automatically conduct transactions or perform specific actions on the Ethereum blockchain. Many people predict smart contracts will help revolutionize finance and other industries over the coming years." [^9]

Com tais características, a infraestrutura Ethereum pode ser entendida como um super computador capaz de armazenar e computar contratos em formato de software sobre qualquer transação entre dois ou mais pares. O que é, por si só, um feito incrível. Porém, suas aplicações mais interessantes surgem do fato de que novos tokens cripto - à exemplo do Bitcoin e Ether - podem ser criados com a expedição de contratos inteligentes no blockchain Ethereum. Desta maneira, qualquer pessoa ou organização pode criar [tokens cripto](https://www.ethereum.org/token) (ou simplesmente tokens) que sirvam de incentivo para diferentes ecossistemas descentralizados que giram em torno do blockchain Ethereum. E com isso, Ethereum têm fomentado o surgimento de vários [DApps](https://blog.bitnation.co/what-are-dapps/) (Decentralized Apps) que buscam melhorar a eficiências de setores corroídos pela burocracia de sistemas de registros e verificação que não foram criados para a era da internet. Estes DApps funcionam como qualquer outra aplicação de software instalada em seu computador ou celular. Porém, pelo fato de eles operarem de maneira descentralizada, seus incentivos de participação são diferentes, de forma que os usuários finais tendem a se beneficiar (inclusive financeiramente) da sua participação na aplicação. Tal movimento tem originado o que está sendo conhecido como Internet 3.0. Uma internet composta de aplicações descentralizadas e regidas por crypto-tokens que retribuem a participação de seus usuários em ecossistemas completamente novos.

>"From socializing to hailing a cab to finding our way around, there's an app to help. Now, there is a new and improved model that is revolutionizing the way we build scalable applications called a DApp, or decentralized application." [^10]

E apesar da infraestrutura Ethereum ser hoje a mais popular para a criação de Dapps, os esforços para melhorar a tecnologia de blockchain - ou apresentar uma alternativa que a torne obsoleta - não param. Caso você queira conhecer mais sobre as outras iniciativas que buscam dar o próximo grande passo no campo de infraestrutura para a descentralização, esta é uma lista de alguns destes projetos:

### Projetos Alternativos

- [Holochain - A new alternative web for truly peer-to-peer applications](https://holochain.org/)
- [Hashgraph - Superior Distributed Ledger Technology](https://hashgraph.com/)
- [RaiBlocks - Feeless Distributed Cryptocurrency Network](https://raiblocks.net/media/RaiBlocks_Whitepaper__English.pdf)
- [EOS - First Blockchain Operating System](https://steemit.com/eos/@trogdor/introduction-to-eos-the-epic-blockchain-operating-system)
- [IOTA - Next Generation Blockchain](https://iota.org/)
- [Bitlattice - Multi-Dimensional Lattice Structure](https://bitlattice.org/)

Apesar das diferentes especificações técnicas, todos esses projetos têm um desejo em comum: oferecer as fundações para os Dapps e a Internet 3.0. Que, por sua vez irão revolucionar a maneira como interagimos em sociedade. É difícil de saber quais projetos terão sucesso nesta empreitada. Porém, isso não muda o fato de que estamos vivenciando um momento que gera bastante expectativas. Até por que hoje podemos acompanhar o desenvolvimento destas tecnologias e projetos em tempo real, através de seus canais de comunicação nas redes socias. Muitos até falam que estamos vivendo momento parecidos ao surgimento da internet na década de 90. Porém, com proporções muito maiores.

## Descentralizando o Mundo para abraçar a Complexidade

> "We should think about the blockchain as another class of thing, like the Internet—a comprehensive information technology with tiered technical levels and multiple classes of applications for any form of asset registry, inventory, and exchange, including every area of finance, economics, and money; hard assets (physical property, homes, cars); and intangible assets (votes, ideas, reputation, intention, health data, information, etc.). But the blockchain concept is even more; it is a new organizing paradigm for the discovery, valuation, and transfer of all quanta (discrete units) of anything, and potentially for the coordination of all human activity at a much larger scale than has been possible before.” [^11]

Até aqui, discutimos bastante sobre os detalhes técnicos das tecnologias de blockchain e como elas são vistas dentro de uma breve perspectiva de evolução de sistemas de registro. Porém, pouco foi dito sobre como elas se relacionam com conceitos gerais da Teoria da Complexidade. De maneira geral, soluções em blockchain permitem o fluxo aberto e seguro de informação no modelo de pessoa para pessoa (peer-to-peer). Isso, por sua vez, dá espaço para maiores quantidades e diversidades de interações sociais através da tecnologia, aumentando a complexidade do sistema social em questão. Este fenômeno apresenta vantagens claras para os elementos deste sistema e para o sistema como um todo, uma vez que há um aumento nas interações comerciais, cívicas, políticas e etc., o que é um resultado fenomenal para processos de inovação e, mais importante ainda, de resolução de problemas complexos.

> Segundo Bar-Yam (fundador do Instituto de Sistemas Complexos da Nova Inglaterra), existe uma lei universal e sagrada dos sistemas complexos: “a complexidade de um sistema realizando uma tarefa deve ser tão grande quanto a complexidade da tarefa”. [^12]

E o fato de que tudo isso acontece de uma maneira auto-gerenciada em rede (especialmente por conta da utilização de contratos inteligentes), deve ser ressaltado, uma vez que esta é uma das características chaves de sistemas complexos adaptativos. Em outras palavras, tecnologias de blockchain permitem a auto-organização de baixo para cima que se adapta ao ambiente em questão - em detrimento de modelos de governança de cima para baixo que determina o formato e direcionamento de um sistema. Com isso, aumentam as chances de um desenvolvimento tecnológico orgânico que é focado na resolução dos problemas reais de um sistema social, ao invés dos problemas imaginados por uma parte deste sistema que acredita entender o sistema como um todo. Então, assim como o desenvolvimento da Contabilidade de Entrada Dupla permitiu o surgimento de formas de organização social mais complexas que fugiam do controle de estrutura centralizadores como a corte, a tecnologia de blockchain permite níveis ainda maiores de complexidade social, tornando obsoleta a maioria das estruturas de centralização.

Neste sentido, a relação entre o blockchain e a complexidade pode ser melhor explorada quando pensamos nas aplicações descentralizadas que estão sendo criadas dentro de ecossistemas como o Ethereum.

> "A new breed of applications is being discussed across the world. These types of applications are not owned by anyone, can’t be shut down, and cannot have downtime." [^13]

Tais aplicações variam bastante de escopo, foco e qualidade. No entanto, elas têm em comum a utilização de tokens crypto como ferramenta fundamental para a interação com seus usuários finais. E essas interações envolvem inclusive o financiamento de tais projetos.

### ICOs

Ao permitir que qualquer projeto possa criar um token em seu blockchain, o projeto Ethereum deu início a uma revolução na maneira em que startups e ideias são financiadas. O modelo de financiamento tradicional envolve a procura por investidores que, ao acreditar no potencial de uma ideia, oferta os recursos necessários para a criação da mesma em troca de ações em suas operações. Isto é, um modelo centralizador de financiamento que fazem uso dos sistemas de registro de entrada dupla, criando infinitas possibilidades de fraude.

> “Let’s say you have a little company that we’ll call Enron. It’s doing tremendously well. You’ve got a million shares of stock, say 10% of the total shares. At least you think you do. You’ve got an official looking piece of paper that says you own a million shares. That’s legit, right? It has a stamp and everything. Except you don’t really, because they were cooking the books or issuing double shares. With today’s double entry systems it’s a security problem to give you access to their books. They live behind the corporate firewall.” [^1]

Por muito tempo esta era única opção para empreendedores que quisessem pôr as suas ideias em prática. Porém, este já não é mais o caso. Agora qualquer projeto pode ser financiado através da venda de crypto-tokens que representam ações no mesmo. Isto é, um modelo descentralizado de financiamento. Este modelo ficou conhecido como ICO (Initial Coin Offering - “Venda Inicial de Moedas”) à exemplo do IPO (Initial Public Offering) que geralmente ocorre quando uma empresa abre as suas ações ao mercado. Empreendedores agora devem se preocupar não mais em agradar e um grupo limitado de potenciais financiadores, mas sim convencer a comunidade de usuários potenciais de sua ideia para que estes sim financiem seu projeto. E apesar de esta parecer uma abordagem duvidosa, existem muitos cases de sucesso que comprovam sua eficácia. Como por exemplo a plataforma descentralizada de comunicação Status que neste ano levantou mais de 100 milhões de dólares em menos de 1 hora.[^14] Veja a recente explosão do fenômeno de ICOs no gif abaixo.[^15]

![ico](/img/postagens/blockchain/ico.gif)

Em geral, a distribuição de tokens é feito através do blockchain do Ethereum, o que garante transparência e segurança ao processo. Assim, compradores destes tokens se beneficiam duas vezes da criação de um projeto. A primeira vez como investidores que poderão vender estes tokens no mercado caso eles valorizem - o que tende a acontecer se a ideia for bem sucedida. E uma segunda vez como usuários dos projetos em que eles estão investindo, já que os token são geralmente utilizados nas atividades finais fornecidas pelo projeto. Como por exemplo a troca de tokens pelo pagamento de algum serviço entre usuários de uma Daap. Tais mecanismos dão origem a um novo paradigma econômico que já está sendo chamado de Economia de Tokens.

> "The decentralized economy works through a token system, where each platform creates a token that represents the underlining value that is being created and exchanged within that
network. People can then invest in that micro-economy by purchasing the tokens and likewise use them in that ecosystem. Through this token system, ultimately, what blockchain will do is create a whole new economy and value system outside of the traditional utility based economy. As more of the traditional form of utility value flows into the token economy, this will enable people to move out of the traditional economic structures as the new full value economy is born and people move to the new economy based on token networks build on the distributed web". [^16]


### Gerenciamento

Ainda mais interessante do que a participação no financiamento de um projeto, é a participação no gerenciamento do mesmo, o que também é possível dentro deste paradigma. Como mencionado, uma vez que um usuário detém um token de um projeto, este token pode ter o valor que for determinado pelos idealizadores do projeto - que transformam tal valor em códigos que regem os contratos inteligentes por trás do token e do projeto. Caso os idealizadores queiram que o projeto seja gerenciado pela sua comunidade de usuários, o token que o representa pode conferir poder de votação para as decisões de governança deste projeto. Este é um insight muito diferente do que, hoje, acredita-se ser normal dentro das práticas de gerenciamento de projetos e empresas. Porém, ele tem um potencial tremendo, ainda mais quando consideramos as constantes [evoluções em estruturas organizacionais](https://www.inc.com/brian-d-evans/status-ico-raised-over-100-million-for-ethereum-powered-dapps-on-ios-and-androi.html). E apesar de existirem poucos projetos operando desta maneira, existem muitos esforços para facilitar esse tipo de organização. Um dos maiores exemplos é a plataforma [Aragon](https://aragon.one/).

### Aragon

A plataforma desenvolvida pelo projeto Aragon (também financiando por um ICO) oferece uma maneira simples de auto-organização através da distribuição de tokens que representem posse e/ou poder de votação para os diferentes membros de uma organização. Uma outra parte do projeto, chamada de Rede Aragon, oferece uma jurisdição de indivíduos que podem arbitrar disputas que surjam dentro e/ou entre as organizações gerenciadas pela plataforma em troca de tokens cripto, de forma que todos os processos das organizações Aragon podem ser resolvidos através do blockchain Ethereum. E a projeto Aragon já é um dos exemplos de organização operando desta maneira.

> "Aragon Network will be the first community governed decentralized organization whose goal is to act as a digital jurisdiction, an online decentralized court system that isn’t bound by traditional artificial barriers such as national jurisdictions or the borders of a single country." [^17]

Assim, Aragon representa um dos caminhos mais fáceis para uma organização que queira atuar de maneira descentralizada - sem depender das estruturas burocráticas estatais para a resolução de seus trâmites legais.

E uma vez que é possível realizar o gerenciamento de organizações através de tecnologias de blockchain, por que não fazer o mesmo para o gerenciamento das atividades sociais e cívicas que regem um grupo de pessoas? Isto é, porque não pensar em ferramentas que permitam a auto-organização política entre indivíduos que compartilhar os mesmos desejos e valores? Foi com base neste tipo de inquietação que surgiram projetos que tentam descentralizar a ideia do Estado-nação. Em outras palavras, estruturas de auto-organização que possibilitem o cumprimento dos contratos sociais que regem um grupo de invidícuos. É esta a missão da [Bitnation](https://bitnation.co/).

### Bitnation

Com a sua plataforma chamada [Pangea](https://tse.bitnation.co/), Bitnation pretende empoderar pessoas ao redor do mundo para que elas criem suas próprias “Decentralised Borderless Voluntary Nation” (DBVN) - ou participem de DBVN existentes. A ideias por trás de tais organizações é a de que seus membros têm o direito de escolher os conjuntos de leis e serviços que são oferecidos a eles em troca de seus impostos. E semelhante à estrutura criada por Aragon, Pangea registra todas as informações pertinentes às DBVNs em no blockchain Ethereum, e conta com uma rede de arbitradores que resolvem os conflitos que possam emergir entre os membros de uma DBVN.

> "Pangea is a decentralized market for legal services. Create and execute peer-to-peer agreements seamlessly across the world, resolve disputes fairly and efficiently. Choose an arbitrator, or become an arbitrator in your field of expertise. On Pangea you can create your own Decentralised Borderless Voluntary Nation (DBVN). Choose your Code of Law, Economic Model, Decision Making Mechanism, write a Constitution and provide Governance Services to Citizens." [^18]

Bitnation é um dos grandes nomes dentro do mundo cripto (mundo que envolve os projetos baseados em tecnologia de blockchain). Muito por conta de seus projetos anteriores, como a [parceria com o governo da Estónia](https://bitnation.co/blog/pressrelease-estonia-bitnation-public-notary-partnership/) para emissão das identidades digitais dos cidadãos do país em um blockchain, e a criação de um sistema Emergencial de Identidade para Refugiados durante a crise de 2015 - [BITNATION Refugee Emergency Response (BRER](https://bitnation.co/refugee-emergency-response/) - também em blockchain. E recentemente o projeto organizou reuniões abertas com representantes dos movimentos sociais da Catalunha para a criação de uma [DBVN catalã](https://bitnation.co/refugee-emergency-response/). Enfim, são grandes as expectativas em torno da plataforma Pangea e elas só aumentam quando olhamos para o histórico de atuação do grupo desenvolvendo a mesma. Felizmente, logo saberemos como esta ferramenta impactará a vida de seus usuários, uma vez que Bitnation está muito próximo de realizar o seu ICO.

![Bitnation](/img/postagens/blockchain/bitnation.jpg)

E se a descentralização do Estado-nação é uma ideia impressionante por si só. O que dizer sobre a descentralização do Mercado? O projeto [District0x](https://district0x.io/) pode ter as respostas para esta pergunta.

### District0x

Após desenvolver uma plataforma para freelance onde empregadores e prestadores de serviço poderiam coordenar atividades com uso uso de cripto-moedas e sem a presença de um intermediário (conferindo um custo mais baixo para todos os envolvidos), a equipe por trás da [Ethlance](https://ethlance.com/) percebeu que eles tinham algo muito mais poderoso em mãos. O que eles tinham desenvolvido era na verdade um conjunto de algoritmos (regendo contratos inteligentes e uma interface de usabilidade) que poderia ser adaptado para a criação de qualquer “marketplace”.

Isto é, seus códigos poderiam ser utilizados para conectar passageiros e pessoas que queiram ofertar carona, residentes de um local e pessoas que buscam por um quarto temporário, donos de algum objeto e pessoas que precisam deste objeto por um tempo curto, etc. Enfim, um código coringa que poderia ser adaptado para a criação de Uberes e Airbnbs descentralizados.

> "Districts are marketplaces and communities that exist as decentralized autonomous organizations on the district0x Network. All internet citizens will be able to deploy districts to the network free of charge, forever." [^19]

Esta equipe decidiu então democratizar este framework para que qualquer pessoa na internet possa, facilmente, criar um mercado descentralizado para qualquer coisa. Estes mercados utilizam o blockchain Ethereum como banco de dados, recebem o nome de distritos e possuem funções de listagem, busca, reputação e pagamento com comprovante. E o mais interessante, todos distritos são geridos por unidades Aragon graças a parceria entre os projetos. Isso significa que os distritos podem ser geridos por aqueles que os utilizam, ao invés de um grupo inicial de fundadores.

Tais características representam uma grande mudança de paradigma em relação as plataforma de compartilhamento existentes, já que estas ainda são controladas por um grupo específico de pessoas cujos modelos de negócio dependem da cobranças de taxas pelo uso de seus códigos. O que gera maiores custos para estes serviços, e cria situações de desequilíbrio de poder entre organização e usuários. A partir do momento em que os usuários finais podem definir as regras da organização, este desequilíbrio diminui e tais serviços passam a ser auto-geridos, adaptando-se à complexidade de seu setor.

### E Muito, Muito Mais…

Basicamente, para todos os serviços existentes hoje em dia, haverá uma pessoa ou grupo trabalhando em uma alternativa descentralizada. Isso é bom e ruim ao mesmo tempo. Por um lado é importante desafiar os sistemas existentes e pensar em soluções mais efetivas. Mas também é importante reconhecer que tais mudanças levam tempo para acontecer e é muito melhor que a transição para o mundo descentralizado seja feita com calma e - principalmente - com consciência por parte dos usuários do que com pressa e falta de informação. Ainda assim, o potencial de transformação social é imenso, como podemos ver no seguinte infográfico[^20]:

![mapa](/img/postagens/blockchain/map.png)

## Guia de Cripto-tokens

Muitos tokens e moedas digitais foram desenvolvidos nos últimos anos. Principalmente depois do lançamento do projeto Ethereum. Portanto, é difícil estar sempre atualizado sobre as funcionalidades de cada moeda. Felizmente, existem resumos que auxiliam neste processo[^21]:

![resumo](/img/postagens/blockchain/resumo.jpg)

E neste mundo de possibilidades, cabe a cada pessoa se manter informada sobre as soluções sendo criadas, bem como os seus benefícios e riscos.

## Finalmente

Chegamos às considerações finais sobre esta breve exploração dos sistemas de registro de informação. Inicialmente, motivados por desafios comerciais, estes sistemas passaram por transformações drásticas em suas estruturas, e hoje vivemos um momento ímpar nessa história com o nascer da tecnologia de blockchain. Apesar do Bitcoin ser hoje a aplicação mais conhecida no que se refere aos mecanismos de entrada tripla, ele ainda se limita ao campo da contabilidade por conta do seu aspecto financeiro. E mesmo não sabendo exatamente como tudo vai acontecer, é razoável imaginar que muitas outras revoluções estão por vir com o surgimento das DApps aqui mencionadas e de outras que ainda estão sendo criadas.

Obviamente, o impacto real destas aplicações dependerá das taxas de adoção entre a população do mundo e de como elas irão lidar com problemas como aqueles que mencionamos aqui e outros que ainda surgirão. A partir de uma visão optimista deste processo, a adoção de tais tecnologias será inevitável, uma vez que elas oferecem vantagens em relação à privacidade burocracia que as tornam mais atrativas. E tais vantagens só tendem a aumentar conforme as tecnologias e protocolos baseados em blockchain evoluem.

De maneira geral, as promessas aqui mencionada são realmente grandiosas. E um certo tom de ceticismo construtivo não faz mal. Porém, caso fosse possível voltar no tempo, eu adoraria ir à Veneza do final século XV e observar as reações dos mercantes da época em seu primeiro contato com a invenção do Frei Luca Pacioli. Na minha opinião, o sistema de contabilidade de entrada dupla deve ter parecido tão estranho para as pessoas daquele período quanto as tecnologias de blockchain são estranhas para as pessoas hoje em dia. Contudo, isso não diminui o impacto que aquela tecnologia teve no mundo. E eu acredito que o mesmo vale para as tecnologias de Registro Público de Entrada Tripla. Mas cabe ao tempo definir o que acontecerá. Por enquanto, é importante sempre tentar não tentar ficar para trás.

---

## Curtiu?

Então chegue junto e participe das trocas e conversas no nosso grupo no [<i class="fab fa-whatsapp"></i> WhatsApp](https://chat.whatsapp.com/4DzwqHLNBkMJ8gCQ3MEeLb){: .btn .btn--success} e/ou se inscreva na nossa Newsletter:

<!-- Begin MailChimp Signup Form -->
<link href="//cdn-images.mailchimp.com/embedcode/horizontal-slim-10_7.css" rel="stylesheet" type="text/css">
<style type="text/css">
	#mc_embed_signup{background:#fff; clear:left; font:14px Helvetica,Arial,sans-serif; width:100%;}
	/* Add your own MailChimp form style overrides in your site stylesheet or in this style block.
	   We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
</style>
<div id="mc_embed_signup">
<form action="https://emergir.us16.list-manage.com/subscribe/post?u=28e41725851da04e2014a8180&amp;id=06c739eed3" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">

	<input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="endereço de e-mail" required>
    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_28e41725851da04e2014a8180_06c739eed3" tabindex="-1" value=""></div>
    <div class="clear"><input type="submit" value="Inscrever-se" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
    </div>
</form>
</div>

<!--End mc_embed_signup-->

E caso você tenha gostado deste material e queira contribuir financeiramente com o Emergir, seguem os endereços das nossas carteiras de Bitcoin e Ethereum (Paypal e patreon também). Claro, as contribuições não financeiras também são <a href="mailto:emergir.co@gmail.com?subject=Oi do Emergir">muito bem vindas</a>.

| Bitcoin | Ether | Patreon | Paypal |
| :---: | :---: | :---: | :---: |  
| ![Bitcoin](/img/emergir_bitcoin_small.png) | ![Ether](/img/emergir_ether_small.png) | [![Patreon](/img/Patreon.png)](https://www.patreon.com/emergir) | [![Paypal](/img/Paypal.png)](https://www.paypal.me/emergir/) |

## Referências

- Vídeos:

1. https://www.youtube.com/watch?v=bBC-nXj3Ng4
2. https://www.youtube.com/watch?v=Lx9zgZCMqXE&feature=youtu.be
3. https://www.youtube.com/watch?v=SSo_EIwHSd4
4. https://www.youtube.com/watch?v=I2oNSs3c_WA
5. https://anders.com/blockchain/coinbase.html

- Textos:

[^1]: https://hackernoon.com/why-everyone-missed-the-most-important-invention-in-the-last-500-years-c90b0151c169
[^2]: https://iang.org/papers/triple_entry.html
[^3]: https://spectrum.ieee.org/energy/policy/the-ridiculous-amount-of-energy-it-takes-to-run-bitcoin
[^4]: https://www.buybitcoinworldwide.com/price/
[^5]: https://www.theguardian.com/business/2017/dec/02/bitcoin-bubble-the-warnings-from-history
[^6]: https://spectrum.ieee.org/energy/policy/the-ridiculous-amount-of-energy-it-takes-to-run-bitcoin
[^7]: https://en.wikipedia.org/wiki/Ethereum
[^8]: https://en.wikipedia.org/wiki/Smart_contract
[^9]: https://themerkle.com/what-is-the-ethereum-virtual-machine/
[^10]: https://bitcoinmagazine.com/articles/how-decentralized-applications-could-bring-the-blockchain-to-new-industries-1455324259/
[^11]: https://www.safaribooksonline.com/library/view/blockchain/9781491920480/preface01.html
[^12]: https://super.abril.com.br/ideias/o-mundo-esta-muito-complexo/
[^13]: https://coinsutra.com/dapps-decentralized-applications/
[^14]: https://www.inc.com/brian-d-evans/status-ico-raised-over-100-million-for-ethereum-powered-dapps-on-ios-and-androi.html
[^15]: https://elementus.io/blog/token-sales-visualization/
[^16]: https://complexitylabs.io/understanding-networked-economy/
[^17]: https://aragon.one/
[^18]: https://tse.bitnation.co/
[^19]: https://district0x.io/
[^20]: https://medium.com/birds-view/mapping-the-decentralized-world-of-tomorrow-5bf36b973203
[^21]: https://www.newline.co/

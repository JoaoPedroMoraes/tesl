# Dupla CASSIO e ERIC

- Cassio Trindade Batista (cassio.batista.13@gmail.com, [@cassiobatista](https://github.com/cassiobatista))
- Eric Felipe de Oliveira Pereira (eric.cbcc@gmail.com, [@eriicf](https://github.com/eriicf))

## Link para atividades

- Atividade01: [link](https://docs.google.com/spreadsheets/d/1KE8YOIUFBwCTb0rkOSTE5cIdBi0Fqv2-fO4vAG79OeI/edit#gid=122497701) e [link](https://docs.google.com/spreadsheets/d/1fV-axR9_C6V3LBRMxadurJQAEyGZCzFRBiEPeVW-tUo/edit#gid=122497701)
- Atividade02: [link](https://docs.google.com/document/d/1ealVO6usU1eS3idCyYAy9e8tJCLbtb6hvh2gnyrpOnU/edit)

## Atividade 03
1. Experimentando comandos do `git`:    
    - `commit`: Serve para confirmar as mudanças feitas nos arquivos.    
    - `push`: Comando para enviar as mudanças salvas localmente para o repositório.    
    - `pull`: Comando para atualizar o repositório local com a mais nova versão.    
    - `checkout`: Comando para alternar entre os branch de um projeto.    
    - `log`: Comando para mostrar o id, autor, data e mensagens dos commits.    
    - `shortlog`: Mostra por usuário o número de commits.    

2. Imprimir saída de terminal similar:    
```
user@host ~/git-all/tesl (master) $ git shortlog -se
     1	AugustofCravo <49079453+AugustofCravo@users.noreply.github.com>
     4	Caio Shimada Rabello <xcaiosr@gmail.com>
     2	CaioMFRodrigues <caiomfrodrigues@gmail.com>
     2	Cassio Batista <cassio.batista.13@gmail.com>
     2	EdsonECS <49080256+EdsonECS@users.noreply.github.com>
     9	Filipe Saraiva <mail@filipesaraiva.info>
    18	Filipe Saraiva <saraiva@ufpa.br>
     2	Gabriel Quinto <gabrielquintoand@gmail.com>
    53	Gustavo Pinto <gustavohenrique.86@gmail.com>
     2	João Ferreira <lubien1996@gmail.com>
     2	Julio Cesar <julio.developer10@gmail.com>
     3	Lakshamana <guitrompa1@gmail.com>
     4	Lucas Gabriel de Souza <lucassouzaufpa@gmail.com>
     2	Lucas Monteiro <tavares.lucas1996@gmail.com>
     2	Lucas Souza <lucassouzaufpa@gmail.com>
     1	Ronaldd <ronaldppinho@gmail.com>
    11	Ronan Silva <contato.ronansilva@gmail.com>
     5	ThayssaRocha <49079381+ThayssaRocha@users.noreply.github.com>
     5	Uriel Campos <31864637+urielfcampos@users.noreply.github.com>
     2	VictorBSI <38796125+VictorBSI@users.noreply.github.com>
     1	Wagner Negrão <35495925+wagnerfns@users.noreply.github.com>
     1	eriicf <eric.cbcc@gmail.com>
     7	leojsv <49284606+leojsv@users.noreply.github.com>
     1	lubien <lubien1996@gmail.com>
     3	reinald28 <49073381+reinald28@users.noreply.github.com>
     2	tavareslucas <tavares.lucas1996@gmail.com>
```
Explicação do comando:     
```bash
git shortlog \
    -s # mostra somente o número de commits por autor, suprimindo qualquer outra descrição textual
    -e # mostra o email de cada autor
```      

3. Fazer um PR que melhore documentação/tradução de um projeto:     
    - Fizemos mais que isso e implementamos duas funções em um projeto na área
   de processamento de linguagem natural (NLP, do inglês *natural language
   processing*). O projeto converte números para sua versão por extenso em
   forma de texto (e.g.: `68 -> "sessenta e oito"`), e tinha as
   funcionalidades de converter números cardinais, ordinais e moedas
   (*currency*) com os métodos `to_cardinal()`, `to_ordinal()` e
   `to_currency()`, respectivamente. Nós implementamos os métodos `to_date()`
   (Cassio) e `to_time()` (Eric) para converter de forma respectiva padrões
   de datas (e.g.: `12/5/1875 -> "doze de maio de mil, oitocentos e setenta e
   cinco"`) e horas 
   (e.g.: `14:55 -> "catorze horas e cinquenta e cinco minutos"`).

    - O link para o projeto foi encontrado no site do
   [CodeTriage](https://www.codetriage.com/savoirfairelinux/num2words).

    - Os métodos encontram-se dentro do arquivo
   [lang_PT_BR.py](https://github.com/cassiobatista/num2words/blob/master/num2words/lang_PT_BR.py),
   o qual encontra-se no repositório do
   [@cassiobatista](https://github.com/cassiobatista/num2words) que foi por
   sua vez forked to repositório original do
   [@savoirfairelinux](https://github.com/savoirfairelinux/num2words). 

   - Por fim, o PR encontra-se neste 
   [link](https://github.com/savoirfairelinux/num2words/pull/250).

## Atividade 04
O projeto escolhido foi o
[num2words](https://github.com/savoirfairelinux/num2words) reportado na
atividade passada (03) cujo link foi encontrado no CodeTriage.

1. Selecione e identifique em um projeto:     
    - links para instalação: existe
   [aqui](https://github.com/savoirfairelinux/num2words#installation). Como o
   projeto é em Python, existe a opção de instalar pelo `pip` e pelo `setup.py`,
   mas a documentação para instalação local por desenvolvedores que desejam
   contribuir é escassa.      
    - documentação: simples para uso
   [aqui](https://github.com/savoirfairelinux/num2words#usage), porém quase
   nenhuma documentação sobre as classes e métodos é fornecida, nem por meio de
   comentários no código fonte     
    - documentação traduzida: não existe, apenas em inglês no próprio `README`.     
    - como contribuir: existe o arquivo
   [CONTRIBUTING](https://github.com/savoirfairelinux/num2words/blob/master/CONTRIBUTING.md)
   com um modelo para preenchimento de informações sobre as features adicionadas
   nos pull requests e com instruções para a formatação do código (PEP8).

2. Revise uma página e sumarize os problemas encontrados:    
    - A página indica a Wiki para procurar infos adicionais, mas na
   [Wiki](https://github.com/savoirfairelinux/num2words/wiki) só há informações
   para os idiomas Japonês, Finlandês e Telugo     
    - O software dá suporte a tradução de números em muitos idiomas, porém a
   documentação encontra-se apenas em inglês      
    - O repositório não possui nenhum arquivo LICENSE, apenas um arquivo
   [COPYING](https://github.com/savoirfairelinux/num2words/blob/master/COPYING),
   o que não é muito intuitivo para iniciantes.

3. Teste a documentação e sumarize os problemas encontrados     
    - falta documentação para instalação por partes dos desenvolvedores. A
   página indica apenas como instalar para usuários, usando `pip` e
   `setup.py`, mas não há indicações de configuração de variáveis de ambiente
   necessárias para executar o projeto localmente (sem permissão de admin),
   tampouco como fazer debug     
    - Na instalação pelo `pip` no Python3 Debian 9.8 Stretch, a função de 
   conversão de _currency_ não funciona para português brasileiro (e.g.: o 
   comportamento esperado seria `32.20 -> trinta e dois reais e vinte centavos`, 
   porém ocorre um erro dizendo que a opção não existe). Ou seja, o repositório
   disponível pelo pip ainda aponta para uma versão desatualizada.

## Atividade 05
1. Justifique o que acontece se um projeto de software não tiver nenhuma licença
definida.    
    - o projeto é tratado como se fosse privado, sendo **TODOS** os direitos de
   uso e redistribuição reservados exclusivamente ao autor do projeto
   (*copyright*).
2. Acesse o site choosealicense, e estude ao menos cinco licenças. Justifique
porque o site da disciplina tem a licença que tem.    
    - [GPLv3](https://choosealicense.com/licenses/gpl-3.0/): é considerada
    _strong copyleft_ por ser recíproca total, ou seja, todo e qualquer
    software derivado de um projeto sob esta licença deverá ser também
   redistribuído sob a mesma licença. 
    - [LGPLv3](https://choosealicense.com/licenses/lgpl-3.0/): criada com base
   na GPL original, a LGPL é considerada recíproca parcial. O `L` refere-se à
   "lesser", o que significa que a licença é mais permissiva por admitir que
   módulos possam ser copiados e redistribuídos sob diferentes licenças,
   incluindo as mais restritas que não disponibilizam código-fonte.
    - [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/): é uma
   licença permissiva, que protege o autor no sentido de proibir forks de
   requerer patentes (direitos) sobre código eventualmente copiado e
   redistribuído. As notas de copyright do autor e a da licença Apache devem ser
   preservados (provavelmente no código), porém modificações e trabalhos maiores
   que tomem o projeto como base podem ser distribuídos em licenças diferentes e
   até mais restritas que não exijam distribuição do código-fonte.
    - [MIT](https://choosealicense.com/licenses/mit/): a licença MIT, conforme
   dito no blog [Exygy](https://exygy.com/which-license-should-i-use-mit-vs-apache-vs-gpl/),
   é uma licença permissiva que permite ao desenvolvedor "fazer o que quiser com
   o código", exigindo somente que o usuário mantenha as notas de copyright dos
   autores e da própria licença. Porém, a redistribuição podem ocorrer sob
   outras licenças, permitindo inclusive a não-divulgação dos códigos fontes, o
   que é de fundamental interesse para fins lucrativos (empresas, por exemplo).
    - [MPL 2.0](https://choosealicense.com/licenses/mpl-2.0/): a Mozilla Public
      License é uma licença recíproca parcial assim como a LGPL. O código fonte
   deve ser feito disponível e todos os arquivos, bem como suas eventuais
   modificações, devem ser disponibilizados sob a mesma licença. Porém, se o
   projeto forked for grande, é possível disponibilizá-lo sob uma diferente
   licença, incluindo as mais restritivas que não obrigam a compartilhar os
   fontes.
    - o site da disciplina possui licença *Creative Commons 4.0* pois não se
   trata de código de software propriamente dito. Conforme consta no
   [choosealicense.com](https://choosealicense.com/non-software/), "
   CC-BY-SA-4.0 is an open license used for non-software material ranging from
   datasets to videos." and "any open source software license or open license
   for media is applicable to software documentation."
3. Procure por projetos de software que utilize uma licença que não deveria ser
empregada em projetos de software.
    - O [Grupo FalaBrasil](https://gitlab.com/) possui um projeto de geração de
   ferramentas para processamento de linguagem natural (NLP) chamado
   [nlp-generator](https://gitlab.com/fb-nlp/nlp-generator) que não possui
   licença.    
   - O projeto [DNF-Patch](https://github.com/Kxnrl/DNF-Patch) utiliza uma
   licença chamada
   [GLWT](https://github.com/Kxnrl/DNF-Patch/blob/master/LICENSE) (good luck
   with that), que não é reconhecida pelo OSI e não consta na lista SPDX.

## Atividade 06

1. Encontre Roadmaps em pelo menos 3 projetos de software livre. Descreva os
planos de curto e longo prazo desse projeto.      
    - [SpaceVim](https://github.com/SpaceVim/SpaceVim): o SpaceVim é um plugin para "IDEzar" o editor de texto Vim, deixando-o com mais funcionalidades de interface gráfica. Seu roadmap é definido dentro do [site oficial](https://spacevim.org/roadmap/) e os desenvolvedores aparentemente se organizam assinalando milestones nas issues do GitHub A versão 1.1.0 é a mais recente, e a 1.2.0 está marcada para agosto de 2019. Infelizmente não há planos mais longos do que para esta data. Para a versão 1.2.0, já há 11 issues fechadas e apenas 2 abertas com os mais variados tópicos, como suporte à assembly, correção de bugs para C, enhanced features com suporte à Python Jupyter notebooks, etc.     
    - [Riot.IM](https://about.riot.im/): o Riot é uma ferramenta para comunicação e troca de mensagens entre grupos de trabalhos, similar ao Slack. Seu roadmap encontra-se no [blog oficial](https://medium.com/@RiotChat/whats-next-for-riot-web-be48f948c801) no Medium e não apresenta datas nem calendário, mas uma sequência ordenada de planos. O documento foi definido na forma de um kanban board, onde lista features em algo similar aos cards do Trello: `now`, `next`, `later` e `later still`. As mais recentes incluem melhorar o suporte à emojis, melhorar o design das salas (grupos), e facilitar a opção de confiar todos os dispositivos de uma mesma pessoa que já é conhecida (end to end encryption). As mais longas incluem consertar os módulos de VoIP (todas marcadas como "tarefas difíceis"), melhorar documentação da API e dos guidelines para contribuição, além de mudanças não específicas no design.
    - [TensorFlow](https://www.tensorflow.org/): o TensorFlow é a API do Google para deep learning que foi milagrosamente disponibilizada de forma open source. O roadmap encontra-se na seção de comunidade do [site oficial](https://www.tensorflow.org/community/roadmap) e foca na seção 2.0 da lib, que deve ser lançada ainda em 2019. As funcionalidades incluem tornar a plataforma mais fácil de aprender através da flexibilização da API (que dará a opção de mais auto nível ou total controle da lib pelo usuário); melhorar as unidades de tensor (TPU), que é a estrutura de dados central da biblioteca, dar mais suporte oficial à biblioteca Keras (que é um fork independente, mas se tornou muito popular), e criar um framework para machine learning de ponta a ponta (end to end). Para além da versão 2.0, o roadmap só fala em corrigir os eventuais bugs da versão em questão.     
2. Selecione 5 projetos de software livre famosos (pelo menos 1000 estrelas) e coloque os links para seus respectivos site, repositório de código fonte, bug tracking e ferramentas de comunicação.     
    - **Vim**: (un)popular and (but) famous text editor (16.5k stars).    
        - site: https://www.vim.org/     
        - source code repo: https://github.com/vim/vim  
        - bug tracking: label `defect` on [GitHub issues](https://github.com/vim/vim/issues?q=is%3Aopen+is%3Aissue+label%3Adefect)    
        - communication tools: lots of [mailing lists](https://www.vim.org/maillist.php), [conferences](https://www.vim.org/news/news.php)    
    - **Kaldi**: speech recognition tool (5.8k stars).    
        - site: https://kaldi-asr.org/    
        - source code repo: https://github.com/kaldi-asr/kaldi    
        - bug tracking: label `bug` on [GitHub issues](https://github.com/kaldi-asr/kaldi/labels/bug)    
        - communication tools: [forum](http://kaldi-asr.org/forums.html) on official website provides links for [dev](https://groups.google.com/forum/#!forum/kaldi-developers) and [help](https://groups.google.com/forum/#!forum/kaldi-help) google groups,
    - **PocketSphinx**: speech recognition tool (2.1k stars).    
        - site: https://cmusphinx.github.io/    
        - source code repo: https://github.com/cmusphinx/pocketsphinx    
        - bug tracking: label `bug` on [GitHub issues](https://github.com/cmusphinx/pocketsphinx/labels/bug) and issue tracker on [SourceForge](https://sourceforge.net/p/cmusphinx/bugs/).    
        - communication tools: group on [Telegram](https://t.me/cmusphinx) and [dev](https://t.me/cmusphinx) mailing list    
    - **Riot.IM**: messaging client software (2.9k stars)    
        - site: https://about.riot.im/    
        - source code repo: https://github.com/vector-im/riot-web    
        - bug tracking: labels `bug`, `p1`, `critical` and `FIRE` on [GitHub issues](https://github.com/vector-im/riot-web/labels)
        - communication tools: ['room' chat](https://riot.im/app/#/room/#riot:matrix.org) within the platform
    - **Keybase**: messaging client software (4.9k stars)    
        - site: https://keybase.io/    
        - source code repo: https://github.com/keybase/client    
        - bug tracking: issue tracker on a exclusive, independent [repo](https://github.com/keybase/keybase-issues); labels `bug` and `showstopper` on [GitHub issues](https://github.com/keybase/client/labels), but bugs are effectively managed through a system called Jira, which is [internal](https://github.com/keybase/keybase-issues/issues/2786#issuecomment-275767901)
        - communication tools: [group chat](https://keybase.io/team/keybasefriends) within the platform
3. Formas de priorizar requisitos
    - Riot.IM: O software de troca de mensagens priora suas issues por tags no GitHub, que vão de P1 à P5, e devem ser associadas à outras tags que remetem à bugs ou a seções particulares do software (e.g.: VoIP, UI, network, etc.). As de P1 normalmente referem à bugs de segurança, enquanto as de P5 são normalmente resolvidas a longo prazo, podendo conter também duplicações. Tudo isso está explicitado logo no [README](https://github.com/vector-im/riot-web) do repositório do GitHub.

## Atividade 07
1. Explique o que são _linters_     
    - Linters são normalmente definidos como software de análise de código (ou
debuggers) que analisam o fonte a procura de problemas de convenções e/ou
estilos de programação, vazamento de memória, bugs, dentre outros. Os linters
são importantes especialmente quando se pensa na manutenção do código ao longo
prazo, visto que o software normalmente não é mantido pela mesma pessoa para
sempre. Além disso, quando se trabalha em grupo, o uso de um analisador de
formatação ajuda membros do grupo na compreensão de código escrito pelos
colegas.
2. Indique um guia de boas práticas de codificação     
    - O Google possui um guia próprio para C++ que deve ser seguido para
integrar o desenvolvimento dos projetos open-source da empresa. O nome é 
[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html) e
define padrões para criação de headers com extensão `.h`, classes,
funções/métodos, nomenclatura de classes, métodos e variáveis, formatação,
conteúdo (scoping) de classes e métodos, etc. As diretrizes acompanham um código
em python chamado
[cpplint.py](https://google.github.io/styleguide/cppguide.html#cpplint) que atua
de forma automática em um código fonte para detecção de erros de convenção. Esse
guia também é utilizado em outros projetos de software livre, como o pacote de
reconhecimento de fala
[Kaldi](https://github.com/kaldi-asr/kaldi#development-pattern-for-contributors).
3. Indique um guia de boas práticas de codificação em frameworks.
    - O [Angular Style Guide](https://github.com/johnpapa/angular-styleguide) 
(24k estrelas) é um guia disponível no GitHub que tem o objetivo de prover
consistência no desenvolvimento de código colaborativo em JavaScript sobre o
framework Angular (o qual é usado no desenvolvimento de aplicações web em
ambientes desktop e mobile) através de um guideline de boas práticas.
    - O framework Joomla possui os seus próprios guidelines para escrita de
código. Na página [Joomla! Coding
Standards](https://developer.joomla.org/coding-standards/basic-guidelines.html)
há um pequeno tutorial para indentação, tamanho da linha, e diversos outros
links para mais informações.

## Atividade 08
1. Explique o são métodos ágeis e qual a sua importância no processo de desenvolvimento de softwares?
    - São alternativas à gerenciamento de projetos, mesmos do que não são relacionados a software, com o intuito de aumentar a produtividade e diminuir o tempo gasto durante o projeto. Trazem maior dinamisno e flexibilidade no desenvolvimento de software.
2. Procure um projeto e indique um commit que indique trabalho feito em par, ou seja, um commit que tenha multiplos autores.
    - Foi encontrado no repositório do projeto Kaldi, um [commit](https://github.com/kaldi-asr/kaldi/commit/0e5e07b27de7941b75cd982b7f710cea2d7d96a4) no qual foi verificado que foi realizado em par por dois contribuidores diferentes.
3. Procure um projeto e indique um commit que tenha Refactor e qual informe o nome da técnica empregada durante o refactor.
    - Encontramos um [commit](https://github.com/kylekatarnls/business-day/commit/10a88da0bd90d2dddadd292f379314278e754527) no qual foi verificado a realização de um refactor do código, onde foi refatorado a classe base e deixando o código com um menor tamanho.

## Atividade 09
1. Why unit tests?
    - The idea is to check if each unit (module, class, method, etc.) of a 
    software is executing as it should. This is important in order to increase
    the reliability of a software, as well as avoiding each individual in a 
    multi-collaborator project doesn't commit garbage that can compromise the 
    software as a whole. Unit tests nowadays are becoming something more like 
    a way of life that must be inherent to the programming practices of the 
    developer, since tests can also ensure the software is being well 
    maintained and sometimes good documented as well.  
2. What are the advantages of using CI?
    - When integrating software into a shared repo more often, the advantage is
    that an automated build can verify each new commit in order to look for
    possible errors (debugging). This is important for detecting errors and
    bugs more quickly, as well as for avoiding a lot of backtracking (let's say
    the dev won't need to look into several weeks old commits because the bug
    must probably had been originated on newer patches). This latter reason can
    be seen as another advatage, since the system wouldn't need to integrate
    lots of commits (which would most likely take a large amount of time), so
    integrating continuously can be seen as a good practice to release often 
    and for finding bugs often too. Additionaly, CI can help the project to 
    grow more solid, especially as the number of contributors also grow, 
    because this also allows devs to follow some patterns of coding that can
    make the source become more reliable, readable, documented... well-writen.
3. Add a method and its respective test into the `calculadora` project
    - [PR #14](https://github.com/wagnernegrao/calculadora-CI/pull/14) created 
    with a new method called `median()` to compute the median value of a vector 
    passed to the class `Operations`. Tests failed on Python 2.7 because the 
    our `median()` method depends on the `avg()` method for even-sized vectors
    and the division operation doesn't provide floats when computing two
    integers in that Python version.

## Atividade 10
1. "truck factor" vs "heroes"
    - Truck factor is a metric that is based on the number of important
  contributors on a project that have to be hit by a truck before the project
  enters the decline stage. In other words, the truck factor identifies the
  concentration of knowledge in software development environments, helping
  therefore at measuring how prepared a project is to deal with developer
  replacement/quit. Obviously, the lower the number of contributors the
  higher the risk of the project, since depending on only a few important people
  decreases the reliability and pretty much affects the future maintainability 
  of the source code. A low truck factor leads to delay in launching new
  releases and ultimately to the discontinuation of the entire project.        
    - A hero project is the one where the great majority of contributions (80% or 
  more) come from a few number of actual developers (less than 20%). Such kind
  of random and sporadic contributions are usually bad for the project since it
  affects the speed of development (which becomes normally slow) and promotes
  information loss (actually, it promotes misinformation).
2. Cite ao menos três **outras** métricas de saúde for FOSS projects    
A nice project community of the Linux Foundation called 
[CHAOSS](https://wiki.linuxfoundation.org/chaoss/metrics) has an exclusive 
committee for capturing metrics to assess OSS health and sustainability. 
Several metrics are defined on the project's 
[GitHub metric](https://github.com/chaoss/metrics) repo, such as:
    - Number of closed issues:
        - Quality criteria: maximize closed issues
        - Indicator: total number of issues
        - Healthy value: X issues closed by period of time or Y issues closed by source code
        - Alarm when: the number of closed issues is below X or Y
    - Communication inclusivity (see [this](https://github.com/chaoss/wg-diversity-inclusion/tree/master/focus-areas/communication) link)
        - Quality criteria: Listening, speaking and alternatives platforms for communication
        - Indicator1: is it allowed to ask text-based questions where BW is a challenged?
        - Indicator2: languages in accessible range for non-English speakers? captioning for the deaf (on live talks)?
        - Indicator3: can I choose from a variety of channels the one I want to communicate with the team?
        - Healthy value: If there exists at least one of the indicators above
        - Alarm when: none of them exist at all
    - Issue response time
        - Quality criteria: minimize time between a new issue is opened and a maintainer's response
        - Indicator: average time a issue is responded after it's been created
        - Healthy value: the issue has been responded after X hours with a satisfactory answery
        - Alarm when: the number of hours is above X
3. Por que os meios para medir qualidade de um projeto de software "tradicional" tem pouca aderência em projetos FOSS?
    - Métodos para medição de qualidade em projetos ditos como "tradicionais" não tem o mesmo resultado quando utilizados em projetos de software livre, pois a qualidade de um projeto de software livre é subjetivo. Um software livre pode atender todos os critérios de uma medição de qualidade "tradicional", porém, aos olhos da comunidade o projeto pode ser ruim, não atendendo as expectativas, não tendo uma boa comunidade de contribuidores. Além disso, pelo fato de serem vários contribuidores em um projeto de software, fica mais difícil que todos os contribuidores mantenham o mesmo padrão, mas, ainda existe a questão dos contribuidores não pagos, que quando são reprovados por algum erro, perdem a motivação para fazerem as correções necessárias e reenviar.

## Atividade 11

1. Informar o LOC de pelo menos 1 projeto usando a ferramenta cloc:
    - Foi escolhido o repositório Vega:

    ```
    -------------------------------------------------------------------------------
    Language                     files          blank        comment           code
    -------------------------------------------------------------------------------
    JSON                           375           1097              0        1072598
    JavaScript                     607          31092          13446         177457
    TypeScript                     133           1201           1122          18083
    Markdown                       202           3236              0          14198
    RobotFramework                   1              0              0           3219
    HTML                            16             65              0            784
    CSS                              2             35             14            649
    YAML                             3              5              2             41
    Bourne Shell                     2             12             10             38
    -------------------------------------------------------------------------------
    SUM:                          1341          36743          14594        1287067
    -------------------------------------------------------------------------------
    ```

    Com um LOC total de 1287067 linhas de código.
3. Proponha pelo menos três métricas para avaliar um projeto de software livre:
    - A primeira seria contabilizar o total de commits por projeto.
    - A segunda seria avaliar a qualidade dos commits realizados, pois nem sempre a quantidade é relacionada com a qualidade.
    - A terceira seria a relevância do projeto para a comunidade.

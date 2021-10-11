# Como se comunicar com pessoas e salas na Matrix através do XMPP


## Introdução

Para além do problema dos mensageiros proprietários, outro crivo é a falta de padronização ou os diversos padrões (o que deixa de padronizar as coisas) entre os próprios mensageiros livres, fazendo com que as pessoas e comunidades fiquem isoladas em seus protocolos. As pontes são uma alternativa que pode minimizar esse problema. Depois de um tempo sem escrever nada para o blog, resolvi escrever sobre essa possibilidade que descobri essa semana através da indicação do amigo Farribeiro: uma ponte entre os protocolos livres de mensagens instantâneas Matrix e XMPP. A comunicação entre os dois protocolos é possível graças à ponte [Bifröst](https://github.com/matrix-org/matrix-bifrost/wiki/Address-syntax) hospedada pelo [matrix.org](https://matrix.org/). Aqui vou falar sobre a comunicação de XMPP para Matrix e no final do texto deixarei a documentação para que o caminho contrário seja realizado.

Este breve texto será bastante pessoal e as vantagens e desvantagens que vou listar aqui são apenas opiniões e não estudos técnicos com alguma metodologia científica. Eu, particularmente, tenho certa inclinação a adotar o XMPP como meu protocolo mensageiro favorito. O protocolo é bem documentado, descentralizado e bastante democrático ao oferecer uma boa variedade de clientes para os mais diversos sistemas operacionais, que podem atender dos mais exigentes aos mais simplistas e escovadores de bits.

A forma como o protocolo Matrix funciona me incomoda um pouco, pois apesar da descentralização de servidores, muita coisa passa pelo matrix.org (além de a esmagadora maioria dos usuários centrarem suas contas nessa instância) e os clientes necessariamete precisam ser autorizados pelo Element, fazendo com que a criptografia só funcione com a intervenção do servidor principal. Também acho um pouco confuso o gerenciamento dos clientes no dia-a-dia (acho difícil de usar mesmo), todavia, o que importa é que o protocolo também é livre e você pode e deve usá-lo se for do seu agrado, priorizando-o frente à ferramentas proprietárias.

Por esses motivos que elenquei, entre outros, vejo XMPP como um protocolo extremamente interessante de se utilizar. Deixo aqui um texto da wiki comunitária [Libre Planet BR](https://libreplanet.org/wiki/Main_Page) com uma introdução ao XMPP: [https://libreplanet.org/wiki/XMPP.pt](https://libreplanet.org/wiki/XMPP.pt)

A ponte Bifröst infelizmente não permite mensagens criptografadas entre os protocolos, justamente por usarem padrões diferentes. Portanto, as comunicações entre pessoas serão sem criptografia e em salas criptografadas será possível apenas enviar mensagens, mas não recebê-las. Todavia, a maioria das salas são descriptografadas e minha experiência tem sido bastante positiva.

Outro ponto negativo é o fato de não ter histórico de mensagens que são enviadas enquanto seu cliente XMPP estiver fechado. A forma como amenizo isso é mantendo o cliente Conversations no celular, pois o software fica conectado enquanto o smartphone está ligado, possibilitando acompanhar as mensagens por lá.

Mesmo com esses fatores, é bastante interessante o fato de poder manter o uso de apenas um protocolo de mensagens e conseguir estabelecer uma comunicação viável com todos que preferem usar a Matrix. Portanto, sem mais delongas, mãos na massa!

## Como falar com outra pessoa na Matrix?

No seu cliente XMPP favorito, adicione a pessoa com quem você quer se comunicar na Matrix utilizando o seguinte padrão:

> nomedousuário_domíniodoservidor@matrix.org

Por exemplo, se o usuário na matrix for:

> @zezinho:matrix.org

Basta você adicioná-lo no cliente XMPP da seguinte forma:

> zezinho_matrix.org@matrix.org

## Como entrar em salas públicas na Matrix?

No seu cliente XMPP favorito, adicione a sala da Matrix que você deseja entrar seguindo o seguinte padrão:

> #nomedasala#domíniodoservidor@matrix.org

Por exemplo, se você desejar entrar na sala do Curso GNU com Debian do Professor Kretcheu, que tem a seguinte sala na Matrix:

> #cursognu:matrix.org

Basta você adicioná-la no cliente XMPP da seguinte forma:

> #cursognu#matrix.org@matrix.org

## Como fazer o caminho contrário (Matrix > XMPP)?

É possível se comunicar com pessoas e salas do XMPP através da Matrix com a ponte Bifröst com o seguinte padrão:

Chats privados:
>@_xmpp_USER=40DOMAIN:matrix.org

Salas públicas:
>#xmpp_MUCNAME_MUCDOMAIN:matrix.org

Todavia, apesar de eu ter conseguido adicionar as pessoas e salas, não consegui me comunicar. É possível que seja culpa da minha falta de intimidade com o protocolo e com o cliente, mas já vi diversas pessoas em salas XMPP utilizando contas da Matrix. Talvez alguém com um pouco mais de intimidade com o Element consiga sucesso.

Isso é tudo por hoje! Espero que eu tenha te ajudado a ser um pouco mais livre!

Abraços <3


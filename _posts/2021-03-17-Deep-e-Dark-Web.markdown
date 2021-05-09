---
layout: post
title:  Clearnet, Deep Web e Dark Web
date:   2021-03-18 08:32:20 +0300
description: Você sabe a diferença entre Deep Web e Dark Web? # Add post description (optional)
img: correios4.jpg # Add image post (optional)
tags: [Segurança]
author:
---
<center><strong>Você sabe a diferença entre Deep Web e Dark Web?</strong></center> 

<p>Usando uma resposta simples e resumida, <b>a Deep Web é utilizada para serviços privados e a Dark Web para fins ilegais</b>. Porém, uma precisa da outra para poder existir.</p>
<p>Mas não são somente essas terminologias que são importantes para definirmos estes tipos de redes e seus conteúdos.<br> 
Para explicar melhor os detalhes e da forma que acredito ser a mais adequada, <b>vamos dividir a Internet em CINCO tipos de arquiteturas</b> e veremos como se interconectam:</p>

<p><i><h5>OBS: As terminologias sobre redes e tecnolgias estão em mudança constante. Então matérias, de cunho sensacionalista ou não, utilizam suas formas de divisões de redes para facilitar o compreensão, porém nem sempre isso tem embasamento. Estou utilizando esta metodologia com base em quem se dedica a pesquisar isso a sério e também baseado na MINHA vivência com essas redes.<br>
Ou seja, estou escrevendo de uma forma didática para facilitar a compreensão do público que não faz parte desse nicho.</p></i></h5>

<p><b><h3>1. Arquiteturas Básicas e Independentes:</h3></b><br>
- <b>P2P (Peer-To-Peer)</b>:
É uma arquitetura de rede usada para compartilhamento de arquivos, onde cada nó da rede atua tanto como cliente quanto como servidor. Então, todos os computadores que estão utilizando o serviço, distribuem informações uns aos outros. Os exemplos mais didáticos são <i>Torrent</i> e <i>Blockchain</i>;</p>

<p>Um exemplo raramente comentado, é sobre o <b>FreeGate</b>. Ele é um software que utiliza um sistema P2P de proxys para permitir que países como China, Coréia do Norte, Síria e Emirados Árabes Unidos, possam ter acesso a sites bloqueados pelo governo. Seu funcionamento é semelhante a uma VPN, porém com rotatividade de IP e DNS dinâmicos para evitar o processo de censura.</p>

<p><center>
<img src="/salamandra/peer2peer.jpg" alt="Exemplo de Rede Peer-To-Peer (P2P)">
<figcaption><i>Exemplo de rede Peer-To-Peer (P2P)</i></figcaption>
</center></p>

<p> </p>

<p>- <b>VPN (Virtual Private Network):</b><br> 
A Rede Virtual Privada funciona como uma sobreposição de redes, onde <b>a conexão pública (Internet) passa por um "túnel" criptografado ou não, cujo a sua intenção serve para acessar uma determinada localidade e ter acesso aos seus serviços</b>, usualmente através de softwares. Os usos mais comuns incluem o acesso a conteúdos bloqueados por região ou home office. Comumente se utiliza de proxys ou algum tipo de criptografia para gerar e manter essa conexão.<br>
A utilização de VPNs é cercada de mitos de segurança. As únicas formas de "anonimato" que uma VPN predispõe são do servidor ver o IP da VPN e dependendo do serviço, propiciar algum tipo de criptografia e políticas de destruição de logs.<br>

<p><center>
<img src="/salamandra/vpn-works.jpg" alt="Exemplo comum de VPN, porém não muito correto">
<figcaption><i>Exemplo simples de VPN, porém não exatamente correto</i></figcaption>
</center></p>

<p> </p>

<p><b><h3>2. CLEARNET E SURFACE WEB:</h3></b><br>
- <b>Clearnet</b>:<br>
É um termo bastante complexo de se definir, mas em termos simples, é utilizado para se referir a <b>tudo aquilo que é publicamente acessível na Internet</b>, ou seja, que não é requerido conexões que preencham a lacuna de privaciade e/ou anonimato. Toda a Surface Web, boa parte da Deep Web e parcelas da Darknet (redes centralizadas, descentralizadas e de malha) e Darkweb, fazem parte da Clearnet.</p>

<p>A Deep Web, que tem seu conteúdo não indexado pelos motores de busca, é acessível públicamente desde que se forneça as credenciais, se necessário.<br>
Já na Darknet, você pode navegar em várias redes utilizando um navegador comum com uma VPN configurada, por exemplo. E o mesmo vale para redes e serviços que utilizam somente o protocolo IPv6 ao invés de IPv4.</p>

<p><b>Este site em questão, se encontra entre a Clearnet e a Deep Web</b>. Você só pode acessá-lo através do link direto ou digitá-lo na barra de endereços, porém ele não é indexado de forma direta pelos motores de busca.</p>   

<p>Segundo dados da IDC (Corporação Internacional de Dados), até 2025 o mundo produzirá <b>163 zettabytes de dados</b>, o que significa em conversão, <i>163 bilhões de Terabytes de dados</i>.</p>

<p> </p>

<p>- <b>Surface Web:</b><br>
É a porção da Internet que está disponível para o PÚBLICO GERAL, <b>cujo seu conteúdo só pode ser encontrado através dos motores de buscas</b> (Google, Bing, Yahoo, Yandex, Baidu). Então todo conteúdo que se torna <b>indexado</b> e de alguma forma <b>ranqueado</b>, faz parte da Surface Web. Estima-se que a Surface Web consista em apenas 10% das informações disponíveis na Internet (cerca de 5,3 bilhões de páginas, distribuídas em 1,8 bilhões de endereços únicos).</p>
<p><b>Exemplos:</b><br>
- Redes Sociais;<br>
- Canais de Entretenimento, como serviços de streaming e blogs;<br>
- E-Commerces populares;<br>
- Serviços Essenciais.<br>
</p>

<p>Aqui não há camadas de criptografia e proxys para termos privacidade. Claro, temos os protocolos de segurança HTTPS/HSTS e certificados digitais que nos ajudam contra ataques de MITM (Man In The Middle) e Sequestro de Sessão (Cookie Hijacking), mas aqui <b>estamos sendo rastreados O TEMPO INTEIRO</b> pelos provedores, servidores e pelo governo.<br>

<!-- <p><b>Métodos de Indexação de Conteúdo</b><br>
- -->



<p> </p>

<p><b><h3>3. DEEP WEB:</h3></b><br> 
É a parte da Internet onde seu conteúdo <b>não é indexado</b> pelos motores de buscas, mas que pode ser acessado via navegadores comuns através do requerimento de <b>credenciais</b>, se necessário. Estimou-se nos anos 2000 que o tamanho da Deep Web seria algo em torno de 400 a 550 vezes o tamanho da Surface Web, mas hoje sabemos que esses valores facilmente triplicam ou quintuplicam.<br>
Normalmente, se um site está bem configurado, os motores de buscas estão programados para não permitir que certos conteúdos sejam indexados por padrão. Se você pesquisar por <b>Google Dorks</b>, irá entender o problema disso tudo.</p>
<p><b>Exemplificando melhor</b>:<br> 
- Sites e sitemas internos de corporações, associações e comércios;<br>
- Redes e sistemas privados de escolas e universidades;<br>
- Bancos de Dados;<br>
- Sites protegidos por senha ou com acesso de "somente membros";<br>
- Páginas com conteúdos pagos, como Netflix e Amazon Prime;<br>
- Conteúdos de E-mails e conversas privadas em Redes Sociais;<br>
- Contas de banco e transações financeiras;<br>
- Repositórios privados, corporativos, acadêmicos, governamentais e científicos;<br>
- Documentos governamentais e registros médicos;<br>
- Servidores FTP;<br>
- Honeypots;<br>
</p>

<p> </p>

<p><b><h3>4. DARKNET:</h3></b><br> 
São redes sobrepostas a Internet que <i>só podem ser acessadas através de softwares, configurações, autorizações e frequentemente, não utilizando protocolos e portas comuns</i>. A Darknet foi construída com o propósito de proteger a privacidade do usuário, então tipicamente <b>descreve serviços descentralizados, distribuídos e de malha que podem utilizar, OU NÃO, grandes camadas de criptografia para o anonimato</b>. Além de que, suas páginas dentro dos seus respectivos serviços, só podem ser acessadas pelos mesmos.</p>

<p>Redes P2P e de VPNs são frequentemente utilizadas para que as conexões possam ser feitas.</p>

<p><b>Quem utiliza a Darknet?</b><br>
- Jornalistas, ativistas, ex-militares, políticos protestantes, trabalhadores do governo e insiders, que estão caminhando juntos para denunciar ferozmente a corrupção em seus respectivos campos;<br>
- Grupos Anti-Censura;<br>
- Residentes de Regimes Políticos Opressivos: Pessoas que vivem sob estes regimes, frequentemente não tem acesso a notícias, informações, dados sobre saúde e sustentabilidade sobre seus países. A Darknet oferece uma certa ajuda que possam obter informações cruciais das quais precisam, além de poderem espalhá-las para o resto da população;<br>
- Órgãos Governamentais e Agências de Inteligência Cibernética;<br>
- White Hats / Gray Hats / Black Hats;<br>
- Criminosos;<br>
- Curiosos.<br>

<p><b>É ilegal acessar a Darknet?</b><br>
Ela é utilizada para quem busca de alguma forma ter privacidade. Tanto o Wikileaks quanto jornais como o The Guardian e The New Yorker, tem hospedagens na Darknet com finalidades de capturar vazamentos de dados e documentos governamentais.<br>
Mas ao contrário do que se pensa, <b>nem tudo na Darknet é pautado para atividades ilícitas</b>. <br>
<b>Então se for com o objetivo de cometer atividades criminais, sim</b>.</p>

<p><b>Quais as vantagens de utilizar a Darknet?</b><br>
Sempre vai depender da rede que você vai navegar. No geral, podemos acessar conteúdos bloqueados por regiões, ausência de propagandas indesejadas, liberdade de expressão, vasto acervo de informações e em alguns casos, com menos uso de espionagem.</p>

<p><b>Quais as desvantagens de utilizar a Darknet?</b><br>
Em redes em que há uma incidência maior de criminalidade, há uma constante vigilância de Órgãos do Governo e Agências de Inteligência Cibernética. Mas sem entrar em termos muitos técnicos, podemos citar: Conteúdos sem regulamentação, falhas em configurações de servidores, ataques de correlação, malwares, DDoS, exposição de metadados, requests gravadas em logs e algoritmos fracos de criptografia.</p>

<p><b>O que é possível encontrar na Darknet?</b><br>
Vale lembrar que, não é porque o conteúdo não é indexado ou que precisa de parafernalhas para poder ter acesso, que ele seja interessante para toda a população.<br>
Todo o tipo de conteúdo que é possível achar na Darknet, também é possível de achar na Clearnet. A única diferença é a <b>QUALIDADE e QUANTIDADE</b> do conteúdo.</p>

<p><b>Primeiramente vamos utilizar exemplos amigáveis e para toda família:</b><br>
- Comunicação via criptografia para garantir privacidade e proteção;<br>
- Redes sociais, blogs, jornais, chats de texto e voz;<br>
- Grupos que lutam por suas causas;<br>
- Discussões acadêmicas e científicas;<br>
- Clube de livros e diversos outros fã-clubes;<br>
- Versões Darknet do Yahoo! Respostas;<br>
- Sistemas bibliotecários;<br>
- Vários tipos de mercados digitais;<br>
- Teorias da conspiração;<br>
- Cursos e MUITO material sobre tecnologia...</p>

<p><b>Agora veremos como é na maioria dos casos:</b><br>
- "Index of / "<br> 
- "This site is hosted" <br>
- "This site has been seized" <br>
- "ERR_CONNECTION_REFUSED"<br>
- "The connection has timed out"<br>
- "Invalid Address"<br>
- "99% Download > Download Error"<br>
- Esperar mais de 30min para atingir a quantidade mínima de nós para poder navegar;<br>
- Sites, serviços e redes clonados;<br>
- Servidores mal-configurados;<br>
- Fóruns abandonados;<br>
- VÁRIAS Creepypastas, FakeNews e Teorias da Conspiração;<br>
- VÁRIOS mercados aleatórios de pessoas anônimas, mas que 99% são golpe;<br>
- MUITA pirataria;<br>
- Malwares em PDFs;<br>
- Documentos vazados;<br>
- Todo tipo de pornografia que você pode imaginar <i>(mas é melhor não imaginar)</i>;<br>
- Chats de conteúdo duvidoso e/ou com mensagens cifradas;<br>
- Pessoas oferecendo serviços estranhos;<br>
- Drogas, drogas, drogas e mais drogas;<br>
- <b>E todo o resto do conteúdo que você encontra na Dark Web.</b></p>

<p><center>
<img src="/salamandra/this-site-has-been-seized.jpg" alt="This Site Has Been Seized">
<figcaption><i>Exemplo de site apreendido pelo FBI na rede TOR.</i></figcaption>
</center></p>

<p>Quando está se acessando a Darknet, dependendo do que você planeja fazer, podem haver várias opções de redes para escolher. Cada uma tem os seus usos, vantagens e desvantagens.<br>
Dependendo do que você planeja procurar, alguns mercados na Darknet podem algumas vezes serem desafiadores. Claro que podemos obter listas de links através da Clearnet e de outros serviços próprios da rede, mas se você busca coisas grotescas, terá que pesquisar muito.</p>

<p><b>Por que minha Internet fica lenta quando utilizo esses serviços?</b><br>
Ao invés de nos conectarmos diretamente com algum servidor, como funciona na Surface, cada pacote enviado pela rede precisa passar por um processo de criptografia e descriptografia cada vez que chega num servidor, nó ou retransmissor. Esse processo é muito custoso para rede e por isso a velocidade de banda por vezes pode diminuir em até 80%, dependendo do serviço.</p>

<p> </p>

<p><b><h3>Uma breve introdução de algumas redes e plataformas da Darknet:</h3></b>
<p>- <b>TOR (The Onion Router)</b>: É uma rede baseada em camadas de criptografia, como o próprio nome sugere, e permite tanto a navegação de sites da Surface quanto de domínios próprios, denominados ".onion".<br>
No momento em que você está estabelecendo uma conexão, estão sendo definidos os nós de proxy por onde sua conexão irá passar. Cada pacote enviado através desses nós é encriptado com uma cifra assimétrica. E cada pacote recebido pelo servidor através desses nós, ele faz um processo de "descascar" a última camada entregue, assim somente o rementente e o último nó sabem da mensagem original.<br>
Qualquer pessoa dentro da arquitetura do TOR pode estar disponível para ser um servidor ou nó/retransmissor. Então quanto mais pessoas estiverem utilizando-o, mais seguro ele se torna.<br>
Apesar de ser o mais famoso dessa lista com o seu uso principal em <b>contornar a censura</b>, ao longo dos anos tornou-se sinônimo de práticas criminosas.</p>

<!-- <p>- <b>I2P</b>: Em estudo.

<p>- <b>FreeNet</b>: Em estudo. -->

<p>- <b>NIPRNet, SIPRNet, JWICS e RIPRNet</b>: São redes privadas utilizadas pelo governo dos EUA (Departamento de Defesa) para compartilhamento de informações secretas, baseada na tecnologia da ARPANET.<br> 

<p>- <b>CJDNS</b>: Uma rede IPv6 sobreposta que provém encriptação de ponta-a-ponta, porém seu uso não é intencionado para o anonimato. Segundo a documentação, foi fundada na ideologia de que as redes deveriam ser fáceis de montar, protocolos deveriam ser mais escalonáveis e que a segurança deveria existir em todo lugar.<br>
Seu funcionamento é no próprio navegador através de instalação de pacotes na máquina e configurações de rede. Para entrar em alguma rede existente, você precisa se conectar com alguém que já esteja lá.</p>  

<p>- <b>Hyperboria (Project Meshnet)</b>: É uma rede distribuída ainda em desenvolvimento que utiliza CJDNS para conexão. Existem cerca de 2100 nós de conexões no Hyperboria. Segundo a documentação do projeto, eles buscam viabilizar uma alternativa para a Clearnet. E seu endereço utiliza o espaço "fc00::/8"</p>
</p>

<p>- <b>Galet</b>: Rede P2P descontinuada (mas que ainda há pessoas acessando) que por padrão é pública, porém há a opção de habilitar VPN. Sua conexão entre os nós não ocorre diretamente, ambos os lados devem decidir aceitar a conexão para poderem se comunicar. É utilizado para compatilhamento de arquivos e mensagens de texto.</p>

<p>- <b>RShare</b>: É uma rede P2P anônima Open-Source de compartilhamento de arquivos, disponível apenas para Windows. Na rede, o remetente e o destinatário não podem ser identificados, pois seus endereços de IP são ocultos.</p>  

<p>- <b>StealthNet</b>: É baseado no cliente RShare, mas que possui criptografia AES-256 de ponta-a-ponta. Não suporta hospedagem de serviços web.</p>

<p>- <b>GlobaLeaks</b>: É um plataforma P2P Open-Source que utiliza tanto retransmissões para a rede TOR quanto para HTTPS. Ela funciona como uma rede de denúncias, que então você pode criar uma iniciativa através de um nó para recolher ou fazer suas denúncias.</p>

<p>- <b>Tox</b>: É uma rede P2P descentralizada que oferece o sistema de criptografia NaCl de ponta-a-ponta como padrão. Ele pode ser usado para compartilhamento de arquvios, mensagens de texto, voz e vídeo, compartilhamento de tela e formação de grupos.<br>

<p>- <b>Twister</b>: É uma plataforma de microblogging descentralizada P2P, que é dividia em três redes sobrepostas. A primeira provém registro de usuários e autenticação baseada na arquitetura de rede utilizada no Bitcoin. A segunda é uma DHT que fornece armazenamento de chaves para recursos do usuário e a localização do nó para a terceira rede; que então é utilizado o P2P para enviar mensagens e notificações aos usuários.<br>
Em resumo, <b>é um Twitter da Darknet</b>.</p>

<p>- <b>MORPHiS</b>: Era um sistema P2P distribuído em desenvolvimento utilizado para compartilhar e criptografar arquivos. Havia também um sistema de E-mail, chamado D-Mail, que utilizava protocolos de criptografia anti-spam, chamado de Dpush. <b>MORPHiS foi descontinuado devido o assassinato do criador, Sam Maloney</b>. Ainda é possível ter acesso a rede, porém sem mais implementações desde 2016.</p>   

<p>- <b>Infinit</b>: É uma rede P2P comercial utilizada para compartilhamento de arquivos de qualquer tamanho. Sua infraestrutura de armazenamento heterogênea permite agregar vários tipos de recursos, seja Amazon S3, OpenStack Swift, Discos Locais, Discos em RAID e qualquer outro dispositivo que possa necessitar de armazenamento. Apesar de não ser uma rede anônima, pois necessita de cadastro via E-mail, utiliza encriptações RSA e AES para criptografar os blocos de dados e as comunicações entre os nós. Parte da biblioteca de software é disponibilizada em Open-Source e também possui a opção de armazenamento gratuito.</p>

<!-- <p>- <b>ECNet (Antiga "Alienet")</b>: Em estudo.

<p>- <b>Maelstrom</b>: Em estudo.

<p>- <b>Resilio</b>: Em estudo.

<p>- <b>Osiris</b>: Em estudo.

<p>- <b>Ricochet</b>: Em estudo.

<p>- <b>Soulseek</b>: Em estudo.

<p>- <b>Perfect Dark</b>: Em estudo.

<p>- <b>DemonSaw</b>: Em estudo.

<p>- <b>Netsukuku</b>: Em estudo.

<p>- <b>OneSwarm</b>: Em estudo.

<p>- <b>Anomos</b>: Em estudo.

<p>- <b>Tribler</b>: Em estudo.

<p>- <b>Syndie</b>: Em estudo.

<p>- <b>Retroshare</b>: Utilizado para compartilhamento de arquivos, chat, forums, e-mail. 

<p>- <b>anoNet</b>: É uma rede descentralizada P2P, semelhante a Freenet, que utiliza-se de VPNs e protocolo BGP. 

<p>- <b>GnuNet</b>: Utilizada para armazenamento e distribuição de arquivos de forma anônima.

<p>- <b>Omemo</b>: Plataforma social de distribuição de arquivos.

<p>- <b>Phantom</b>: Em desenvolvimento. Utiliza serviços anônimos e faz uso do IPv6 nativamente.

<p>- <b>FreedomBox</b>: Em desenvolvimento. Cria servidores pessoais para comunicações de redes sociais, e-mail e audio/video.

<p>- <b>Telex</b>: Uma nova maneira de passar pela censura da Internet.

<p>- <b>Project Byzantium</b>: Distribuição bootável do Linux que monta uma rede de malha independente do hardware que você tiver.

 -->

<p>- <b>Freifunk</b>: É uma rede alemã de wireless comunitário que conta com 400 comunidades locais e mais de 41.000 pontos de acesso. Os usos da Freifunk são com base no princípio de Neutralidade de Redes, de garantir acesso ao conhecimento e informação livremente e também com o uso de tecnologias Open-Source.</p>   

<p>- <b>ChaosVPN</b>: Utiliza redes Tinc como base. É uma rede para que Gray/Black Hats e ativistas possam se comunicar via intranet, separando-os da Internet. Apesar do foco não ser o anonimato, é desenhada para que ninguém veja o tráfego das outras pessoas. Os serviços disponíveis variam entre VoIP, IRC, Minecraft, Torrent e FTP.</p> 

<p>- <b>DN42 (Decentralized Network 42)</b>: É uma rede que utiliza VPNs dinâmicas baseado em tecnologias como BGP e DNS. Os usuários da rede podem se conectar através de tuneis de IPsec, OpenVPN, GRE e Tinc, e também se interconectarem com outras redes, como ChaosVPN e Freifunk. 

<p>- <b>Hypercore Protocol (Antiga "Dat")</b>: É uma rede distribuída de compartilhamento P2P Open-Source. É focada em interesses públicos, como ciência, tecnologia, blockchain e outras criptomoedas.</p>

<p>- <b>StegoShare</b>: Um software de esteganografia que pode ser utilizado para compartilhamento de arquivos.

<p> </p>

<p>Não abordarei <i>"Como navegar de forma segura na Darknet"</i> pois já existem milhares de páginas demonstrando isso. Apenas tenha em mente o que você pretende fazer, já que há centenas de redes com suas vantagens e desvantagens.</p> 

<p> </p>

<p><b><h3>5. DARK WEB:</h3></b><br>
É aqui onde Órgãos do Governo e Agências de Inteligência Cibernética tem o seu maior interesse. Basicamente é uma pequena porcentagem, cerca de 3.4% do tráfego total da Internet inteira, que <b>é composta somente por atividades criminosas e conteúdos "não amigáveis"</b>.<br>
Tudo o que encontramos aqui é facilmente encontrado na Clearnet, porém a única diferença é o uso de camadas de criptografia e anonimato.</p>

<p>Querendo ou não, a popularização das criptomoedas (como Bitcoin, Dash, Litecoin e Monero), começou na Dark Web. Pois, já que são moedas descentralizadas e teoricamente não podem ser rastreadas devido aos seus algoritmos de criptografia, os consumidores da rede acabam por adotar este tipo de empreendimento.</p>

<p> </p>

<p><b>O que podemos encontrar na Dark Web:</b><i> (não necessariamente com facilidade e autenticidade)</i></p>
<p>- <b>Maconha</b>: Todas as espécies, variantes e "potências" podem ser encontradas aqui. Tipicamente os preços são bem abaixo do valor comercial e isso se tornou uma porta de entrada para que "maconhistas" utilizem esses serviços anônimos para se obter facilmente;</p>

<p>- <b>Remédios Controlados e Anabolizantes</b>: Um mercado com bastante consumidores na rede. Esses remédios podem ser adquiridos por centavos, que variam desde analgésicos, remédios para disfunção erétil quanto como coqueteis quimioterápicos;</p>

<p>- <b>Drogas e Narcóticos</b>: A Dark Web é a casa para você encontrar qualquer tipo de droga que você imagina. Frequentemente os consumidores procuram por maconha, cocaína, heroína, bala, doce, escopolamina, DMT, GHB, cogumelos, crack, ketamina e anfetaminas;</p>

<p>- <b>Venenos e Substâncias Tóxicas</b>: Os usos do Ricino na série Breaking Bad inspiraram vários casos criminais envolvendo ele e outras substâncias similares. Mercados da Dark Web, quando isso começou a se popularizar, disponibilizaram lotes em massa de Ricino para serem comprados;</p>

<p>- <b>Urânio e outros elementos químicos e/ou radioativos</b>: Um dos casos mais bizarros documentado foi a venda de Urânio na Dark Web. Não se pode afirmar se o site era de fato legítimo, mas também é possível encontrar outros elementos como polônio, tório, arsênio, enxofre, vários tipos de ácidos, "matéria-prima" para bombas e outros elementos que são utilizados para criar armas de elite.</p> 

<p>- <b>Armas, Munições e Proteção Corporal Estilo SWAT</b>: É possível encontrar várias réplicas de AK-47, lança-mísseis, lança-granadas e ainda proteções caseiras estilo SWAT, que são utilizadas durante campanhas militares;</p>

<p>- <b>Explosivos</b>: Em conjunto nos sites de vendas de armas, encontra-se também dinamites e IEDs (Bombas caseiras e improvisadas) utilizando os mais variados tipos de materiais, desde pólvora e nitroglicerina a elementos radioativos. É mais comum encontrar receitas de bombas e "manuais terroristas";</p>

<p>- <b>Artigos Contrabandeados de Luxo e Réplicas</b>: Qualquer réplica de qualquer marca pode ser encontrada e por preços extremamente baixos. Entre elas estão Gucci, Rolex e Louis Vuitton;</p>

<p>- <b>Geradores de EMP</b>: Neste caso, Geradores de Pulso Eletromagnético são utilizados para causar pane em dispositivos eletrônicos próximos. Este tipo de mercado é muito consumido pela China, onde os usuários costumam adicionar créditos em máquinas caça-níqueis, em cassinos e salas de jogos, para então utilizarem o EMP para enganar a máquina e obterem ganhos máximos;</p>

<p>- <b>Venda de Cidadanias e Passaportes Falsos</b>: Tipicamente para o Reino Unido, Canadá e EUA, e com seus preços variando na faixa de $1200;</p>

<p>- <b>Certificados e Diplomas Falsificados</b>: Se você sempre quis ter um diploma de Harvard, Stanford, ou Yale, você pode conseguir rapidamente e por preços acessíveis;</p>

<p>- <b>Cartões de Crédito</b>: Um mercado bastante grande na Dark Web. Tipicamente são vendidos em lotes e estão preparados para a maioria dos fins ilícitos;</p>

<p>- <b>Contas Roubadas e Invadidas</b>: É comum achar contas de Netflix e Spotify que estão sendo vendidas por centavos. Contas de Uber são utilizadas para escapar de fiscalizações e contas de Paypal são livres para retirar todo o dinheiro;</p>

<p>- <b>Cupons Falsificados</b>: Cupons que oferecem desde $0,50 a >20% de desconto, também são um negócio em expansão na Dark Web. Os cupons são geralmente de empresas grandes e que, para se obter de maneira fraudulenta, utiliza-se da impressão de códigos de barras aparentemente legítimos de outros cupons;</p>

<p>- <b>Serviços de Impressão 3D</b>: Muito utilizado para criar dinheiro falsificado, aparelhos para fraudar cartões, armas, munições e tudo o que o consumidor necessitar;</p>

<p>- <b>Números de Seguro / Previdência Social</b>: Alguns mercados vendem números da previdência ou seguros sociais que incluem scores de crédito superiores a 750 por bons preços e frete grátis;</p>

<p>- <b>Bilhetes de Loterias de Criptomoedas</b>: Frequentemente o Bitcoin e outras criptomoedas são utilizadas para jogos de azar e outras atividades ilícitas semelhantes, porém existe uma indústria artesanal de loterias de criptomoedas que atrai muitos consumidores;</p>

<p>- <b>Dados e Documentos de Governos</b>: Parece que se tornou de praxe dos Black Hats fazerem vazamentos de dados aqui no Brasil, pois é um mercado em constante crescimento na Dark Web. Milhares de consumidores buscam lista de E-mails, CPFs, cartões de crédito, telefones e uma insana lista de outros dados confidenciais;</p>

<p>- <b>Acompanhantes de Elite</b>: É meio curioso contratar este tipo de serviço na Dark Web. Mas se você tem certeza que não será usado em Tráfico de Pessoas, pode ser uma boa escolha;</p>

<p>- <b>Serviços de Black Hat</b>: Mercado onde consumidores contratam "crackers" para invadirem sites, sistemas de empresas, escolas e comércios. Porém, não é raro a pessoa que faz esse tipo de serviço atacar o próprio consumidor;</p>

<p>- <b>Softwares / Malwares / Exploits</b>: Além da pirataria de softwares comerciais, existe uma gama de malwares e "kit exploits" a serem vendidos na Dark Web. Consumidores geralmente procuram por falhas "Zero-Day" e Ransomwares, com o objetivo de lucrar em cima de resgates via criptomoedas;</p>

<p> <p>

<p><b>Daqui para baixo entraremos em tópicos desagradáveis.</b></p>

<p>- <b>Tutorais e Manuais</b>: Antigamente era comum encontrar no ParaZite (site da rede TOR) vários tutoriais sobre as mais diversas coisas. Isso incluia vandalismo, criação de bombas, manual do suicídio indolor, lockpicking, roubo, necrofilia, canibalismo, terrorismo, abuso de menores, violência sexual, anarquia, blasfêmia e várias outras coisas não muito agradáveis;</p>

<p>- <b>Vídeos de Abuso e Mutilação de Cadáveres</b>: Não que o "TheYNC", "XRares" ou "DeathAddict" não tenham coisas parecidas na Clearnet, mas aqui <i>"temos mais opções"</i>, digamos assim;</p>

<p>- <b>Vídeos de Maus-Tratos aos Animais</b>: Nada de diferente do que você encontra em grupos de WhatsApp, Telegram ou Facebook;</p>

<p>- <b>Vídeos de Tortura, Estupro e Assassinato</b>: Também não muito diferente do que você encontra nos sites citados acima;</p>

<p>- <b>Serviços de Bate-Papo e para Encontrar "Amigos"</b>: Com certeza esse é o maior perigo da Dark Web. Nas redes sociais comuns já é um pouco complicado de capturar abusadores, aqui eles têm o benefício da criptografia para ajudar a esconder seus traços. Não é raro de encontrar salas de bate-papos que tem avisos proibindo pornografia infantil, mas que sempre há algum espertinho divulgando links e/ou conversando com outros abusadores, seja abertamente ou com mensagens cifradas.<br>
Geralmente utilizam serviços como o TOR, Tox, Retroshare e I2P para se comunicarem;</p>

<p>- <b>Pornografia Infantil (CP - Child Porn)</b>: Deixei este tópico justamente em último por ser <b>o mais sensível</b> de abordar, pois infelizmente, este tipo de conteúdo desprezível é facilmente encontrado na Clearnet e aos montes, seja em sites como "Caiu Na Net" aqui no Brasil, quanto como em sites Russos e Asiáticos. Porém, além do "revenge porn" praticado com menores, temos a questão de que na Dark Web não há limites.</p>

<p><b>Operação Darknet</b>:<br>
Entre 2013 e 2016, a PF do Rio Grande do Sul realizou a primeira investigação sobre Pornografia Infantil do Brasil na rede TOR. A operação resultou na busca e apreensão de mais de 100 pessoas em 18 estados brasileiros e em países como Itália, Portugal, Colômbia, México e Venezuela. Poucas polícias no mundo obtiveram êxito nas investigações, como o FBI, Scotland Yard e a Polícia Federal Australiana.</p>
 
<p> </p>

<p><b><h3>RESUMO</h3></b><br>
De certo modo, tanto a Deep Web quanto a Dark Web, ainda chama muito a atenção de curiosos devido as várias <b>lendas</b> que surgiram desde o aparecimento dessas redes. Porém, por vezes <b>essa curiosidade pode acabar colocando o usuário em sérios riscos de privacidade</b>, caso ele não saiba o que está fazendo. Afinal, <b>não existe 100% de anonimato na Internet</b>. E não é porque o conteúdo não aparece nas buscas que ele é de fato interessante, mas ele está lá por algum motivo.</p>

<p>A Surface Web ainda é a rede mais perigosa de todas, comparando com todas as outras. Não temos noção o suficiente de como nossos dados estão sendo administrados e rastreados o tempo todo. Mesmo com os melhores protocolos de segurança e os melhores sistemas de defesa, <b>todos somos vítimas em potenciais</b>, pois o atacante só quer uma única coisa: <b>PODER</b>.<br>
É muito mais fácil se tornar uma presa na Surface Web do que na Dark Web. Pois, <b>grande parte da população não tem noções mínimas ou básicas de segurança da informação</b>, ou porque acham que nunca serão vítimas por pensarem que o atacante não teria interesse na vida delas, ou simplesmente por <b>ignorância</b>.</p>

<p>Portanto, para o público geral que vive a sua vida tranquila, <b>não há nada de interessante na Darknet</b> pelo qual valeria o motivo de se arriscar.</p>

<p>Para os curiosos, pesquise muito antes de fazer qualquer coisa precipitada, <b>pois isso pode lhe custar muito caro depois</b>.</p>

<p>Para as pessoas que têm interesse em cuidar da sua privacidade, se a sua vida toda for baseada na Surface Web e subitamente você mudar de rede e continuar a fazer as mesmas coisas na Darknet, <b>infelizmente só terá efeitos negativos</b>. Então concentre seus esforços em tomar medidas na Surface Web e policie a si mesmo.</p>

<p>E para os criminosos... Não adianta utilizar serviços como VPNs, Tails, Whonix ou o próprio TOR, <b>se não há nenhuma tecnologia existente até hoje que torne uma pessoa invisível na Internet</b>. Para o seu provedor e servidores, isso só será mais um indício que há um comportamento estranho na rede e será passível de <b>investigação ou ataques de correlação</b>. Por mais que serviços tenham suas políticas de privacidade, como o DuckDuckGo ou NordVPN, <b>qual a garantia que você tem de que seus dados estão seguros com essas empresas?</b></p>

<p> </p>

<p>_________________________________________________________________________________</p>
<p><b>REFERÊNCIAS</b></p>
<p>- <b>Canais do Youtube: <a href="https://www.youtube.com/channel/UCGObNjkNjo1OUPLlm8BTb3A">Fábrica de Noobs (Natanael Antonioli)</a>, <a href="https://www.youtube.com/c/STACKZOFICIAL/videos">STACKZ / Gustavo Pinheiro</a>, <a href="https://www.youtube.com/channel/UCbuxUJVokSf4V0Nmj_kWq0A/videos">Deep Web Brasil</a>, <a href="https://www.youtube.com/c/SomeOrdinaryGamers/videos">SomeOrdinaryGamers (Mutahar Anas)</a>, <a href="https://www.youtube.com/channel/UCyEXkaNrS9TNiTnyhKj3iQA/videos">Irfan Shakeel</a></b><br> 
- <b>RETSKIN, Sion</b>. Hands-On: Dark Web Analysis. Packt, 2018.<br>
- <b>KOZAKIEWICZ, Dilmar José</b>. Deep Web e Segurança da Informação: Uma análise e seus impactos na sociedade e nas organizações. UTFPR, Curitiba, 2018.<br>
- <b>PINHEIRO, Débora</b>. Crime de Pornografia Infantil na Deep Web: Medidas Legais para Combate e Proteção Infantojuvenil. UNAMA, 2020.<br> 
- <b><a href="http://www.mpf.mp.br/rs/sala-de-imprensa/docs/outros-documentos/operacao-darknet">Ministério Público Federal - Operação Darknet</a><br>
- <a href="http://www.pf.gov.br/agencia/noticias/2016/11/pf-combate-crime-de-pornografia-infantil-na-deep-web">PF combate crime de pornografia infantil na Deep Web</a><br>
- <a href="https://quod.lib.umich.edu/j/jep/3336451.0007.104?view=text;rgn=main">White Paper: The Deep Web - Surfacing Hidden Value</a><br>
- <a href="https://blog.radware.com/security/2016/04/darknet-101/">Darknet 101: An Introduction to The Darkest Places Online</a><br>
- <a href="https://www.gdatasoftware.com/guidebook/what-is-the-darknet-exactly">What actually is the Darknet?</a><br>
- <a href="https://lifehacker.com/how-can-i-stay-anonymous-with-tor-1498876762">How Can I Stay Anonymous with Tor?</a><br>
- <a href="https://us.norton.com/internetsecurity-emerging-threats-what-is-the-deep-dark-web-30sectech.html">What is the dark web</a><br>
- <a href="https://us.norton.com/internetsecurity-how-to-how-can-i-access-the-deep-web.html">How to safely access the deep and dark webs</a><br>
- <a href="http://www.internetfreedom.org/FreeGate.html">Documentação do FreeGate</a><br>
- <a href="https://digital.com/online-privacy/deep-dark-web/">Enter The Deep & Dark Web If You Dare (And Get Ready For A Surprise)<a><br>
- <a href="https://docs.meshwith.me/">Documentação do Hyperboria</a><br>
- <a href="https://github.com/cjdelisle/cjdns/blob/master/doc/Whitepaper.md">Documentação do CJDNS</a><br>
- <a href="https://dat.foundation/about/foundation/">What is Dat?</a><br>
- <a href="https://wiki.freifunk.net/">Freifunk Wiki</a><br>
- <a href="https://wiki.hamburg.ccc.de/ChaosVPN">Chaos Computer Club - ChaosVPN</a><br>
- <a href="https://armypubs.army.mil/epubs/DR_pubs/DR_a/pdf/web/ARN17362_P25_2_1_Admin_FINAL.pdf">Army Cross Domain Solution and Data Transfer Management</a><br>
- <a href="http://galet.sourceforge.net/">Página do Galet</a><br>
- <a href="https://zilionweb.wordpress.com/rshare/">Zillion Web - RShare</a><br>
- <a href="https://www.globaleaks.org/support/faqs/">Globaleaks FAQ<a><br>
- <a href="https://tox.chat/index.html">Página Inicial do Tox<a><br>
- <a href="http://twister.net.co/faq/">Twister FAQ</a><br>
- <a href="https://morph.is/v0.8/#learn">Página Inicial do MORPHiS</a><br>
- <a href="https://www.vice.com/pt/article/d7x7wy/por-que-a-policia-canadense-matou-um-hacker-aparentemente-inofensivo">Por que a polícia canadense matou um hacker aparentemente inofensivo? (O Criador da Rede MORPHiS, Sam Maloney)</a><br>
- <a href="https://infinit.sh/documentation/overview/">Overview da Rede Infinit</a><br>


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
Para explicar melhor os detalhes, <b>vamos dividir a Internet em SETE tipos de redes</b> e veremos como se interconectam:</p>
<p><b><h3>1. P2P (Peer-To-Peer):</h3></b><br>
É uma arquitetura de redes usada para compartilhamento de arquivos, onde cada nó da rede atua tanto como cliente quanto como servidor. Então, todos os computadores que estão utilizando o serviço, distribuem informações uns aos outros. Os exemplos mais didáticos são <i>Torrent</i> e <i>Blockchain</i>;</p>

<p>Um exemplo raramente comentado, é sobre o <b>FreeGate</b>. Ele é um software que utiliza um sistema P2P de proxys para permitir que países como China, Coréia do Norte e Sul, Síria, Vietnam, Irã e Emirados Árabes Unidos, possam ter acesso a sites bloqueados pelo governo. Seu funcionamento é semelhante a uma VPN, porém com rotatividade de IP e DNS dinâmicos para evitar o processo de censura.</p>

<p><center>
<img src="/salamandra/peer2peer.jpg" alt="Exemplo de Rede Peer-To-Peer (P2P)">
<figcaption><i>Exemplo de rede Peer-To-Peer (P2P)</i></figcaption>
</center></p>

<p><b><h3>2. VPN (Virtual Private Network):</h3></b><br> 
A Rede Virtual Privada funciona como uma sobreposição de redes, onde a conexão pública (Internet) passa por um "túnel" onde se torna privada, normalmente através de softwares. <b>O real uso da VPN está em acessar uma determinada localidade ou servidor para obter acesso aos seus serviços</b>, como acessar conteúdos bloqueados por região ou home office, por exemplo. Comumente se utiliza de proxys ou criptografia para se manter uma conexão.<br>
A utilização de VPNs é cercada de mitos de segurança. As únicas formas de "anonimato" que uma VPN predispõe são do servidor ver o IP da VPN e dependendo do serviço, propiciar algum tipo de criptografia e políticas de destruição de logs.<br>
<i>(Nos próximos posts abordarei "O Problema das VPNs" de forma mais completa e mitigando vários quesitos de segurança)</i></p>

<p><center>
<img src="/salamandra/vpn-works.jpg" alt="Exemplo comum de VPN, porém não muito correto">
<figcaption><i>Exemplo simples de VPN, porém não exatamente correto</i></figcaption>
</center></p>

<p><b><h3>3. CLEARNET></h3></b><br>
É um termo bastante complexo de se definir, mas em termos simples, é utilizado para se referir a <b>tudo aquilo que é publicamente acessível na Internet</b> e a Surface Web é somente uma parte dela</i>, que não é um sinônimo.</p>
<p>A sua complexidade se dá pelo fato que muitos conteúdos estão acessíveis publicamente através de softwares específicos, mas que não precisam de anonimato ou camadas de criptografia para se ter acesso.<br>
Isso quer dizer que as ferramentas de OSINT (Open-Source Intelligence) e Análise de Vulnerabilidades, como Shodan e Nessus, também estão incluídas, afinal as informações estão disponíveis publicamente.</p>

<p>Então muitos serviços ditos pertencentes a Darknet, na verdade tem a sua base na Clearnet e podem oferecer conjuntamente a opção de serem estruturados na Darknet.<br>
Uma parte dos serviços P2P, por exemplo, não necessitam de anonimato e estão acessíveis ao público.<br>
O mesmo vale para redes e serviços que utilizam somente IPv6 ao invés de IPv4. Você apenas precisa verificar se no seu provedor está implantado o endereçamento IPv6 e ativá-lo.</p>

<p>É causa desses fatores e detalhes que se torna complexo de definir os seus limites.</p>

<p><b><h3>4. SURFACE WEB:</h3></b><br>
É a porção da Internet que está disponível para o público geral, <b>cujo seu conteúdo só pode ser encontrado através dos motores de buscas</b> (Google, Bing, Yahoo, Yandex, Baidu). Então todo conteúdo que se torna <b>indexado</b> e de alguma forma <b>ranqueado</b>, faz parte da Surface Web. Estima-se que a Surface Web consista em apenas 10% das informações disponíveis na Internet (cerca de 5,24 bilhões de páginas).</p>
<p>Exemplos:<br>
- Redes Sociais;<br>
- Canais de Entretenimento, como serviços de streaming e blogs;<br>
- E-Commerces populares;<br>
- Serviços Essenciais.<br>
</p>

<p><b><h3>5. DEEP WEB:</h3></b><br> 
É a parte da Internet onde seu conteúdo <b>não é indexado</b> pelos motores de buscas, mas que pode ser acessado via navegadores comuns e não necessitam de ferramentas especiais. O máximo que pode ser requerido é suas <b>credenciais</b>, ou seja, informações de Login e Senha.</p> 
<p>Exemplificando melhor:<br> 
- Playlists e videos não listados do YouTube;<br>
 Bancos de Dados;<br>
- Conteúdos de E-mails e conversas privadas em Redes Sociais;<br>
- Contas de banco e transações financeiras;<br>
- Repositórios privados, corporativos, acadêmicos, governamentais e científicos;<br>
- Documentos governamentais e médicos...<br>
</p>



<p><b><h3>6. DARKNET:</h3></b><br> 
É uma rede sobreposta que <i>só pode ser acessada através de softwares, configurações, autorizações e frequentemente, não utilizando protocolos e portas comuns</i>. A Darknet foi construída com o propósito de proteger a privacidade do usuário, então tipicamente <b>descreve serviços que utilizam grandes camadas de criptografia para o anonimato</b>.</p>
<p>Geralmente utiliza-se de redes descentralizadas, como P2P, para que as conexões possam ser feitas. Algumas redes podem até podem ser acessadas através de navegadores comuns sob algum tipo de configuração, porém o risco de ser rastreado é muito maior.</p>

<p><b>É ilegal acessar a Darknet?</b><br>
Ela é utilizada para quem busca de alguma forma manter-se anônimo e ter privacidade. Órgãos governamentais, exército, agências de ciberinteligência, jornalistas e ativistas, utilizam diariamente a Darknet. Tanto o Wikileaks quanto jornais como o The Guardian e The New Yorker, tem hospedagens na Darknet com finalidades de capturar vazamentos de dados e documentos governamentais.<br>
Ao contrário do que se pensa, <b>nem tudo na Darknet é pautado para atividades criminais</b>. Exemplos como pirataria e liberdade de expressão, são justos, dependendo do tipo de governo em que o usuário está inserido. Governos como da Rússia, China, Irã e Coréia do Norte, tomam medidas restritivas quanto a liberdade e privacidade que o usuário tem sobre seus dados e conteúdos disponíveis em seus países.<br>
<b>Então se for com o objetivo de cometer atividades criminais, sim</b>.</p>

<p><b>O que é possível encontrar na Darknet?</b><br>
Vale lembrar que, não é porque o conteúdo não é indexado ou precisa de parafernalhas para poder ter acesso, que ele seja interessante para toda a população.<br>
Todo o tipo de conteúdo que é possível achar na Darknet, também é possível de achar na Clearnet e na Deep Web. A única diferença é a <b>QUALIDADE</b> do conteúdo.

<p>Quando está se acessando a Darknet, dependendo do que você planeja fazer, podem haver várias opções de redes para escolher. Cada uma tem os seus usos, vantagens e desvantagens.<br>
Dependendo do que você planeja procurar, alguns mercados na Darknet podem algumas vezes serem desafiadores. Claro que podemos obter listas de links através da Clearnet e de outros serviços próprios da rede, mas se você busca coisas grotescas, terá que pesquisar muito.</p>

<p><b>Exemplos de redes</b>: (34 de 30.000)<br>
- <b>TOR (The Onion Router)</b>: O mais famoso dessa lista. 
</p>

<p>- <b>Garlic Routing</b>: É uma variação do TOR que utiliza o processo de Key-Based Routing

<p>- <b>I2P</b>:

<p>- <b>FreeNet</b>:

<p>- <b>Hyperboria</b>: A distributed meshnet built on cjdns.

<p>- <b>Galet</b>:

<p>- <b>StealthNet</b>:

<p>- <b>GlobalLeaks</b>:

<p>- <b>Perfect Dark</b>:

<p>- <b>Tox</b>:

<p>- <b>Twister</b>:

<p>- <b>MORPHiS</b>:

<p>- <b>Infinit</b>:

<p>- <b>Alienet</b>:

<p>- <b>Maelstrom</b>:

<p>- <b>Resilio</b>:

<p>- <b>Ricochet</b>:

<p>- <b>Soulseek</b>:

<p>- <b>Retroshare</b>: Utilizado para compartilhamento de arquivos, chat, forums, e-mail. 

<p>- <b>DemonSaw</b>:

<p>- <b>OnionShare</b>:

<p>- <b>anoNet</b>: É uma rede descentralizada P2P, semelhante a Freenet, que utiliza-se de VPNs e protocolo BGP. 

<p>- <b>Netsukuku</b>:

<p>- <b>GnuNet</b>: Utilizada para armazenamento e distribuição de arquivos de forma anônima.

<p>- <b>OneSwarm</b>: Serviço P2P

<p>- <b>Omemo</b>: Plataforma social de distribuição de arquivos.

<p>- <b>Phantom</b>: Em desenvolvimento. Utiliza serviços anônimos e faz uso do IPv6 nativamente.

<p>- <b>FreedomBox</b>: Em desenvolvimento. Cria servidores pessoais para comunicações de redes sociais, e-mail e audio/video.

<p>- <b>Telex</b>: Uma nova maneira de passar pela censura da Internet.

<p>- <b>Project Byzantium</b>: Distribuição bootável do Linux to set up wireless mesh nodes with commonly available hardware.

<p>- <b>dn42</b>: Comunidade de roteamento

<p>- <b>CJDNS</b>: Uma rede IPv6 sobreposta que provém encriptação de ponta-a-ponta. Não é anônima por natureza.

<p>- <b>StegoShare</b>: Um software de esteganografia que pode ser utilizado para compartilhamento de arquivos.

<p>- <b>Syndie</b>: Uma rede


Nem sempre é um lugar perigoso, pois por mais que há uma grande quantidade de pirataria, existem pessoas de boa fé. Mas a lei é "Nunca confie em ninguém da Darknet e Dark Web".<br>

<p>Frequentemente as pessoas pensam que acessar a Darknet é preciso de muito conhecimento em tecnologia e de configurações complicadas, porém não é bem assim. Para se usar o TOR, por exemplo, basta baixar e executar, simplesmente.</p>

<p>A única parte "paga" da Darknet, são certos fóruns ou mercados que controlam quem pode ver e acessar os serviços que oferecem.</p>

</p>

<p><b><h3>7. DARK WEB:</h3</b><br>
É o conteúdo que existe na Darknet, sendo composta de atividades criminosas e conteúdos perturbadores. Podemos encontrar Pornografia Infantil (CP - Child Porn), venda de drogas, venda de armas, serviços de black hat e imensos vazamentos de dados. <i>Tudo isso encontramos facilmente na Clearnet</i>, porém a única diferença é o uso de camadas de criptografia e anonimato.</p>

O conteúdo mais predominante na Dark Web são os Mercados Negros, onde vendem vários tipos de itens e serviços diferentes. Sua moeda de troca normalmente é Bitcoin e outras criptomoedas.<br>
<p>O que se pode encontrar nos Mercados Negros:<br>
- Softwares / Malwares / Exploits;<br>
- Serviços de Black Hat;<br>
- Produtos Falsificados;<br>
- Drogas, Remédios Controlados, Ervas, Substâncias Ilegais, Químicas e Tóxicas;<br>
- Armas e Munições;<br>
- Vazamentos de Dados e Doxxing;<br>
- </p>



<p>______________________________________________________________________________________________________________</p>
<p><strong>RESUMO:</strong></p>
<p>Em termos simples, podemos exemplificar usando a <b>"Metáfora do Iceberg"</b>, <i>mesmo não sendo a mais correta</i>. A parte visível, que fica acima do nível do mar, é chamada de <b>"Surface Web"</b> e é tudo o que se pode encontrar através de <b>motores de buscas</b> <i>(Google, Bing, Yahoo, Yandex)</i> fica na "superfície", como:<br>
- Redes sociais;<br>
- Canais de entretenimento;<br> 
- Serviços essenciais;<br>
- E-Commerces populares...<br>
Qualquer pessoa pode navegar livremente, sem precisar de algum tipo de <b>anonimato</b>. Mas não significa que seja um "lado amigável" da Internet, apenas <b>menos complexo</b> de acessar.</p>

<p>Indo para parte submersa do Iceberg... Se na <b>Surface Web</b> podemos encontrar o que quisermos através de sites indexados e ranqueados via motores de busca, na <b>Deep Web</b> é justamente ao contrário:<br>
- Playlists e vídeos não listados do YouTube;<br>
- Bancos de Dados;<br>
- Conteúdos dos seus E-mails;<br> 
- Contas de banco;<br>
- Registros médicos e transações financeiras;<br>
- Repositórios privados, acadêmicos, ciêntíficos e empresariais;<br> 
- Conversas de Whatsapp ou qualquer outro mensageiro...<br>
<b>Este site</b>, por exemplo, <b>está hospedado na Deep Web</b>, onde teoricamente não se poderia obter acesso de forma direta (a não ser se pesquisar pelo meu Instagram).<br>
Embora, os serviços não sejam indexáveis, é possível acessar certos conteúdos que necessitam de credenciais através do seu navegador comum. Contudo, há sempre o risco de ser rastreado, porém <b>é muito mais seguro navegar na Deep Web do que na Dark Web</b>.<br>
Na Deep Web, você acessa seu E-mail, sua conta do banco <i>tranquilamente</i>, mas não quer dizer que essas informações não tenham valor de mercado, tanto para empresas, governo ou criminosos.</p>

<p>A <b>Dark Web</b> contém, em sua maioria, <b>atividades criminais e conteúdos prejudiciais</b>. Navegadores comuns <b>até</b> podem acessar, <i>mas há um enorme risco de comprometer a segurança da máquina e dos seus dados</i>. Então, precisa-se de <b>serviços específicos para facilitar e permitir um certo anonimato no acesso</b>.<br>
O <b>TOR</b> <i>(The Onion Router)</i>, é um serviço que ficou bem famoso por permitir <b>várias camadas de anonimato</b> <i>(onde surgiu erroneamente o termo "Camadas da Deep Web")</i> e domínios próprios de hospedagem, com terminações <b>.onion</b>.</p>

<p>Algumas redes da Dark Web até possuem motores de buscas ou Wikipédias com coleções de links, mas são <i>adicionandos manualmente</i>. Então se tiver algo que você queira muito encontrar, passará um bom tempo pesquisando.<br>   
Mas a Dark Web não vive só de vazamento de dados, mercado negro, pornografia infantil e serviços ilegais. Em certos países onde há uma <b>restrição governamental do uso da Internet e também onde são privados os direitos de liberdade de expressão</b>, os sofredores desses regimes vão para a Dark Web para se <i>expressarem sob o benefício do anonimato</i>.</p>

<p><b>EM RESUMO</b>, cada "camada do Iceberg" <b>precisa uma da outra para poder existir</b>. A Deep Web funciona quase que sobreposta a Surface, enquanto a Dark Web é composta em sua maioria por atividade criminosa e liberdade de expressão sob o benefício (por vezes malefício) do anonimato. Mas isso não significa que o que há na Dark Web não pode ser encontrado na Surface Web.</p>
<p>_________________________________________________________________________________________________________________</p>
<p><b>REFERÊNCIAS</b></p>
<p>- <b>JEP</b>: <a href="https://quod.lib.umich.edu/j/jep/3336451.0007.104?view=text;rgn=main">White Paper: The Deep Web - Surfacing Hidden Value</a><br>
- <b>Radware Blog - Daniel Smith</b>: <a href="https://blog.radware.com/security/2016/04/darknet-101/">Darknet 101: An Introduction to The Darkest Places Online</a><br>
- <b>Life Hacker</b>: <a href="https://lifehacker.com/how-can-i-stay-anonymous-with-tor-1498876762">How Can I Stay Anonymous with Tor?</a><br>
- <b>Computerworld</b>: <a href="https://www.computerworld.com.pt/2015/07/02/servicos-de-vpn-menos-seguros-do-que-se-pensava/">Serviços de VPN menos seguros do que se pensava</a><br>
- <b>Sciendo - Vasile C. Perta et al.</b>: <a href="https://sciendo.com/article/10.1515/popets-2015-0006">A Glance through the VPN Looking Glass: IPv6 Leakage and DNS Hijacking in Commercial VPN clients</a><br>
- <b>Gizmodo - Daniel Kolitz</b>: <a href="https://gizmodo.uol.com.br/internet-desligar-de-repente/">O que aconteceria se a internet inteira desligasse de repente?
</a><br>
- <b>Norton</b>: <a href="https://us.norton.com/internetsecurity-emerging-threats-what-is-the-deep-dark-web-30sectech.html">What is the dark web</a><br>
- <b>Norton</b>: <a href="https://us.norton.com/internetsecurity-how-to-how-can-i-access-the-deep-web.html">How to safely access the deep and dark webs</a><br>
- <b>InternetFreedom</b>: <a href="http://www.internetfreedom.org/FreeGate.html">FreeGate</a><br>
- 

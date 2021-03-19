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

<p> </p>

<p><b><h3>2. VPN (Virtual Private Network):</h3></b><br> 
A Rede Virtual Privada funciona como uma sobreposição de redes, onde a conexão pública (Internet) passa por um "túnel" onde se torna privada, normalmente através de softwares. <b>O real uso da VPN está em acessar uma determinada localidade ou servidor para obter acesso aos seus serviços</b>, como acessar conteúdos bloqueados por região ou home office, por exemplo. Comumente se utiliza de proxys ou criptografia para se manter uma conexão.<br>
A utilização de VPNs é cercada de mitos de segurança. As únicas formas de "anonimato" que uma VPN predispõe são do servidor ver o IP da VPN e dependendo do serviço, propiciar algum tipo de criptografia e políticas de destruição de logs.<br>
<i>(Nos próximos posts abordarei "O Problema das VPNs" de forma mais completa e mitigando vários quesitos de segurança)</i></p>

<p><center>
<img src="/salamandra/vpn-works.jpg" alt="Exemplo comum de VPN, porém não muito correto">
<figcaption><i>Exemplo simples de VPN, porém não exatamente correto</i></figcaption>
</center></p>

<p> </p>

<p><b><h3>3. CLEARNET:</h3></b><br>
É um termo bastante complexo de se definir, mas em termos simples, é utilizado para se referir a <b>tudo aquilo que é publicamente acessível na Internet</b>, ou seja, que não é requerido conexões encriptadas e privadas (não inclui VPNs). Toda a Surface Web, boa parte da Deep Web e parcelas da Darknet e Darkweb, fazem parte da Clearnet.</p>

<p>A Deep Web, que tem seu conteúdo não indexado pelos motores de busca, é acessível públicamente desde que se forneça as credenciais, se necessário.<br>
Já na Darknet, você pode navegar em algumas redes utilizando um navegador comum com uma VPN, por exemplo, porém o risco de ser rastreado é muito maior.</p>

<p>Por exemplo, <b>este site se encontra entre a Clearnet e a Deep Web</b>. Você só pode acessá-lo através do link direto ou digitá-lo na barra de endereços, porém não precisa de nenhuma credencial ou autenticação para poder usar. Meio complicado, não?</p>   

<p>Ferramentas de OSINT (Open-Source Intelligence) e Análise de Vulnerabilidades, como Shodan e Nessus, também estão incluídas, afinal as informações estão disponíveis publicamente e não precisam de autenticação.<br>
E o mesmo vale para redes e serviços que utilizam somente o protocolo IPv6 ao invés de IPv4. Você apenas precisa verificar se no seu provedor está implantado o endereçamento IPv6 e ativá-lo.</p>

<p> </p>

<p><b><h3>4. SURFACE WEB:</h3></b><br>
É a porção da Internet que está disponível para o PÚBLICO GERAL, <b>cujo seu conteúdo só pode ser encontrado através dos motores de buscas</b> (Google, Bing, Yahoo, Yandex, Baidu). Então todo conteúdo que se torna <b>indexado</b> e de alguma forma <b>ranqueado</b>, faz parte da Surface Web. Estima-se que a Surface Web consista em apenas 10% das informações disponíveis na Internet (cerca de 5,24 bilhões de páginas).</p>
<p><b>Exemplos:</b><br>
- Redes Sociais;<br>
- Canais de Entretenimento, como serviços de streaming e blogs;<br>
- E-Commerces populares;<br>
- Serviços Essenciais.<br>
</p>

<p>Aqui não há camadas de criptografia e proxys para termos privacidade. Claro, temos os protocolos de segurança HTTPS/HSTS e certificados digitais que nos ajudam contra ataques de MITM (Man In The Middle) e Sequestro de Sessão (Cookie Hijacking), mas aqui <b>estamos sendo rastreados O TEMPO INTEIRO</b> pelos provedores, servidores e pelo governo.<br>

<p> </p>

<p><b><h3>5. DEEP WEB:</h3></b><br> 
É a parte da Internet onde seu conteúdo <b>não é indexado</b> pelos motores de buscas, mas que pode ser acessado via navegadores comuns e não necessitam de ferramentas especiais. O máximo que pode ser requerido é suas <b>credenciais</b>, ou seja, informações de Login e Senha.<br>
Normalmente, se um site está bem configurado, os motores de buscas estão programados para não permitir que certos conteúdos sejam indexados por padrão.</p>
<p>Exemplificando melhor:<br> 
- Sites e sitemas internos de corporações, associações e comércios;<br>
- Redes e sistemas privados de escolas e universidades;<br>
- Bancos de Dados;<br>
- Sites protegidos por senha ou com acesso de "somente membros";<br>
- Páginas com conteúdos pagos;<br>
- Conteúdos de E-mails e conversas privadas em Redes Sociais;<br>
- Contas de banco e transações financeiras;<br>
- Repositórios privados, corporativos, acadêmicos, governamentais e científicos;<br>
- Documentos governamentais e médicos...<br>
- Servidores FTP;<br>
- Honeypots;<br>
- 
</p>

<p> </p>

<p><b><h3>6. DARKNET:</h3></b><br> 
São redes sobrepostas a Internet que <i>só podem ser acessadas através de softwares, configurações, autorizações e frequentemente, não utilizando protocolos e portas comuns</i>. A Darknet foi construída com o propósito de proteger a privacidade do usuário, então tipicamente <b>descreve serviços que utilizam grandes camadas de criptografia para o anonimato</b>.</p>
<p>Geralmente utiliza-se de redes descentralizadas, como P2P, para que as conexões possam ser feitas. Algumas redes podem até podem ser acessadas através de navegadores comuns sob algum tipo de configuração, porém o risco de ser rastreado é muito maior.<br>
Um ponto desvantajoso é que não se há um controle ou regulação de conteúdos nessas redes.</p>



<p><b>É ilegal acessar a Darknet?</b><br>
Ela é utilizada para quem busca de alguma forma manter-se anônimo e ter privacidade. Órgãos governamentais, exército, agências de ciberinteligência, jornalistas e ativistas, utilizam diariamente a Darknet. Tanto o Wikileaks quanto jornais como o The Guardian e The New Yorker, tem hospedagens na Darknet com finalidades de capturar vazamentos de dados e documentos governamentais.<br>
Ao contrário do que se pensa, <b>nem tudo na Darknet é pautado para atividades criminais</b>. Exemplos como pirataria e liberdade de expressão, são justos, dependendo do tipo de governo em que o usuário está inserido. Governos como da Rússia, China, Irã e Coréia do Norte, tomam medidas restritivas quanto a liberdade e privacidade que o usuário tem sobre seus dados e conteúdos disponíveis em seus países.<br>
<b>Então se for com o objetivo de cometer atividades criminais, sim</b>.</p>

<p><b>O que é possível encontrar na Darknet?</b><br>
Vale lembrar que, não é porque o conteúdo não é indexado ou precisa de parafernalhas para poder ter acesso, que ele seja interessante para toda a população.<br>
Todo o tipo de conteúdo que é possível achar na Darknet, também é possível de achar na Clearnet. A única diferença é a <b>QUALIDADE e QUANTIDADE</b> do conteúdo.</p>

<p><b>Primeiramente vamos utilizar exemplos amigáveis e para toda família:</b><br>
- Comunicação via criptografia para garantir privacidade e proteção;<br>
- Redes sociais, blogs, jornais, chats de texto e voz;<br>
- Grupos que lutam por suas causas;<br>
- Clube de livros e diversos outros fanclubes;<br>
- Versões Darknet do Yahoo! Respostas;<br>
- Sistemas bibliotecários;<br>
- Vários tipos de mercados digitais;<br>
- Teorias da conspiração;<br>
- Cursos e MUITO material sobre tecnologia...</p>

<p><b>Agora veremos como é na maioria dos casos:</b><br>
- "Index of / "<br> 
- "This site is hosted" <br>
- "This site has been seized" <br>
- Sites, serviços e redes clonados;<br>
- Servidores mal-configurados;<br>
- Fóruns abandonados;<br>
- VÁRIAS Creepypastas e hoaxes;<br>
- VÁRIOS mercados aleatórios de pessoas anônimas, mas que 99% são golpe;<br>
- MUITA pirataria;
- Documentos vazados;<br>
- Todo tipo de pornografia que você pode imaginar (mas é melhor não imaginar);<br>
- Sites e/ou rede de chats estranhos com mensagens cifradas;<br>
- Pessoas oferecendo serviços estranhos;<br>
- Drogas, drogas, drogas e mais drogas;<br>
- <b>E todo o resto do conteúdo que você encontra na Dark Web.</b></p>

<p>Quando está se acessando a Darknet, dependendo do que você planeja fazer, podem haver várias opções de redes para escolher. Cada uma tem os seus usos, vantagens e desvantagens.<br>
Dependendo do que você planeja procurar, alguns mercados na Darknet podem algumas vezes serem desafiadores. Claro que podemos obter listas de links através da Clearnet e de outros serviços próprios da rede, mas se você busca coisas grotescas, terá que pesquisar muito.</p>

<p><b>Exemplos de redes da Darknet</b>: (34 de aprox. 30.000)<br>
- <b>TOR (The Onion Router)</b>: O mais famoso dessa lista. É um software que utiliza 
Os problemas conhecidos do TOR são os ataques de correlação, os nós de saída podem ser interceptados por não utilizarem criptografia de ponta-a-ponta, falhas de configurações de sites que permitem exposição de metadados e endereçamento real do usuário/servidor, e várias outras brechas mais complexas.</p> 
</p>

<p>- <b>Garlic Routing</b>: É uma variação do TOR que utiliza o processo de Key-Based Routing

<p>- <b>CJDNS</b>: Uma rede IPv6 sobreposta que provém encriptação de ponta-a-ponta, porém seu uso não é intencionado para o anonimato. Segundo a documentação, foi fundada na ideologia de que as redes deveriam ser fáceis de montar, protocolos deveriam ser mais escalonáveis e que a segurança deveria existir em todo lugar.<br>
Seu funcionamento é no próprio navegador através de instalação de pacotes na máquina e configurações de rede. Para entrar em alguma rede existente, você precisa se conectar com alguém que já esteja lá.</p> 

<p>- <b>I2P</b>:

<p>- <b>FreeNet</b>:

<p>- <b>Hyperboria (Project Meshnet)</b>: É uma rede distribuída, ainda em desenvolvimento, que utiliza CJDNS para conexão. Existem cerca de 2100 nós de conexão no Hyperboria.<br>
Segundo a documentação do projeto, eles buscam viabilizar uma alternativa para a Clearnet.<br>
Seu endereço utiliza o espaço "fc00::/8"</p>
</p>

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

<p>- <b>Freifunk</b>: É uma rede comunitária wireless alemã, que conta com 400 comunidades locais e mais de 41.000 pontos de acesso.<br>
Os usos da Freifunk são com base no princípio de Neutralidade de Redes, de garantir acesso ao conhecimento e informação livremente e também com o uso de tecnologias Open-Source.<br>   

<p>- <b>ChaosVPN</b>: Utiliza redes Tinc como base. Basicamente é uma rede para que Gray/Black Hats e ativistas via intranet, separando-os da Internet. 

<p>- <b>DN42 (Decentralized Network 42)</b>: É uma rede que utiliza VPNs dinâmicas baseado em tecnologias como BGP e DNS. Os usuários da rede podem se conectar através de tuneis de IPsec, OpenVPN, GRE e Tinc, e também se interconectarem com outras redes, como ChaosVPN e Freifunk. 

<p>- <b>Dat (Hypercore Protocol)</b>: É uma rede distribuída e de compartilhamento P2P Open-Source. É focada em interesses públicos, como ciência, tecnologia, blockchain e outras criptomoedas.</p>

<p>- <b>StegoShare</b>: Um software de esteganografia que pode ser utilizado para compartilhamento de arquivos.

<p>- <b>Syndie</b>: Uma rede

<p> </p>

<!-- <p><b><h3>COMO NAVEGAR DE FORMA SEGURA <i>(ou com menos riscos)</i> NA DARKNET?<b></h3><br>
<b>1. Planejamento:</b> É importante que você saiba o que irá procurar e fazer, pois você pode passar horas navegando e acabar vendo o que não quer;</p>
<p><b>2. Estude sobre Segurança da Informação (ou pelo menos saiba o básico):</b> Procure entender mais sobre Redes 

<p><b>3. Identidades e Credenciais:</b> Em hipótese alguma utilize seu nome real, nome de amigos e parentes, E-mails ou qualquer outra coisa que possa te identificar, mesmo que indiretamente. Existem serviços específicos, como o Guerrilla Mail ou ProtonMail, que oferecem E-mails descartáveis ou específicos para serem usados nessas redes.<br>
Também <b>não procure as mesmas coisas que você procura na Surface na Darknet</b>, pois isso pode traçar um perfil de usuário e sua identidade ser descoberta.</p> -->



<p> </p>

<p><b><h3>7. DARK WEB:</h3></b><br>
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



<p>__________</p>
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
<p><a href="https://quod.lib.umich.edu/j/jep/3336451.0007.104?view=text;rgn=main">White Paper: The Deep Web - Surfacing Hidden Value</a><br>
- <a href="https://blog.radware.com/security/2016/04/darknet-101/">Darknet 101: An Introduction to The Darkest Places Online</a><br>
- <a href="https://lifehacker.com/how-can-i-stay-anonymous-with-tor-1498876762">How Can I Stay Anonymous with Tor?</a><br>
- <a href="https://us.norton.com/internetsecurity-emerging-threats-what-is-the-deep-dark-web-30sectech.html">What is the dark web</a><br>
- <a href="https://us.norton.com/internetsecurity-how-to-how-can-i-access-the-deep-web.html">How to safely access the deep and dark webs</a><br>
- <a href="http://www.internetfreedom.org/FreeGate.html">Documentação do FreeGate</a><br>
- <a href="https://www.ispblog.com.br/2018/05/02/9-passos-para-habilitar-o-ipv6-em-uma-rede-isp/">9 Passos para Habilitar o IPV6 em uma Rede ISP</a><br>
- <a href="https://digital.com/online-privacy/deep-dark-web/">Enter The Deep & Dark Web If You Dare (And Get Ready For A Surprise)<a><br>
- <b>RETSKIN, Sion</b>. Hands-On: Dark Web Analysis. Packt, 2018.<br>
- <b>KOZAKIEWICZ, Dilmar José</b>. DEEP WEB E SEGURANÇA DA INFORMAÇÃO: UMA ANÁLISE E SEUS IMPACTOS NA SOCIEDADE E NAS ORGANIZAÇÕES. UTFPR, Curitiba, 2018.<br>
- <a href="https://docs.meshwith.me/">Documentação do Hyperboria</a><br>
- <a href="https://github.com/cjdelisle/cjdns/blob/master/doc/Whitepaper.md">Documentação do CJDNS</a><br>
- <a href="https://dat.foundation/about/foundation/">What is Dat?</a><br>
- <a href="https://wiki.freifunk.net/">Freifunk Wiki</a><br>
- 

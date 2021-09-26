---
layout: post
title:  VPNs e o Pseudoanonimato
date:   2021-09-28 08:32:20 +0300
description: A Política de Privacidade de um serviço o torna seguro? # Add post description (optional)
img: .jpg # Add image post (optional)
tags: [Segurança]
author:
---
<p>O <b>propósito original</b> das <b>VPNs</b> <i>(Redes Privadas Virtuais)</i> era com o objetivo de <b>obter acesso a servidores remotos</b>, especialmente para se ter acesso a <b>conteúdos bloqueados por região e home office</b>. Infelizmente, com o passar do tempo e com o aumento massivo de ataques cibernéticos, <b>as VPNs tornaram-se errôneamente um sinônimo de anomimato e privacidade</b>, dando a falsa sensação de que o tráfego redirecionado deixa o usuário protegido de alguma forma. Porém, sabemos que <b>isso nunca foi verdade</b> e hoje quero mostrar o porquê...<p> 

<p> </p>

<p><b><h3>1. Como as VPNs Funcionam?</h3></b><br>
De modo simples e resumido, as VPNs atuam como <b>servidores intermediários</b> entre você e a Internet, e por padrão, todas as VPNs utilizam algum tipo de protocolo de tunelamento e algoritmos de encriptação. Os protocolos de tunelamento servem para ligar o seu dispositivo a VPN, de modo que sua conexão torna-se privada e seu endereço de IP não seja visível fora da conexão. A aplicação dos algoritmos de criptografia irá depender de cada serviço, pois quanto maior a chave, maior é a influencia na velocidade e segurança da conexão.</p>

<p> </p>

<><b><h3>2. Tipos de VPNs:</h3></b><br>

<p>- <b>Acesso Remoto:</b>: É o tipo mais comum, que envolve apenas conectar o dispositivo a um servidor remoto.</p>

<p>- <b>Acesso Intranet Site-To-Site:</b> Normalmente utilizada para trabalho, onde a VPN cria uma conexão com vários dispositivos juntos e permite que o empregado possa trabalhar de diversas localidades do mundo. Uma VPN Intranet cria essa conexão mas permite que vários dispositivos conectem-se diretamente sem encriptação.</p>

<p>- <b>Acesso Extranet Site-To-Site:</b> Utilizada normalmente em projetos colaborativos, onde a VPN cria uma conexão entre duas Intranets separadas e permite que os usuários se comuniquem diretamente.</p>

<p> </p>

<p><b><h3>3. Diferença entre Proxy e VPN:</h3></b><br>
Um Proxy

<p>Já a VPN

<p> </p>

<p><b><h3>3. Protocolos Utilizados em VPNs:</h3></b><br>
<p>- <b>TLS (Transport Layer Security)</b>: Protocolo com solução barata, de fácil implementação, com muitas vulnerabilidades e pouco conhecimento sobre mitigação. Projetado a nível de aplicação web <i>(fornece redirecionamento para aplicativos específicos e não para a rede inteira)</i>, provém um sistema de autenticação entre servidores/usuários e distribui direitos de acesso sem a necessidade de instalação de software. Além de suas vulnerabilidades, pode também haver problemas com compartilhamento de arquivos, backup e acesso a recursos de impressão.</p> 

<p>- <b>PPTP (Point-to-Point Tunneling Protocol):</b> É um protocolo que foi desenvolvido pela Microsoft e integrado ao Windows 95 nas conexões discadas, sendo o mais antigo utilizado nas VPNs atuais. Utiliza-se do MPPE (Microsoft Point-to-Point Encryption) com chaves de até 128-bit para fornecer a segurança dos dados, porém ele se tornou obsoleto devido as suas vulnerabilidades bem conhecidas. Mas, por apresentar uma conexão extremamente rápida, de alta compatibilidade, fácil configuração (requisitando apenas nome de usuário, senha e endereço do servidor), ele é ainda utilizado em larga escala por várias aplicações. Acredito que o único uso atual do PPTP seja para acessar conteúdos bloqueados por região, já que o nível de segurança não importa.</p>

<p>- <b>IPSec (Internet Protocol Security):</b> Faz o redirecionamento entre 

<p>- <b>L2TP (Layer 2 Tunnel Protocol) + IPSec:</b> O L2TP foi apresentando como um substituto para o PPTP, com a diferença da requisição ser através de UDP e um encapsulamento duplo do tráfego. Porém, como ele não trabalha sozinho, ele deve ser usado conjuntamente com o IPSec para a conexão se tornar mais segura.</p> 

<p>- <b>SSTP:</b> O funcionamento do SSTP se assemelha como um tráfego HTTPS, . Por não ser open-source, talvez ele seja passível de backdoors ou qualquer outro método para a espionagem de tráfego. 

<p>- <b>OpenVPN:</b> . Por utilizar várias camadas de encriptação, a sua conexão não é tão rápida como os outros protocolos.

<p>- <b>IKEv2 + IPSec:</b>

<p>- <b>WireGuard:</b> . Mesmo sendo open-source, sua pouca idade não é o suficiente para demonstrar seus limites e riscos.

<p> </p>

<p><b><h3>4. Por que utilizar uma VPN?</h3></b><br>

<p>- <b>Privacidade:</b> Provavelmente esse é o principal motivo das pessoas estarem utilizando tantos serviços de VPNs atualmente. 

<p>- <b>Proteção de Identidade:</b> 

<p>- <b>Acessar Conteúdos Bloqueados por Região:</b>

<p>- 

<p><b><h3>5. O Grande Problema das VPNs:</h3></b></p>

<p>- <b>Políticas de Privacidade:</b> As Políticas de Privacidade são obrigatórias para qualquer tipo de serviço que tenha retenção de dados na Internet. Fazer uma propaganda bonita de que 

<p> </p>

<p><b><h3>6. Darknet e Redes Anonimizadas:</h3></b><br>

<p> </p>

<p><b><h3>7. The Onion Route (Tor):</h3></b><br>

<p> </p>

<p><b><h3>8. Técnicas e Ataques a Redes Anônimas e VPNs:</h3></b><br>

<p><b><h4>Ataques de Negação de Serviço (DoS):</h4></b></p>

<p>- <b>Cellfood Attack:</b>

<p>- <b>Botnet Flooding Attack:</b>

<p>- <b>Sniper Attack:</b>

<p> </p>

<p><b><h4>Ataques de Apoio:</h4></b></p>

<p>- <b>Packet Size Analysis Attack:</b>

<p>- <b>Tor Authentication Protocol Attack:</b>

<p>- <b>Influencing Tor's Guard Selection:</b>

<p>- <b>Sybil Attack:</b>

<p>- <b>Guard Selection Attack:</b>

<p> </p>

<p><b><h4>Ataque de Fingerprinting:</h4></b><p>

<p>- <b>Circuit Fingerprinting:</b>

<p> </p>

<p><b><h4>Ataques de Desanonimização:</h4></b><p>

<p>- <b>Bandwidth Estimation Attack:</b>

<p>- <b>Indirect Rate Reduction Attack:</b>

<p>- <b>Congestion Attack:</b>

<p>- <b>Fingerprinting Attack:</b>

<p>- <b>Relay Early Attack:</b>

<p>- <b>Raptor Attack:</b>

<p> </p>

<p><b><h4>Ataques de Correlação:</h4></b><p>

<p>- <b>Replay Attack:</b>

<p>- <b>Cell Counter Based Attack:</b>

<p>- <b>Correlation-Based Traffic Analysis Attack:</b>

<p>- <b>Low Resource Routing Attack:</b>

<p>- <b>HTTP Patern Injection Attack:</b>

<p>- <b>Packet Timing Watermarking Attack:</b>

<p>- <b>Bad Apple Attack:</b>

<p>- <b>Probabilistic Attack Attack:</b>

<p>- <b>Torben Attack:</b>

<p> </p>

<p><b><h4>Ataques de Revelação de Serviço:</h4></b></p>

<p>- <b>Clock Skew Attack:</b>

<p>- <b>First Node Attack:</b> 


- Monitoramento Passivo: Quando um cibercriminoso simplesmente recolhe informações do tráfego do utilizador, com ou sem encriptação;
- Sequestro de DNS: Quado o cibercriminoso redireciona o tráfego do usuário para um servidor comprometido;
- Ataque de Correlação de Tráfego / Ataque de Confirmação E2E: 
- Devido a uma vulnerabilidade conhecida como "IPv6 Leakage", até as melhores VPNs disponíveis no mercado podem expor o usuário. Normalmente as VPNs só protegem o tráfego de IPv4.



<p>_________________________________________________________________________________________________________________</p>
<p><b>REFERÊNCIAS</b></p>
<p>- <a href="https://www.netmotionsoftware.com/blog/connectivity/vpn-protocols">VPN Protocols</a><br>
- <a href="https://www.security.org/vpn/encryption/">Is a VPN Encrypted?</a><br>
- <a href="https://www.computerworld.com.pt/2015/07/02/servicos-de-vpn-menos-seguros-do-que-se-pensava/">Serviços de VPN menos seguros do que se pensava</a><br>
- <a href="https://www.techradar.com/vpn/vpn-tunnels-explained-how-to-keep-your-internet-data-secure">VPN Tunnels explained: what are they and how can they keep your internet data secure</a><br>
- <a href="https://pt.linkedin.com/pulse/maldito-ransomware-vpn-e-lgpd-nilson-vianna-m-sc-">Nilson Viana - Maldito Ransomware... VPN e LGPD</a><br>
- <a href="https://sciendo.com/article/10.1515/popets-2015-0006">A Glance through the VPN Looking Glass: IPv6 Leakage and DNS Hijacking in Commercial VPN clients</a><br>
- <a href="https://gizmodo.uol.com.br/internet-desligar-de-repente/">O que aconteceria se a internet inteira desligasse de repente?</a><br>
- <a href="https://www.wired.com/story/china-russia-vpn-crackdown/">The Attack on Global Privacy Leaves Few Places To Turn</a><br>
- <a href="https://github.com/Attacks-on-Tor/Attacks-on-Tor">Attacks On Tor</a><br>
- 
 

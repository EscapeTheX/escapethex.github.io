---
layout: post
title:  O Problema das VPNs e o Pseudoanonimato
date:   2021-09-28 08:32:20 +0300
description: Será que basta apenas confiarmos na Política de Privacidade de um serviço? # Add post description (optional)
img: .jpg # Add image post (optional)
tags: [Segurança]
author:
---
<p><center><strong>Repita 6x no espelho: VPNs não foram projetadas para garantir privacidade e anonimato!</strong></center></p> 

<p>O <b>propósito original</b> das <b>VPNs</b> <i>(Redes Privadas Virtuais - Virtual Private Networks)</i> era com o objetivo de <b>obter acesso a servidores remotos</b>, especialmente para se ter acesso a <b>conteúdos bloqueados por região e home office</b>. Infelizmente, com o passar do tempo e com o aumento massivo de ataques cibernéticos, <b>as VPNs tornaram-se errôneamente um sinônimo de anomimato e privacidade</b>, dando a falsa sensação de que o tráfego redirecionado deixa o usuário protegido de alguma forma. Porém, sabemos que <b>isso nunca foi verdade</b> e hoje quero mostrar o porquê...<p> 

<p> </p>

<p><b><h3>Como as VPNs Funcionam?</h3></b><br>
De modo simples e resumido, as VPNs atuam como <b>servidores intermediários</b> entre você e a Internet. 


criando uma conexão ponto-a-ponto para redirecionar todo o tráfego do seu dispositivo e aplicar protocolos de tunelamento, assim garantindo um certo <i>"nível de segurança"</i> nas conexões. 
Os protocolos de tunelamento servem para ligar o seu dispositivo a VPN, de modo que sua conexão torna-se privada e seu endereço de IP não seja visível fora da conexão. A aplicação dos algoritmos de criptografia é opcional e vai depender de cada serviço, já que isso influencia diretamente na velocidade, segurança e privacidade.


<p> </p>
<p><b><h3>Diferença entre Proxy e VPN:</h3></b><br>
Um Proxy

<p>Já a VPN

<p> </p>

<p><b><h3>Tipos de Protocolos Utilizados em VPNs:</h3></b><br>
<p>- <b>TLS (Transport Layer Security)</b>: Provém um sistema de autenticação entre servidores e usuários,

<p>- <b>PPTP (Point-to-Point Tunneling Protocol)</b>: É um protocolo que foi desenvolvido pela Microsoft e integrado ao Windows 95 nas conexões discadas, sendo o mais antigo utilizado nas VPNs atuais. Utiliza-se do MPPE (Microsoft Point-to-Point Encryption) para fornecer a segurança dos dados, que atualmente é um protocolo inseguro. Mas que, por apresentar uma conexão extremamente rápida, de alta compatibilidade, fácil configuração (requisitando apenas nome de usuário, senha e endereço do servidor), ele é ainda utilizado em larga escala por várias aplicações.</p>

<p>- <b>IPSec</b>: 

<p>- <b>L2TP (Layer 2 Tunnel Protocol) + IPSec</b>: O L2TP foi apresentando como um substituto para o PPTP, com a diferença da requisição ser através de UDP e um encapsulamento duplo do tráfego. Porém, como ele não trabalha sozinho, ele deve ser usado conjuntamente com o IPSec para a conexão se tornar mais segura.</p> 

<p>- <b>SSTP</b>: O funcionamento do SSTP se assemelha como um tráfego HTTPS, . Por não ser open-source, talvez ele seja passível de backdoors ou qualquer outro método para a espionagem de tráfego. 

<p>- <b>OpenVPN</b>: . Por utilizar várias camadas de encriptação, a sua conexão não é tão rápida como os outros protocolos.

<p>- <b>IKEv2 + IPSec</b>:

<p>- <b>WireGuard</b>: . Mesmo sendo open-source, sua pouca idade não é o suficiente para demonstrar seus limites e riscos.



Devido a uma vulnerabilidade conhecida como "IPv6 Leakage", até as melhores VPNs disponíveis no mercado podem expor o usuário. Normalmente as VPNs só protegem o tráfego de IPv4.




<p><b><h3>Darknet e Redes Anonimizadas:</h3></b><br>

<p><b><h3>The Onion Route (Tor):</h3></b><br>







<p><b><h3>Técnicas e Ataques a Redes Anônimas e VPNs:</h3></b></p>

<p><b>Ataques de Negação de Serviço (DoS):</b></p>
- Cellfood Attack:
- Botnet Flooding Attack:
- Sniper Attack
  
<p><b>Ataques de Apoio:</b></p>
- Packet Size Analysis Attack:
- Tor Authentication Protocol Attack:
- Influencing Tor's Guard Selection:
- Sybil Attack:
- Guard Selection Attack:

<p><b>Ataque de Fingerprinting:</b><p>
- Circuit Fingerprinting:
- 
  
<p><b>Ataques de Desanonimização:</b><p>
- Bandwidth Estimation Attack:
- Indirect Rate Reduction Attack:
- Congestion Attack:
- Fingerprinting Attack:
- Relay Early Attack:
- Raptor Attack:
  
<p><b>Ataques de Correlação:</b><p>
- Replay Attack:
- Cell Counter Based Attack:
- Correlation-Based Traffic Analysis Attack:
- Low Resource Routing Attack:
- HTTP Patern Injection Attack:
- Packet Timing Watermarking Attack:
- Bad Apple Attack:
- Probabilistic Attack Attack:
- Torben Attack


<p><b>Ataques de Revelação de Serviço:</b></p>
<p>- <b>Clock Skew Attack:</b>

<p>- First Node Attack:</b> 


- Monitoramento Passivo: Quando um cibercriminoso simplesmente recolhe informações do tráfego do utilizador, com ou sem encriptação;
- Sequestro de DNS: Quado o cibercriminoso redireciona o tráfego do usuário para um servidor comprometido;
- Ataque de Correlação de Tráfego / Ataque de Confirmação E2E: 


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
 

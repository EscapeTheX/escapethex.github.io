---
layout: post
title:  O Problema das VPNs e o Pseudoanonimato
date:   2021-03-25 08:32:20 +0300
description: Será que basta apenas confiarmos na Política de Privacidade de um serviço? # Add post description (optional)
img: .jpg # Add image post (optional)
tags: [Segurança]
author:
---
<center><strong>Repita 6x no espelho: VPNs não foram projetadas para garantir privacidade e anonimato!</strong></center> 

<p>O <b>propósito original</b> das <b>VPNs</b> <i>(Redes Privadas Virtuais - Virtual Private Networks)</i>, era com o objetivo de <b>obter acesso a servidores remotos</b>, especialmente para se ter acesso a <b>conteúdos bloqueados por região e home office</b>. Infelizmente, com o passar do tempo e com o aumento massivo de ataques cibernéticos, <b>as VPNs tornaram-se errôneamente um sinônimo de anomimato e privacidade</b>, dando a falsa sensação de que o tráfego redirecionado deixa o usuário protegido de alguma forma. Porém, sabemos que <b>isso nunca foi verdade</b> e hoje quero mostrar o porquê...<p> 

<p><b><h3>Como uma VPN Funciona?</h3></b><br>




Devido a uma vulnerabilidade conhecida como "IPv6 Leakage", até as melhores VPNs disponíveis no mercado podem expor o usuário. Normalmente as VPNs só protegem o tráfego de IPv4.






<p><b><h3>The Onion Route (Tor):</h3></b><br>







<p><b><h3>Técnicas e Ataques a Redes Anônimas e VPNs:</h3></b></p>

<p>Ataques de Negação de Serviço (DoS):<br>
- Cellfood Attack:
- Botnet Flooding Attack:
- Sniper Attack
  
<p>Ataques de Apoio:<br>
- Packet Size Analysis Attack:
- Tor Authentication Protocol Attack:
- Influencing Tor's Guard Selection:
- Sybil Attack:
- Guard Selection Attack:

<p>Ataque de Fingerprinting:<p>
- Circuit Fingerprinting:
- 
  
<p>Ataques de Desanonimização:<p>
- Bandwidth Estimation Attack:
- Indirect Rate Reduction Attack:
- Congestion Attack:
- Fingerprinting Attack:
- Relay Early Attack:
- Raptor Attack:
  
<p>Ataques de Correlação:<p>
- Replay Attack:
- Cell Counter Based Attack:
- Correlation-Based Traffic Analysis Attack:
- Low Resource Routing Attack:
- HTTP Patern Injection Attack:
- Packet Timing Watermarking Attack:
- Bad Apple Attack:
- Probabilistic Attack Attack:
- Torben Attack

<p>Ataques de Revelação de Serviço:
- Clock Skew Attack:
- First Node Attack: 


- Monitoramento Passivo: Quando um cibercriminoso simplesmente recolhe informações do tráfego do utilizador, com ou sem encriptação;
- Sequestro de DNS: Quado o cibercriminoso redireciona o tráfego do usuário para um servidor comprometido;
- Ataque de Correlação de Tráfego / Ataque de Confirmação E2E: 

Muitos fornecedores de VPNs ainda dependem de protocolos de tunelamento desatualizados como PPTP, que são facilmente quebrados através de BruteForce.
VPNs não foram projetadas para garantir privacidade e anonimato.





<p>_________________________________________________________________________________________________________________</p>
<p><b>REFERÊNCIAS</b></p>
<p>- <a href="https://www.computerworld.com.pt/2015/07/02/servicos-de-vpn-menos-seguros-do-que-se-pensava/">Serviços de VPN menos seguros do que se pensava</a><br>
- <a href="https://www.techradar.com/vpn/vpn-tunnels-explained-how-to-keep-your-internet-data-secure">VPN Tunnels explained: what are they and how can they keep your internet data secure</a><br>
- <a href="https://pt.linkedin.com/pulse/maldito-ransomware-vpn-e-lgpd-nilson-vianna-m-sc-">Nilson Viana - Maldito Ransomware... VPN e LGPD</a><br>
- <a href="https://sciendo.com/article/10.1515/popets-2015-0006">A Glance through the VPN Looking Glass: IPv6 Leakage and DNS Hijacking in Commercial VPN clients</a><br>
- <a href="https://gizmodo.uol.com.br/internet-desligar-de-repente/">O que aconteceria se a internet inteira desligasse de repente?</a><br>
- <a href="https://www.wired.com/story/china-russia-vpn-crackdown/">The Attack on Global Privacy Leaves Few Places To Turn</a><br>
- <a href="https://github.com/Attacks-on-Tor/Attacks-on-Tor">Attacks On Tor</a><br>
- 
 

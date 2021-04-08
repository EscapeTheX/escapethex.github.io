---
layout: post
title:  Como Rastrear Criminosos na Darknet?
date:   2021-03-20 08:32:20 +0300
description: Você já ouviu falar que não existe 100% de segurança na Internet? # Add post description (optional)
img: .jpg # Add image post (optional)
tags: [Segurança]
author:
---
<center><strong>Você já ouviu falar que não existe 100% de segurança na Internet?</strong></center> 

<p>Se você ainda não leu meu post sobre <a href="https://escapethex.netlify.app/deep-e-dark-web/">Clearnet, Deep Web e Dark Web</a>, sugiro que leia para poder entender melhor o assunto de hoje.</p>

<p>A Darknet atualmente possui cerca de 30.000 serviços únicos para anonimato, o que representa apenas 3,4% do tráfego total da Internet. Porém, como sabemos essas redes são usadas para quem quer privacidade ou quebrar barreiras de censura em seus países.<br>

A Darknet pode não ser tão "dark" como parece. Há muita relação entre os links postados na Darknet e na Surface Web. Mais de 20% dos 1,5 milhões de páginas hospedadas na Darknet tem suas imagens, documentos e arquivos Javascript importados de sites da Surface Web.
Isso aumenta o potencial risco dos donos desses recursos serem rastreados através de motores de buscas. Por exemplo, o Google pode monitorar 13% dos domínios presentes na Darknet por meio dessa "vulnerabilidade".

Muitos sites contém scripts de rastreamento que monitoram o comportamento dos usuários em aproximadamente 27% das páginas que visitam. 1/3 deles são de origem da Surface Web e 43% são do Google.
Se um serviço da Darknet utiliza o mesmo script de um site na Surface, qualquer um pode monitorar as atividades dos usuários e potencialmente identificá-los quando visitarem sites menos privados.
Os serviços de proxy do TOR, como o Tor2Web, apresenta o maior risco. Pois os serviços podem ver os IPs dos usuários e os links acessados entre a Darknet e a Surface, também podem ser monitorados por terceiros. Quando o usuário utiliza desse serviço, o navegador pode acessar normalmente, se desviando do processo de anonimato.
Nas configurações, pode-se desligar o uso de scripts, porém os sites podem apresentar mal-funcionamento.

Estima-se que 35% dos serviços da Darknet possam ser desanonimizados.

Por serem descentralizadas, estão mais propensas a sofrerem ataques coordenados, como de DDoS (Distributed Denial of Service), causando um efeito em cascata catastrófico em cada nó, assim uma rede inteira pode vir a falhar.
Porém são menos vulneráveis a sofrerem ataques diretos, pois os serviços que utilizam garlic e onion route, tem seus ataques parados por conta das camadas de criptografia.

Algumas vezes donos dos sites hospedados na Darknet deixam escapar o verdadeiro IP do servidor ou metadados em arquivos subidos no site.

OnionScan é um software que escaneia automaticamente serviços anônimos do TOR, procurando vulnerabilidades e problemas. Porém qualquer pessoa pode obter o benefício de verificar se o site é seguro ou não, incluindo Doxxers e Chefes de Mercados Negros.
Os problemas podem causar o desmascaramento do servidor ou a identidade dos seus proprietários.
Pode-ser constatar que uma mesma pessoa possua o mesmo servidor para hospedar um site na Clearnet quanto na Darknet, metadados em imagens que revelam coordenadas de GPS, imagens de status do Apache expostas, imagens not stripped of exif data, imagens revelando as ferramentas utilizadas para montar o site.
Funciona igual a um analizador de vulnerabilidades web da clearnet, porém para serviços anônimos.
Porém como qualquer outro rastreador, as requests ficam gravadas nos logs.

De acordo com o site da Tails: "Os padrões de tempo e volume de diferentes comunicações através das redes, podem ser estatísticamente possível identificar circuitos e correlacionar usuários e servidores".


Os problemas conhecidos do TOR são os ataques de correlação, os nós de saída podem ser interceptados por não utilizarem criptografia de ponta-a-ponta, falhas de configurações de sites que permitem exposição de metadados e endereçamento real do usuário/servidor, e várias outras brechas mais complexas.</p> 
Onion Share, Whonix, Tails




<p>_________________________________________________________________________________________________________________</p>
<p><b>REFERÊNCIAS</b></p>
<p>- <a href="https://quod.lib.umich.edu/j/jep/3336451.0007.104?view=text;rgn=main">White Paper: The Deep Web - Surfacing Hidden Value</a><br>
- <a href="https://blog.radware.com/security/2016/04/darknet-101/">Darknet 101: An Introduction to The Darkest Places Online</a><br>
- <a href="https://lifehacker.com/how-can-i-stay-anonymous-with-tor-1498876762">How Can I Stay Anonymous with Tor?</a><br>
- <a href="https://www.computerworld.com.pt/2015/07/02/servicos-de-vpn-menos-seguros-do-que-se-pensava/">Serviços de VPN menos seguros do que se pensava</a><br>
- <a href="https://sciendo.com/article/10.1515/popets-2015-0006">A Glance through the VPN Looking Glass: IPv6 Leakage and DNS Hijacking in Commercial VPN clients</a><br>
- <a href="https://us.norton.com/internetsecurity-emerging-threats-what-is-the-deep-dark-web-30sectech.html">What is the dark web</a><br>
- <a href="https://us.norton.com/internetsecurity-how-to-how-can-i-access-the-deep-web.html">How to safely access the deep and dark webs</a><br>
- <a href="https://www.newscientist.com/article/2126472-trackers-could-unmask-dark-web-users-who-think-theyre-anonymous/">Trackers could unmask dark web users who think they’re anonymous</a><br>
- <a href="https://www.newscientist.com/article/2123354-why-the-dark-net-is-more-resilient-to-attack-than-the-internet/">Why the dark net is more resilient to attack than the internet</a><br>
- <a href="https://github.com/s-rah/onionscan">What is OnionScan?</a><br>
- <a href="https://tails.boum.org/about/index.en.html">How Tails Works</a><br>
- <a href="https://docs.onionshare.org/2.3.1/en/">OnionShare's Documentation</a><br>
- <a href="https://metrics.torproject.org/hidserv-dir-onions-seen.html">Tor Metrics</a><br>
- <a href="https://www.whonix.org/wiki/FAQ">FAQ Whonix</a><br>
- <a href="https://www.ispblog.com.br/2018/05/02/9-passos-para-habilitar-o-ipv6-em-uma-rede-isp/">9 Passos para Habilitar o IPV6 em uma Rede ISP</a><br>
 

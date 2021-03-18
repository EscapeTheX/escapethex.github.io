---
layout: post
title:  Basicão Sobre Redes, Internet e Segurança
date:   2021-03-18 08:32:20 +0300
description: Entenda Redes, Internet e Segurança com exemplos toscos, porém funcionais # Add post description (optional)
img: redesfordummies.jpg # Add image post (optional)
tags: [Segurança]
author:
---
<p><b>0. Explicação básica sobre o funcionamento de Redes e da Internet:</b></p>

<p> Podemos definir a Internet como um sistema de entregas, como os correios. Temos vários <b>pacotes</b> <i>(dados)</i> a serem entregues entre <b>centrais</b> <i>(servidores)</i>, <b>distribuidoras</b> <i>(terminais e portas)</i> e <b>clientes</b> <i>(máquinas)</i>. Cada pacote tem sua <b>nota fiscal</b> <i>(header ou cabeçalho)</i>, identificando seu conteúdo, quantidade, incluindo data e hora do envio e da entrega.<br>
Às vezes, tem pessoas que tentam <b>burlar ou forjar a nota fiscal do pacote</b>, seja para meios lícitos ou ilícitos. Como quando há extravio ou roubo de encomendas, quando colocam tijolos ao invés de um XBOX na caixa ou <i>empresas que fazem seus negócios de cunho privado</i>. Porém, <b>há sempre algum tipo de registro</b>, mesmo que residual do pacote, <b>que pode identificar o conteúdo, remetente e o destinatário</b>.</p>

<p>- <b>Clientes</b>:  

<p>Cada máquina possui <b>dois</b> identificadores únicos:<br>
- <b>IP - Internet Protocol:</b> É uma identificação que a rede atribui a cada máquina conectada a ela, para que haja alguma comunicação. Teoricamente, nunca poderá existir um endereço igual, porém pode ser alterável.<br> 
Podemos categorizar os endereços de IP em <b>sete tipos</b>: <i>público, privado, estático, dinâmico, dedicado, compartilhado e de classe</i>. Mas o que interessa pra gente agora é o <b>Público</b>, <i>utilizado para se comunicar com a Internet</i>, e o <b>Privado</b>, <i>utilizado para redes domésticas e corporativas</i>.<br>
- <b>MAC - Media Access Control</b>: Refere-se ao <b>endereço físico da máquina</b>, ou seja, gravada em hardware na placa de rede. Ao contrário do IP que pode ser mutável, o MAC pode ser apenas <b>falsificado</b> através de <i>técnicas de spoofing</i>.</p>
<p>Para ver seus endereços de IP e MAC no <b>Windows</b>, basta acessar as propriedades da placa de rede ou abrir o <b>cmd</b> e digitar: <i>"ipconfig /all"</i>.</p>
<p>.</p>
<p><b>1. Protocolos de Comunicação e Ameaças à Segurança:</b>
<p>Antes de falarmos diretamente sobre o tema do post, é necessário abordar alguns tópicos sobre <b>Segurança</b> para podermos <i>elucidar alguns mitos</i> e darmos uma continuidade sólida ao tema.<br>
Desde 1990, o protocolo <b>HTTP</b> é utilizado como <i>base de comunicação de dados entre navegadores e sites</i>, portanto, <b>todas as informações são transferidas entre um cliente e um servidor</b>. Todavia, sabemos que essas informações podem ser <b>interceptadas, manipuladas ou roubadas facilmente por qualquer pessoa</b>.<br>
Para dar segurança extra as comunicações, foi criado o protocolo <b>HTTPS</b>, que é aquele <i>cadeado</i> que fica ao lado da barra de endereço. Ele utiliza um protocolo de criptografia chamado <b>TLS - Transport Secure Layer</b> <i>(antes conhecido como SSL - Secure Socket Layer)</i>, que obriga toda informação que será transmitida a passar por um processo de <b>cifragem</b> e <b>autenticação</b>.</p>
<p>Exemplo:</p>
<p><b>Antes da encriptação:</b><br>
{% highlight ruby %} Oi, Google Chrome! Faz o favor de entrar no YouTube? {% endhighlight %}
<p><b>Depois da encriptação:</b><br>
{% highlight ruby %}  laI3/ViNFcViv4Bxe3FKITFVvgvdXCruFu5PWW5MWeod8FXhqdtM05SWF8uUiRa7YOXsG9Z4LkIcUV4wj8uzLg== {% endhighlight %}<br>
<i>(Isto está cifrado em AES-128, que é utilizado para verificação de integridade, autenticação e garantir a segurança de informações num servidor)</i></p>

<p>Contudo, só porque um site tem um cadeado/HTTPS, não quer dizer que suas informações estão completamente seguras. Só o HTTPS sozinho não funciona para nada, pois existem dois tipos de ataques que fazem ele ser <b>praticamente inútil</b>:<br>
- <b>MITM - Man In The Middle</b>: É quando há uma interceptação de informações entre o cliente e servidor, agindo como uma ponte. O problema do MITM é uma <i>vulnerablidade</i> chamada <b>"SSL Strip"</b>, que, enquanto o atacante faz análise do tráfego de pacotes, ele faz uma <b>requisição HTTP</b> para interceptar as informações do cliente antes de chegar no servidor, <b>mas continua mantendo a conexão HTTPS entre ele e o servidor</b>.<br>
Normalmente para o usuário que está sofrendo ataque, pode <b>RARAMENTE</b> ocorrer avisos de <b>página não segura</b>, certificados inválidos, erros do tipo <b>"302 - Found"</b> sobre redirecionamento de páginas, carregamento lento, páginas que tentam simular logins reais de sites famosos...<br>
- <b>Session Hijacking - Sequestro de Sessão</b>: É um tipo de MITM, porém ele <b>sequestra o cookie</b> da sua sessão.<br>
Cookies são pedaços de scripts utilizados para guardar informações sobre a máquina e o navegador





<p>________________________________________________________________________________________________________</p>
<p><b>REFERÊNCIAS</b></p>
<p>- CloudFlare: What is HTTPS. <https://www.cloudflare.com/pt-br/learning/ssl/what-is-https/><br>
- NordVPN: Tipos de Endereço de IP. <https://nordvpn.com/pt-br/blog/tipos-de-ip/#:~:text=%C3%A9%20VPN%3F%E2%80%9D.-,Quais%20s%C3%A3o%20os%20tipos%20de%20IP%3F,%2C%20privado%2C%20est%C3%A1tico%20e%20din%C3%A2mico.><br>
- HostGator: Different Types Of IP Address. <https://www.hostgator.com/help/article/ip-address-static-vs-dynamic-public-vs-private-shared-vs-dedicated><br>
- NetCraft: 95% of HTTPS servers vulnerable to trivial MITM attacks.<https://news.netcraft.com/archives/2016/03/17/95-of-https-servers-vulnerable-to-trivial-mitm-attacks.html><br>
- 
---
layout: post
title:  Criptografia e Blockchain
date:   2021-03-18 08:32:20 +0300
description:  # Add post description (optional)
img: correios4.jpg # Add image post (optional)
tags: [Segurança]
author:
---
<center><strong></strong></center> 

<p><b><h3>O QUE É CRIPTOGRAFIA?</h3></b><br>
Criptografia é a ciência de manter os dados seguros longe de entidades não confiáveis ou indesejadas. 
Ela é o fundamento da Segurança da Informação.

CONSTRUÇÃO DO ALGORITMO / PROVA MATEMÁTICA DE QUE A CONSTRUÇÃO DO ALGORTIMO SATISFAZ A DEFINIÇÃO

<p><b><h3>POR QUE CRIPTOGRAFIA É IMPORTANTE?</h3></b><br>


<p><b><h3>OBJETIVOS DA CRIPTOGRAFIA:</h3></b><br>


<p><b><h3>APLICAÇÕES DA CRIPTOGRAFIA:</h3></b><br>
Privacidade
Autenticidade
Integridade

Prevenir Falha de Single Point, pois a informação está armazenada num único local e é relativamente fácil de comprometê-la.
Uma das soluções seria distribuir ou compartilhar a chave da informação sensível entre múltiplas localidades. Onde através da aquisição das diversas chaves somente será possível obter a informação sensível.

No sistema RSA, "N" é parte da chave-pública de encriptação e sua palavra-secreta de decriptação depende dos fatores "P" e "Q".
Gráficos isomóficos


<p><b><h3>CRIPTOANÁLISE DE ALGUMAS CIFRAS NA HISTÓRIA:</h3></b><br>
CIFRA DE CÉSAR (shift cipher), ataque de bruteforce com as 26 cahves diferentes
Princípio do espaço-chave suficiente: Qualquer cifra segura deve conter uma chave-espaço que não é vulnerável a tentativas exaustivas
Cifra de substituição/permutação monoalfabética: Cifra de césar com permutações, 26! = 2**88 tentativas para brute force

Cifra de Vigenere, Cifra alemã, 
Cirptografia clássica era considerada uma arte, mas sem muitos fundamentos cientificos
Criptografia moderna, baseada em métodos cientificos e principios

Segurança perfeita é sempre desejável, porém ela tem um preço:
- A chave deve ser do tamanho da menssagem
- Uma chave é gerada a cada instância de encriptação

A criptografia moderna segue um approach diferente:
- Tenta chegar perto da segurança perfeita
- Quer se livrar das limitações práticas imposta pela segurança perfeita = pequena e chaves reutilizáveis

As ideias básicas da segurança computacional são:
- Segurança preservará apenas contra adversários eficientes, que deverão ter bastante trabalho
-- Como matematicamente definimos adversários eficientes?
- Adversários estão permitidos a quebrar o esquema com alguma probabilidade, que é tão pequena que não incomoda
-- Como matematicamente definimos pequena probabilidade?




<p><b><h3>TIPOS DE CRIPTOGRAFIA:</h3></b><br>
- <b>Redes Sem Fio:</b>

- <b>Criptografia Simétrica:</b>
Computacionalmente eficiente, porém as chaves não estarão muito seguras. As chaves serão iguais para descriptografar a mensagem
Algoritmo determinístico
Algoritmo randomizado, depende dos valores randomicamente gerados

SINTAXE DA ENCRIPTAÇÃO DE CIFRA SIMÉTRICA
As cifras são coleções de 3 algortimos (Gen, Enc, Dec)
Gen (Generator): escolha do algoritmo, para definir todas as possiblidades de saída da chave, gerado internamente. Pode ser randomizado
Enc (Encriptação): Será a forma gerada internamente para expor a cifra externamente, que então definirá todas as possibilidades da saída da mensagem cifrada. Pode ser randomizado
Dec (Decriptação): Sempre será um Algoritmo Determinístico. Apenas definirá todas as possibilidades da mensagem descriptograda

USOS TÍPICOS DE UMA CIFRA ASSIMÉTRICA
Gen, Enc, Dec são publicamente conhecidos.
Executar o Gen e compatilhar a chave de acesso do início ao fim
Encriptar a mensagem e enviar a chave para outra entidade
A entidade irá descriptografar a menssagem utilizando a chave
Para usos de privacidade (não muito comum), a chave não poderá revelar nada sobre o texto e vice-versa
O processo de encriptação é seguro se o texto ou a chave não revelar nada sobre ambos

TIPOS DE ATAQUES
Ciphertext-Only Attack (COA): Ataque mais simples, o atacante terá acesso a cifra
Known plaintext attack (KPA): O atacante terá acesso a várias informações da cifra e da mensagem. Todas as mensagens criptografadas não permanecem privadas indefinidamente. 
Chosen plaintext attack (CPA): O atacante não sabe quem é o rementente e o destinatário, mas sabe que existe uma cifra
Chosen ciphertext attack (CCA): O atacante tem já sabe qual o algortimo de encriptação e escolhe quais mensagens ele quer decriptar, podendo ou não saber quem é o rementente ou destinatário

PRINCÍPIO DE KERCKHOFF
Para manter segurança, a chave deve ser sempre privada, definir o tamanho da chave, deve ser fácil de substituir a chave se ela for exposta.
É perigoso utilizar esquemas de criptografia propietárias
O algortimo pode ser vazado ou passivo de engenharia reversa
"Um sistema criptográfico deve ser seguro mesmo que tudo sobre o sistema, exceto a chave, é de conhecimento público"


Perfect security, pseudo-random generator (PRG), stream ciphers, pseudo-random functions (PRF), block ciphers, message-authentication codes (MAC), hash functions, DES, AES





- <b>Criptografia Assimétrica:</b>
Computacionalmente ineficiente, mas não haverá muitos problemas com a segurança das chaves


Teoria dos Números, Diffie-Hellman key-exchange protocol, ElGamal encryption scheme, RSA encryption scheme, Digital signatures

- <b>Certificado Digital, Assinatura Digital e Autoridade de Certificação (CA):</b>

- <b>ECDSA (Elliptic Curve Digital Signature Algorithm):</b>

- <b>Funções Hash:</b>

- <b>DHT (Distributed Hash Table):</b> 

<p><b><h3>BLOCKCHAIN:</h3></b><br>


<p>_________________________________________________________________________________</p>
<p><b>REFERÊNCIAS</b></p>
<p>- <b>KATZ, Jonathan; LINDELL, Yehuda</b>. Introduction to Modern Cryptography;<br>
- <b>STINSON, Douglas</b>. Cryptography: Theory and Practice;<br>
- <b>SMART, Nigel</b>. Cryptography: An Introduction;<br>
- <b>BONEH, Dan; SHOUP, Victor</b>. A Graduate Course in Applied Cryptography;<br> 
- <b>RETSKIN, Sion</b>. Hands-On: Dark Web Analysis. Packt, 2018.<br>
- <b>MENEZES, Alfred; VAN OORSCHOT, Paul; VANSTONE, Scott</b>. Handbook of Applied Cryptography;<br>
-  



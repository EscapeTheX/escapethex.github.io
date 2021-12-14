---
layout: post
title:  01# Boas Práticas de SI - Autenticação Baseada em Usuário e Senha
date:   2022-01-02 08:32:20 +0300
description:  # Add post description (optional)
img: .jpg # Add image post (optional)
tags: [Segurança]
author:
---
<p>Dando início a série 

<p> </p>

<p><b><h3>1. SEGURANÇA FUNDAMENTAL:</h3></b></p>
<p>Nesta sessão quero lhe apresentar <b>conceitos fundamentais e em comum de várias tecnologias</b> <i>(para evitar a repetição nos próximos tópicos)</i>, como numa espécie de dicionário de termos técnicos ordenado de forma cronológica, seguido de dicas específicas para as correspondentes.<br>
Cada tópico específico estará dividido em <i>níveis de prioridade</i>, sendo <b>"ALTA"</b> para uso obrigatório, <b>"RECOMENDADA"</b> para utilização mediante a disponibilidade e <b>"OPCIONAL"</b> para aprimoramento adicional de privacidade.

<p> </p>

<p><b><h3>1.1 CONCEITOS BÁSICOS E EM COMUM:</h3></b></p>

<p><b>1.1.1 AUTENTICAÇÃO BASEADA EM USUÁRIO/SENHA:</b></p>
<p>Existem vários fatores que podem comprometer suas credenciais de acesso (usuário e senha) e que, em quase sua totalidade, são originados de falhas humanas toscas. Claro, conforme o avanço da tecnologia, as metodologias utilizadas por criminosos também se sofisticam. Mas isso não é motivo para deixar de cuidar da sua privacidade com o pensamento de que uma hora você também será uma vítima.</p>

<p> </p>

<p><b>1.1.1.1 O QUE É BRUTEFORCE?</b><br>
É um conjunto de técnicas baseado na tentativa e erro para se descobrir informações de credenciais e páginas ocultas.<br>
- <b>Ataque Simples:</b> Consiste em tentar adivinhar pela lógica (normalmente por padronização) e sem a assistência de ferramentas. Normalmente utilizado em painéis de controle e páginas de roteadores;<br>
- <b>Ataque de Dicionário:</b> É o tipo de ataque mais comum, onde o atacante escolhe um alvo e aplica um dicionário de palavras no usuário. Pode-se personalizar esses dicionários através da incrementação de caracteres alfanuméricos e especiais. E atualmente, com a grande quantidade de vazamento de dados, os dicionários se baseiam em listas desses vazamentos;<br>
- <b>Spidering:</b> Consiste na técnica de coletar informações sobre o alvo e criar um dicionário personalizado;<br>
- <b>Bruteforce Reverso:</b> Consiste em adivinhar o usuário com base na senha;<br>
- <b>Preenchimento de Credenciais:</b> É um erro comum as pessoas utilizarem as mesmas credenciais para vários serviços. Então, se o ataque tiver sucesso num serviço, é normal que o atacante tente as mesmas credenciais em outros serviços também;<br>
<i>*As técnicas são praticamente as mesmas para o Bruteforce em páginas ocultas.</i></p>

<p> </p>

<p><b>1.1.1.2 A PROBLEMÁTICA DOS INFOGRÁFICOS DE BRUTEFORCE:</b><br>
É provável que você já tenha visto algum infográfico sobre a efetividade (em complexidade e comprimento) da sua senha contra ataques de Bruteforce. O que pode parecer uma simples forma de alerta para a população gostaria de abordar o quão problemático podem ser os infográficos sobre Bruteforce.</p>

<p><center>
<img src="/salamandra/chartsec.jpg" alt="Exemplo de infográfico sobre Bruteforce">
<figcaption><i>Exemplo de infográfico sobre Bruteforce</i></figcaption>
</center></p>

<p><a href="https://raw.githubusercontent.com/EscapeTheX/escapethex.github.io/master/salamandra/infotropia.jpg">São raros os exemplos de infográficos que contém informações detalhadas</a> sobre efetividade de entropia, algoritmo utilizado, software utilizado e suporte de hardware, configurações da máquina, autenticação multifatorial, tentativas por sessão, técnicas de wordlists... O intuito, infelizmente, é somente para alertar a população sobre o cuidado que se deve ter com suas senhas, sem explicar os diversos outros fatores que influenciam nesse processo. Somente a quantidade de caracteres e complexidade não quer dizer muita coisa, apenas se pode ter uma noção básica.</p>

<p> </p>

<p><b>1.1.1.3 ALGORITMOS DE CRIPTOGRAFIA:</b><br>

<p> </p>

<p><b>1.1.1.4 FUNÇÕES HASH E RAINBOW TABLES:</b><br>

<p> </p>

<p><b>1.1.1.5 ENTROPIA:</b><br>
No contexto da criptografia, a entropia se refere a uma medida de efetividade de uma senha contra um adversário e ela depende de 3 fatores:<br>
- Comprimento:
- Tipos de Caracteres:
- Imprevisibilidade:
 Cada tipo de caractere possui uma quantidade específica de bits, sendo o mínimo de 50 bits como um ideal seguro para a combinação.<br>
- <b>Números (0-9):</b> 3.322 bits;<br>
- <b>Caracteres Minúsculos (26):</b> 4.7 bits;<br>
- <b>Caracteres Maiúsculos (26):</b> 4.7 bits;<br>
- <b>Caracteres Especiais (32):</b> 5 bits;<br>
*Senha Exemplo 1: password123 = 56.87 bits
*Senha Exemplo 2: P@$$w0rD123 = 65.55 bits




<p>_________________________________________________________________________________________________________________</p>
<p><b>REFERÊNCIAS</b></p>
<a href="https://github.com/Lissy93/personal-security-checklist">Lissy93 - Personal Security Checklist</a><br>
<a href="https://www.kaspersky.com/resource-center/definitions/brute-force-attack">Kaspersky - Brute Force Attacks</a><br>
<a href="https://www.omnicalculator.com/other/password-entropy#what-is-password-entropy">Omnicalculator - Password Entropy Calculator</a><br>
<a href="https://www.gov.br/anpd/pt-br/documentos-e-publicacoes/checklist-vf.pdf">ANPD - Checklist de Medidas de Segurança para Agentes de Tratamento de Pequeno Porte (PDF)</a><br>
<a href="https://cartilha.cert.br/">CERT - Cartilha para Segurança na Internet</a><br>
<a href="https://portal.tcu.gov.br/lumis/portal/file/fileDownload.jsp?fileId=8A8182A24F0A728E014F0B226095120B">TCU - Boas Práticas em Segurança da Informação (PDF)</a><br>
<a href="https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-86.pdf">NIST 800-86 - Guide To Integrating Forensic Techniques Into Incident Response (PDF)</a><br>
<a href="https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf">NIST 800-53 - Security & Privacy Controls For Information Systems And Organizations</a><br>
<a href="https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.01162020.pdf">NIST Privacy Framework (PDF)</a><br>
<a href="https://www.trt4.jus.br/portais/governanca/politica-seguranca-informacao">TR4 - Políticas de Segurança da Informação</a><br>
<a href="https://paper.bobylive.com/Security/CIS/CIS_Controls_v8_Guide.pdf">CIS Controls v8 (PDF)</a><br>
<a href="https://www.mitre.org/sites/default/files/publications/16-3713-finding-cyber-threats%20with%20att%26ck-based-analytics.pdf">MITRE - Finding Cyber Threats with
ATT&CK (PDF)</a><br>
<a href="https://www.cnj.jus.br/wp-content/uploads/2021/03/AnexoVManualReferenciaPrevencaoMitigacaoDeAmeacasCiberneticasConfiancaDigitalRevisadoREV.docx.pdf">Manual de referência – Prevenção e Mitigação de Ameaças Cibernéticas e Confiança Digital (PDF)</a><br>
<a href="https://portswigger.net/web-security/all-materials">PortSwigger - Web Security Leaning Materials</a><br>
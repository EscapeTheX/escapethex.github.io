---
layout: post
title:  Guia - Boas Práticas de Segurança da Informação
date:   2022-01-02 08:32:20 +0300
description: Apenas Mais Um Guia de Segurança da Informação. # Add post description (optional)
img: .jpg # Add image post (optional)
tags: [Segurança]
author:
---
<p>Olá,<br>
No post de hoje quero trazer um Guia de Boas Práticas de Segurança da Informação 

<p> </p>

<p><b><h3>1. CONCEITOS BÁSICOS E EM COMUM:</h3></b></p>
<p>Nesta sessão quero lhe apresentar <b>conceitos fundamentais e em comum de várias tecnologias</b> <i>(para evitar a repetição nos próximos tópicos)</i>, como numa espécie de dicionário de termos técnicos ordenado de forma cronológica.</p>

<p> </p>

<p><b>1.1 O QUE É BRUTEFORCE?</b><br>
É um conjunto de técnicas baseado na tentativa e erro para se descobrir informações de credenciais e páginas ocultas.<br>
- <b>Ataque Simples:</b> Consiste em tentar adivinhar pela lógica (normalmente por padronização) e sem a assistência de ferramentas. Normalmente utilizado em painéis de controle e páginas de roteadores;<br>
- <b>Ataque de Dicionário:</b> É o tipo de ataque mais comum, onde o atacante escolhe um alvo e aplica um dicionário de palavras no usuário. Pode-se personalizar esses dicionários através da incrementação de caracteres alfanuméricos e especiais. E atualmente, com a grande quantidade de vazamento de dados, os dicionários se baseiam em listas desses vazamentos;<br>
- <b>Spidering:</b> Consiste na técnica de coletar informações sobre o alvo e criar um dicionário personalizado;<br>
- <b>Bruteforce Reverso:</b> Consiste em adivinhar o usuário com base na senha;<br>
- <b>Preenchimento de Credenciais:</b> É um erro comum as pessoas utilizarem as mesmas credenciais para vários serviços. Então, se o ataque tiver sucesso num serviço, é normal que o atacante tente as mesmas credenciais em outros serviços também;<br>
<i>*As técnicas são praticamente as mesmas para o Bruteforce em páginas ocultas.</i></p>

<p> </p>

<p><b>1.2 A PROBLEMÁTICA DOS INFOGRÁFICOS DE BRUTEFORCE:</b><br>
É provável que você já tenha visto algum infográfico sobre a efetividade (em complexidade e comprimento) da sua senha contra ataques de Bruteforce. O que pode parecer uma simples forma de alerta para a população gostaria de abordar o quão problemático podem ser os infográficos sobre Bruteforce.</p>

<p><center>
<img src="/salamandra/chartsec.jpg" alt="Exemplo de infográfico sobre Bruteforce">
<figcaption><i>Exemplo de infográfico sobre Bruteforce</i></figcaption>
</center></p>

<p><a href="https://raw.githubusercontent.com/EscapeTheX/escapethex.github.io/master/salamandra/infotropia.jpg">São raros os exemplos de infográficos que contém informações detalhadas</a> sobre efetividade de entropia, algoritmo utilizado, software utilizado e suporte de hardware, configurações da máquina, autenticação multifatorial, tentativas por sessão, técnicas de wordlists... O intuito, infelizmente, é somente para alertar a população sobre o cuidado que se deve ter com suas senhas, sem explicar os diversos outros fatores que influenciam nesse processo. Somente a quantidade de caracteres e complexidade não quer dizer muita coisa, apenas se pode ter uma noção básica.</p>

<p><b>1.3 ALGORITMOS DE CRIPTOGRAFIA:</b><br>

<p><b>1.4 FUNÇÕES HASH E RAINBOW TABLES:</b><br>

<p><b>1.4 ENTROPIA</b><br>
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


<p><b><h3>2. SEGURANÇA FUNDAMENTAL:</h3></b></p>
 seguido de dicas específicas para as correspondentes.<br>
Cada tópico específico estará dividido em <i>níveis de prioridade</i>, sendo <b>"ALTA"</b> para uso obrigatório, <b>"RECOMENDADA"</b> para utilização mediante a disponibilidade e <b>"OPCIONAL"</b> para aprimoramento adicional de privacidade.

<p> </p>

<p><b><h3>2.1 CONCEITOS BÁSICOS E EM COMUM:</h3></b></p>

<p><b>2.1.1 AUTENTICAÇÃO BASEADA EM USUÁRIO/SENHA:</b></p>
<p>Existem vários fatores que podem comprometer suas credenciais de acesso (usuário e senha) e que, em quase sua totalidade, são originados de falhas humanas toscas. Claro, conforme o avanço da tecnologia, as metodologias utilizadas por criminosos também se sofisticam. Mas isso não é motivo para deixar de cuidar da sua privacidade com o pensamento de que uma hora você também será uma vítima.</p>






<p><b>O que é Hash?</b><br>

- <b>Rainbow Table:</b>
-     



<p><b>Acesso ao Banco de Dados:</b><br>

<p><b>O atacante já sabe sob qual algoritmo a senha está armazenada?</b> Texto puro, cifra simétrica, cifra assimétrica, hash?<br>

<p><b>O atacante já sabe a quantidade de caracteres da senha?</b>

<p><b>Qual é a configuração do sistema do atacante?</b> Quantas hash/s ele é capaz de processar?<br>

<p><b>O serviço utiliza Autenticação Multifatorial?</b>

podemos dizer que por enquanto, a quantidade de caracteres é a forma mais segura

<p><b>Quantas tentativas podem ser feitas por sessão?</b>

<p><b>O atacante utiliza Spidering para incrementar seu dicionário?</b>




<p> salt, bcrypt, se a senha estiver armazenada em md5 o tamanho não importa, para hashes sem limite de salt até 14 caracteres podem ser crackeados instantaneamente, para bcrypt 6 caracteres demoraria anos,

and be able to then run a program that generates every password commonly used or random to match a password in that database.

This is wrong or misleading because it assumes the hacker knows your password composition. The hacker cannot tell from the hash that it is only digits and thus cannot narrow his tests like this chart assumes. It's also misleading because it assumes the server is using a weak hash, which no serious organization does today. And also misleading because it (presumably) doesn't include salting effects which are a rainbow table speed bump.

<p>Quais são os parâmetros para uma boa senha?
- Comprimento: a senha deve conter 12+ caracteres
- Complexidade: a senha deve conter letras maiusculas e minusculas, numeros e caracteres especiais
- Imprevisibilidade: a senha não deve conter informações que possam te identificar

Tecnicas de quebra de senhas
- Ataque de dicionario: Envolve utilizar listas de palavras para quebrar a senha
- Bruteforce: Similar ao ataque de dicionario, porém se utiliza de algoritmos alfanumericos e simbolos para revelar a senha. Ex.: uma senha chamada "password" pode ser escrita "p@$$w0rd"
- Rainbow Table: Utiliza-se de hashs pré-calculadas. Assumindo que um banco de dados armazena as senhas em md5, podemos criar outro banco de dados em md5 com as senhas mais comuns. Então é feita a comparação da senha em hash com a senha armazenada no banco de dados. Se acontecer identificação, então temos a senha;



<p>Tenha cuidado redobrado com provedores que apresentarem essas práticas:<br>
- Armazenamento de credenciais em texto puro, sem criptografia;
- Armazenamento de credenciais com criptografia simétrica (mesma chave para codificação e decodificação);
- Suas credenciais são enviadas por e-mail;
- Não fornece autenticação multifatorial;
- Não permite a utilização de caracteres especiais na criação de senha;


<p> </p>

Se sua senha for muito pequena ou conter palavras sem nenhum tipo de formatação, ela poderá ser facilmente quebrada ou adivinhada sem qualquer esforço por parte do atacante.
<b>Vulnerabilidades:</b> Phishing, Bruteforce, Ataque de Dicionário, Engenharia Social, Malwares.
<b>Como Prevenir:</b> 


 Como princípio básico de uma senha forte, ela deve conter no mínimo 12 caracteres, sendo uma combinação de caracteres especiais (!@#$%&*()ç), números e caixa alta e baixa.
- Utilize uma senha para cada conta. Pois, se um atacante descobrir a senha de um serviço, ele utilizará a mesma para adentrar em vários outros.
- Não utilize informações pessoais nas suas senhas. Isso inclui nomes familiares, cpf, número de celular, nome de animais de estimação ou qualquer informação sobre seus gostos pessoais.
- Não utilize letras e números sequenciais ou varias letras repetidas (Ex.: batata99)
- Depois de um atacante obter acesso as suas credenciais, ele vai procurar qualquer tipo de informação que possa ser utilizado como senha e com isso montar um dicionário para ataques de bruteforce. Além, das informações como nomes, endereços, bancos para roubar dinheiro, falsificação de credencial e identidade.

<p>- <b>Não Reutilize Senhas:</b><br>
Caso você tenha se cadastrado num serviço em que tempos depois ele sofreu com vazamento de dados, esse banco de dados com senhas será utilizado para incrementar um ataque de bruteforce.


<p><b>1.1.2 AUTENTICAÇÃO MULTIFATORIAL:</b></p>

<p>- <b>Ative a Autenticação de Fator Múltiplo (2FA/MFA):</b><br>
A Autenticação de Fator Múltiplo é a combinação chave para dificultar a quebra das suas credenciais, onde você deve fornecer a senha em conjunto com outra ou várias formas de autenticação, sendo e-mail, celular, aplicativo gerador de códigos. O que significa que se, por um acaso você cair num phishing, malware ou vazamento de dados, o atacante não poderá fazer login, já que ele necessita de um segundo fator para poder ser autenticado. A maneira mais fácil é utilizar um aplicativo de autenticação no seu celular, ir nas configurações da sua conta e habilitar a 2FA/MFA. Na próxima vez que você fizer login, será gerado um código nesse aplicativo para a autenticação (geralmente funcionam de forma offline e possuem uma duração de 30 segundos).

<p>- <b>Mantenha Seguro os Códigos de Backup:</b><br>
Quando você ativa a 2FA/MFA, você geralmente recebe uma chave-mestra com vários códigos para caso você não tenha mais acesso ao seu aplicativo. Mantenha esses códigos seguros para prevenir perdas ou acesso não autorizado.

<p>- <b>Não utilize seu gerador de senhas para armazenar códigos de 2FA/MFA:</b><br>
Muitos gerenciadores de senhas permitem gerar códigos de 2FA/MFA. Porém, não é uma prática recomenda, já que se houver uma falha, tudo de uma vez será comprometido. 

<p>- <b>Não utilize reconhecimento facial para o acesso de suas credenciais:</b><br>
A maioria dos dispositivos modernos oferecem o reconhecimento facial para o acesso de credenciais, utilizando uma câmera para comparação de uma foto armazenada em hash. Por um ponto pode até ser conveniente, mas há várias maneiras de isso ser isso ser burlado, sendo a utilização de fotos digitais e reconstrução de câmeras de segurança. Ao contrário das senhas padrão, há muitas fotos da sua face na Internet, em documentos e videos de câmeras de segurança. Então, apesar de parecer conveniente, é uma falha crítica de segurança.

<p>- <b>Fique de olho em Keyloggers:</b><br>
Keyloggers são softwares ou hardwares que gravam e enviam todas as suas interações com o mouse e teclado para servidores remotos. Pode ser tanto um processo rodando em segundo plano quanto um dispositivo disfarçado e alocado na porta USB. As maneiras de se proteger incluem a verificação de processos suspeitos em segundo plano, checar quais dispositivos estão conectados no seu dispositivo, verificar se o mouse/teclado há algum sinal de modificação na sua carcaça e sempre considere levar o seu próprio dispositivo de I/O pessoal quando for possível. Dados digitados em teclados virtuais, colados da área de transferência ou autopreenchidos, dificilmente podem ser interceptados por keylogger de hardware. Então, se você estiver num dispositivo público, considere utilizar um teclado virtual. 


<p><b>1.1.2 AUTENTICAÇÃO BASEADA EM OUTROS MECANISMOS:</b></p>




<p><b><h4>1.2 CONCEITOS ESPECÍFICOS:</h4></b></p>




















<p><b><h4>1.2.1 SENHAS E AUTENTICAÇÃO:</h4></b></p>

<p><b>PRIORIDADE - RECOMENDADO</b></p>

<p>- <b>Utilize um Gerenciador de Senhas:</b><br>
Para a maioria das pessoas, é quase impossível de memorizar dezenas de senhas fortes e únicas. Um Gerenciador de Senhas é um aplicativo que gera, armazena e autopreenche suas credenciais de login. Todas as suas senhas serão encriptadas com uma chave-mestra (que também deve ser forte e você deve lembrar). A maioria dos gerenciadores possuem extensões nos navegadores e aplicativos mobile, então independente do dispositivo que você está, ele será autopreenchido. Tenha preferencia por aplicativos open-source.

<p>- <b>Cubra suas senhas em público:</b><br>
Quando você precisar digitar sua senha em público seja num smartphone ou notebook, procure não colocar a tela do seu dispositivo na visão de uma câmera e garantir que ninguém esteja olhando sobre seus ombros. Cubra e oculte sua senha enquanto você digita e não revele nenhuma senha em texto puro na sua tela.

<p>- <b>Não permita o armazenamento de senhas e informações em navegadores:</b><br>
A maioria dos navegadores atuais permitem o armazenamento de senhas e dados recorrentes. Porém, esses dados em sua maioria não são encriptados e quando são, utilizam um algoritmo fraco. Além de que, qualquer pessoa pode ter acesso a todas as suas contas e informações de uma só vez.

<p>- <b>Evite fazer login em dispositivos de terceiros:</b><br>
Não há como garantir que um dispositivo de alguém está livre de keyloggers ou spywares, especialmente em máquinas públicas, como de lan house em que o rastreamento é velado. Mas se o uso for quando não tiver alternativas, utilize a guia anônima, verifique se há processos suspeitos em segundo plano do sistema e se possível, modifique sua senha quando estiver no seu ambiente de confiança.

<p>- <b>Não utilize PIN de 4 dígitos:</b><br>
Não use um PIN curto para acesso ao seu dispositivo. Ao invés disso, use uma senha em texto ou um PIN com 8+ dígitos, apesar de que senhas numéricas são fáceis de quebrar.

<p>- <b>Considere utilizar um token de hardware (U2F/FIDO2):</b><br>
Um U2F/FIDO2 é uma chave de segurança que pode se apresentar nos formatos de um dispositivo USB ou NFC, que serve para autenticação em serviços online, verificar sua identidade. Soluções como SoloKey e NitroKey são exemplos que podem trazer vários benefícios de segurança. COMPLEMENTAR DEPOIS

<p><b>PRIORIDADE - OPCIONAL</b></p>

<p>- <b>Assine para receber alerta de vazamento de dados:</b><br>
Depois que um site sofre significantemente com vazamento de dados, suas informações são vendidas ou disponibilizadas livremente na internet. Vários sites coletam esses registros e permitem você procurar pelo seu e-mail para checar se você está nessa lista. Sites como Firefox Monitor, Have I Been Pwned e Breach Alarm, permitem que você receba notificações para monitoramento do seu e-mail, caso apareça em algum dataset vazado. É útil saber o quanto antes sobre isso, para que você possa mudar suas senhas nas contas afetadas. 

<p>- <b>Atualize suas senhas em contas principais periodicamente:</b><br>
Vazamentos de dados são comuns quando a brecha se torna pública, mas não tão comum quando a empresa não é exposta ou se nega admitir um vazamento. Então, é interessante periodicamente (anual/semestral/trimestral) atualizar senhas de contas principais. Porém, isso já não é mais recomendado para usuários corporativos, já que induz a criação de senhas fracas.

<p>- <b>Evite dicas de senhas:</b><br>
Alguns site permitem que você utilize dicas para lembrar da sua senha, em que normalmente se tornaria fácil de adivinhar sua senha. No caso em que este passo é obrigatório, utilize perguntas e respostas mais aleatórias possíveis. 

<p>- <b>Evite utilizar códigos de SMS como 2FA/MFA:</b><br>
Quando habilitar a autenticação de múltiplos fatores, opte por códigos baseados em aplicativos ou token por hardware, se suportado. SMS é suscetível à várias ameaças, como clonagem de SIM e interceptação. Também não há uma garantia de segurança de como o número do seu celular será armazenado ou para quais outras finalidades ele será utilizado. SMS só funciona se você tiver sinal da operadora, normalmente são lentas na entrega da mensagem e pode haver tarifas para envio da mensagem. 



<p><b><h4>1.2 NAVEGADORES:</h4></b></p>

<p><b>PRIORIDADE - ALTA</b></p>

<p>- <b>Bloqueie os Anúncios:</b><br>

<p>- <b>Cheque se o site que você está acessando é autêntico:</b><br>
Isso é óbvio, mas quando você está utilizando suas credenciais online, há algumas formas de ataques (MITM) que podem comprometer sua experiência. Quando se está visitando sites novos, verifique alguns sinais que indicam um site comprometido, como erros de digitação, avisos de navegação, redirecionamentos, spam, pop-ups. 

<p>- <b>Fique de olho em Malwares:</b><br>
Seu sistema pode ser comprometido por spywares, miners, hijackers, redirecionamentos maliciosos, supercookies, adwares... Usualmente isso pode ser prevenido ignorando, pop-ups, prestando atenção no que você clica, não proceder na navegação caso o navegador avise ser suspeito de malware... Sinais comuns de infecção por malware incluem sua homepage ou mecanismo de pesquisa sendo modificado, adição de barra de ferramentas, extensões e ícones não familiares, mais anúncios, erros, páginas que demoram mais para carregar do que o normal (salvo problemas de internet) e utilização mais significante de cpu, ram e gpu enquanto navegando. 

<p>- <b>Mantenha o seu navegador atualizado:</b><br>
Vulnerabilidades em navegadores são constantemente descobertas e consertadas, então é importante mantê-los sempre atualizados para evitar exploits zero-day. Alguns navegadores atualizam automaticamente para a versão mais estável.

<p>- <b>Sempre utilize HTTPS/HSTS:</b><br>
Se você digitar informações em sites que não utilizam HTTPS/HSTS, os dados serão transportados de forma não criptografada e poderão ser lidos por qualquer um que interceptar. Mas também não deixe o cadeado na barra de navegação te dar uma falsa sensação de segurança só porque ele utiliza um certificado com TLS e isso também não quer dizer que isso o torna seguro, já que é relativamente fácil forjar certificados. A extensão HTTPS-Everywhere é uma extensão que força todos os sites que você visita a utilizarem HTTPS automaticamente, desde que ele suporte. 

<p>- <b>entenda como sua identidade é formada através de habitos de navegação:</b><br>
Fingerprinting é uma metodologia acurada de rastreamento, onde um site pode identificar você baseado nas informações do seu dispositivo (OS, header, região, fontes, extensões, componentes de hardware).

<p>- <b>Gerencie seus cookies:</b><br>
Limpar cookies regularmente é um passo para diminuir o rastreamento de sites, anunciantes, analytics, em segundo plano. Extensões como Privacy Badger e uBlock Origin cumprem seu papel e estão disponíveis na maioria dos navegadores. Como alternativa, você pode bloqueá-los a nível de rede, como com Pi-Hole e Diversion. VPNs também oferecem funções básicas de bloqueio.

<p>- <b>Tenha cuidado com redirecionamentos:</b><br>
Alguns redirecionamentos podem parecer necessários (caso de links quebrados), enquanto outros são utilizados para ataques de phishing, que fazem com que o link pareça legítimo. Se você não tem certeza sobre um possível redirecionamento, utilize o RedirectDetective e também desabilite no seu navegador essa função. 

<p>- <b>Desabilite downloads automáticos:</b><br>
Permitir que sites transfiram seus conteúdos automaticamente é uma forma bastante simples de armazenar arquivos prejudiciais no seu dispositivo. Então tenha cuidado quando um site pede para você baixar algo inesperadamente ou sem aviso/solicitação; 

<p>- <b>Desabilite o acesso aos sensores do seu dispositivo:</b><br>
Sites em dispositivos mobile podem utilizar dos seus sensores embutidos sem te solicitarem. Se você der essas permissões no navegador, todos os site terão acesso a esses dados, sem que apareça notificações, solicitação de uso. A melhor solução é limpar a seleção de permissões do seu navegador mobile e utilizar navegadores focados em privacidade.

<p>- <b>Desabilite serviços de localização:</b><br>
Serviços de localização permitem que sites tenham acesso a sua localização física para "melhorar a sua experiência". Porém, esse é só mais um método de se obter informações sobre a sua localidade, já que isso também pode ser atribuído a informações aproximadas com seu IP, região, informações do dispositivo, DNS e ataques de correlação. 

<p>- <b>Desabilite o acesso a câmera e microfone:</b><br>
A não ser que você esteja utilizando alguma versão de navegador de um aplicativo, essas permissões de acesso devem ser desabilitadas e garantidas que nenhum site poderá ter acesso. O que inclui também como medida, utilizar tampas na webcam, bloqueadores do microfone e desabilitar o dispositivo quando não estiver em uso.

<p>- <b>Desabilite o armazenamento de usuários e senhas:</b><br>
Isso pode ser facilmente acessado por qualquer um que tiver acesso ao seu dispositivo. O Chrome protege seus dados através da credencial do Windows, mas que pode ser quebrado com ferramentas de redefinição de senhas.

<p>- <b>Desabilite o autopreenchimento de informações:</b><br>
Esse recurso é útil para preenchimento de dados em lojas online ou qualquer outro serviço que necessite disso. Mas o armazenamento de informações como nome, endereço, cartão de crédito, termos de busca, pode ser extremamente danoso se o seu navegador estiver comprometido. 

<p>- <b>Desabilite o WebRTC:</b><br>
Apesar do WebRTC fornecer uma comunicação de qualidade para audio/video e facilitar a transferência de arquivos via P2P diretamente do navegador, isso vai contra as medidas de privacidade, especialmente se você não usa proxy ou VPN. 

<p><b>PRIORIDADE - RECOMENDADO</b></p>

<p>- <b>Utilize navegadores focados em privacidade:</b><br>

<p>- <b>Utilize um mecanismo de pesquisa não-rastreador:</b><br>
Opções como DuckDuckgo, Startpage, Quant, SearX. 

<p>- <b>Remova extensões desnecessárias:</b><br>
As extensões dos navegadores normalmente possuem permissões para ler, registrar e modificar tudo o que você faz no navegador. Apesar de alguns ter funcionalidades inocentes ou serem bem úteis, podem esconder intenções maliciosas. Os sites podem ver quais extensões estão instaladas e podem utilizar isso para melhorar seu fingerprinting, para identificar você e te rastrear. Olhe as reviews, apenas instale aquelas que você realmente necessita, desabilite caso você não estiver utilizando no momento e as remova caso não seja mais utilizada.

<p>- <b>utilize guia anônima:</b><br>
Quando utilizar um dispositivo alheio, procure utilizar guia anônima para navegação. Isso previne que o histórico, cookies e que alguns dados sejam armazenados, mas não é uma solução para eliminar o rastreio.

<p>- <b>Desabilite serviços de autopreenchimento:</b><br>
Alguns navegadores permitem o autopreenchimento de dados, senhas e de URLs em tempo real. Se isso estiver habilitado, os dados serão enviados a cada tecla que você pressiona, ao contrário de quando você aperta enter. Você pode requer desabilitar isso para diminuir a quantidade de dados coletados.

<p>- <b>Desabilite notificação de push:</b><br>
Notificações são um método comum para que criminosos encorajam você a clicar em links maliciosos. Então desabilite essa configuração por padrão.

<p>- <b>Falsifique os vetores de rastreio por Canvas:</b><br>
Canvas é uma API HTML5 utilizada para renderização de gráficos e animações em páginas que utilizam Javascript. Fora disso, o Canvas é utilizado um método de rastreio, onde são enviadas imagens invisíveis para o seu navegador e retornam para o servidor com informações do seu computador e localização. 

<p>- <b>Falsifique o user-agent:</b><br>
O user-agent é um pedaço de texto que diz para o site quais são as informações sobre o seu dispositivo, navegador e versão que você usa. É um método de rastreio, então mudar periodicamente de user-agent é um pequeno passo para você ser menos único.

<p><b>PRIORIDADE - OPCIONAL:</b></p>

<p>- <b>Utilize DNS-over-HTTPS:</b><br>
As requisições tradicionais de DNS são feitas em texto puro para qualquer um que possa ver, o que permite a "escuta" e manipulação dos dados de DNS através de ataques MITM. DNS-over-HTTPS performa a resolução do DNS através do protocolo HTTPS, isso significa que os dados entre os dados entre você e a resolução do seu DNS serão encriptados. Uma opção popular é o Cloudflare (1.1.1.1). Porém, ele apresenta alguns problemas como prevenção de filtragem de conteúdo web.

<p>- <b>Utilize containers de multi-sessão:</b><br>

<p>- <b>Não faça login no seu navegador:</b><br>
Muitos navegadores permitem que você utilize sua conta para sincronizar com histórico, favoritos, senhas e outros dados que podem ser utilizados comumente em vários dispositivos. Porém, isso não só permite a coleta de dados múltipla, como também a consolidação de um perfil de usuário e que pode ser utilizado com maior eficácia por um atacante. 

<p>- <b>Proteja-se contra ataques de exfiltration:</b><br>
CSS Exfiltration é um forma de ataque onde suas credenciais e outros dados sensiveis podem ser transformados em CSS puro e isso significa que será inútil a proteção de desativar o Javascript. 

<p>- <b>Desative o ActiveX:</b><br>
ActiveX é uma API utilizada e ativada por padrão no Internet Explorer. Não é mais utilizada por sites legítimos. Porém, quando utilizado, fornece direitos de acesso íntimo e por isso deve ser desabilitado.

<p>- <b>Ignore o Do-Not-Track (DNT):</b><br>
DNT é um header de HTTP, suportado pela maioria dos navegadores, que quando ativado, envia uma flag para os sites dizendo que você não deseja ser rastreado. Ativar o DNT não tem praticamente impacto algum, já que muitos sites ignoram, não respeitam ou não seguem essa regra. Sendo de baixo uso, é conveniente desabilitar para evitar o perfilamento único, que traz consequências de fácil rastreio.

<p>- <b>Previna o rastreio de HTTP Strict Transport Security (HSTS):</b><br>
O HSTS foi feito para ajudar na segurança de sites, prevenindo ataques de downgrade de HTTPS. Porém, por questões de privacidade, permite que os administradores dos sites implantem super-cookies para continuar o rastreio mesmo no modo anônimo. 

<p>- <b>Previna a utilização de navegação em segundo plano:</b><br>

<p>- <b>Utilize navegadores de redes descentralizadas:</b><br>
O Tor provém um navegador que encripta e redireciona todo o seu tráfego através de múltiplos nós, mantendo uma navegação segura e com baixa interceptação e rastreio. Porém, sua velocidade de conexão decai, a experiência visual não é das melhores, assim como é possível haver vazamento de DNS, mas ele é tratado como um dos navegadores mais seguros atualmente.

<b>- <b>Desabilite o Javascript:</b><br>
Se você necessita de uma opção mais radical, desabilitar o javascript vai resolver boa parte dos problemas, mas com a consequência de limitar funções e visibilidade dos conteúdos da maioria dos sites. 



<p><b><h4>1.3 SERVIÇOS DE E-MAIL:</h4></b></p>

<p><b>PRIORIDADE - ALTA</b></p>

<p>- <b>Tenha mais de um endereço de e-mail:</b><br>
Considere utilizar diferentes endereços de e-mail para vários tipos de serviços, como contas em serviços triviais como em contas bancárias. Isso reduz o dano em potencial que uma conta pode ser acometida num vazamento de dados.

<p>- <b>Mantenha seu endereço principal privado/oculto:</b><br>
Nunca compartilhe seu e-mail primário publicamente, pois eles podem ser alvos de phishing.

<p>- <b>Mantenha sua conta segura:</b><br>
Use uma senha longa e única, ative autenticação multifatorial (2FA/MFA) e tenha cuidado no acesso. 

<p>- <b>Desative o carregamento automático de conteúdo:</b><br>
E-mails podem conter conteúdos potencialmente maliciosos e indesejados, como imagens, documentos de texto, planilhas e que são automaticamente carregados através do servidor. Isso deve ser desabilitado, pois pode haver a exposição do seu endereço de IP e informações do seu dispositivo, no que é utilizado para rastreio.

<p>- <b>Fique atento quanto as assinaturas de e-mail:</b><br>
spoof de cabeçalho

<p><b>PRIORIDADE - RECOMENDADO</b></p>

<p>- <b>Utilize um domínio personalizado:</b><br>

<p>- <b>Desative respostas automáticas:</b><br>
Apesar de ser conveniente preparar uma mensagem automática para quando você não estiver disponível, isso pode ser utilizado de má fé. O atacante vai saber o porquê de você demorar a responder, saberá algumas informações importantes e poderá utilizar isso para engenharia social e ataques direcionados.

<p>- <b>Escolha um protocolo de e-mail adequado:</b><br>
Não use protocolos obsoletos como IMAPv4 ou POPv3, pois eles possuem vulnerabilidades bem conhecidas e não possuem mais senso de segurança.

<p>- <b>Sempre utilize portas TLS:</b><br>
Há algumas opções de SSL para POP3, IMAP e SMTP, como portas padrões TCP/IP. Elas são fáceis de usar e são largamente suportadas. Por padrão, POP3=995, IMAP=993 e SMTP=465.

<p><b>PRIORIDADE - OPCIONAL</b></p>

<p>- <b>Utilize visualização de texto puro:</b><br>
Há duas formas de estilos de e-mail: a em texto puro e de HTML. HTML frequentemente possui identificadores como links e imagens, que constituem de identificadores e há consideráveis riscos de execução de código remoto no HTML do seu provedor de e-mail, que não pode ser explorado se utilizado em texto puro. 

<p>- <b>Não conecte/dê permissão para aplicativos de terceiros no seu provedor:</b><br>
A permissão de um aplicativo de terceiro pode lhe trazer alguns riscos, como o aplicativo ter acesso a sua caixa de e-mail e seus conteúdos, além de gerenciar e modificar seus conteúdos.

<p>- <b>Não transmita dados sensíveis via e-mail:</b><br>
E-mails são facilmente interceptados. Além de que você não tem a plena certeza do quanto é seguro o ambiente do destinatário. A não ser você o criptografe.

<p>- <b>Considere trocar por um provedor seguro:</b><br>
Alguns servidores como _____ possuem criptografia de ponta-a-ponta e políticas de segurança mais restritas. Diferente dos servidores típicos de e-mail, o seu conteúdo não pode ser lido a não ser você próprio, pois todo o conteúdo está criptografado. Provedores como Google, Microsoft, Yahoo escaneiam suas mensagens para anunciantes, analytics e por questões de lei. 

<p>- <b>Utilize uma chave inteligente na utilização de PGP:</b><br>

<p>- <b>Utilize aliases / sub-contas:</b><br>
E-mails que permitem a criação de contas secundárias no próprio domínio, permitem adereçar um único e-mail para cada serviço que você se inscrever. Isso significa que caso você comece a receber spam, você pode bloquear e determinar qual companhia deixou vazar seu endereço. E o mais importante, você não precisa revelar seu e-mail primário/real para nenhuma companhia. 

<p>- <b>Utilize sub-endereçamento:</b><br>



<p><b><h4>1.4 SERVIÇOS DE MENSAGEM:</h4></b></p>

<p><b>PRIORIDADE - ALTA</b></p>

<p>- <b>Apenas utilize mensageiros que possuem criptografia 2e2:</b><br>
E2E é um sistema de comunicação onde as mensagens são encriptadas no seu dispositivo e não são reveladas até que se chegue no destinatário. Isso garante que qualquer atacante que interceptar o tráfego não poderá ver o conteúdo da mensagem, nem ninguém que tenha acesso aos servidores onde os dados estão armazenados. Se o aplicativo que você utiliza não é totalmente open-source, então seu sistema de encriptação não pode ser auditado, logo não deve ser confiável.

<p>- <b>Utilize uma plataforma confiável:</b><br>
Ele deve ser estável e ativamente gerenciado. O ideal é pesquisar por desenvolvedores confiáveis, com reputação. 

<p>- <b>Cheque suas configurações de segurança:</b><br>
Configure opções de segurança. ___ Desabilite opções como "lido por último", "ultima vez online", "notificação de digitação", desabilite sincronização de backup na nuvem, as opções de acessar em outro dispositivo.

<p>- <b>Assegure que o seu ambiente está seguro:</b><br>
Há várias formas do seu ambiente estar comprometido, monitorado ou interceptado. mantenha seus dispositivos atualizados, evitando malwares, cuidando de ataques de phishing, utilizando senhas fortes e mfa. Se voce ainda tiver duvidas quanto a isso, considere utilizar o roteamento do Tor.

<p>- <b>Desabilite serviços de nuvem:</b><br>
Os backups do whatsapp não são encriptados

<p>- <b>Cuide da segurança de grupo:</b><br>
Quanto mais participantes num grupo, maiores são os riscos. Há uma chance de que o adversário esteja entre os membros e passe despercebido. Periodicamente cheque se todos os participantes são legítimos e garanta que apenas membros confiáveis terão privilegios administrativos. Nem todos os mensageiros possuem criptografia para grupos.

<p><b>PRIORIDADE - RECOMENDADA</b></p>

<p>- <b>Use apenas mensageiros em plataforma open-source:</b><br>
A não ser que o aplicativo que você utiliza possua informações públicas sobre auditoria, que garantam que não há backdoors, vulnerabilidades ou outras questões de segurança, ele não deve ser confiado.

<p>- <b>Elimine metadados dos seus arquivos de midia:</b><br>
Metadados são "dados sobre dados" ou informações adicionais adicionadas a um arquivo ou transação. Quando você envia uma foto, gravação de audio, video ou documento, você pode estar revelando mais do que sua intenção, como vazando sua localização, dispositivo utilizado para produzir o conteúdo. Dados de Exif atrelados a imagens tipicamente incluem: nome e modelo do dispositivo, autor, data e hora, latitude e longitude de gps e informações da fotografia. Para proteger a sua privacidade, você deve remover esses dados antes de enviar o arquivo. Alguns aplicativos removem essas informações automaticamente, mas eles podem registrar isso antes de apagar.

<p><b>PRIORIDADE - OPCIONAL</b></p>

habilite mensagens autodestrutivas
evite sms
verifique as permissões do aplicativo
considere a jurisdição
utilize plataformas descentralizadas
utilize plataformas focadas em privacidade
quando disponível, utilize pfs



<p><b><h4>1.5 REDES SOCIAIS:</h4></b></p>

pense sobre suas ações publicas e privadas
todas as suas ações serão permanentes ou por um longo tempo determinado
revele o mínimo de informação
cuidado com o que você envia
não compartilhe seu numero ou e-mail
não dê permissões desnecessarias
cuidado com integrações de terceiros
evite publicar dados geograficos enquanto estiver no local
remova metadados antes de publicar arquivos de midia
implemente camuflagem nas suas midias
considere forjar seu gps quando estiver em casa
considere utilizar informações falsas
não utilize redes sociais



<p><b><h4>1.6 REDES:</h4></b></p>

modifique a senha do seu roteador
utilize WPA2/WPA3 e senhas fortes
mantenha o firmware do roteador atualizado
utilize uma vpn
proteja-se de vazamento de DNS e garanta sua segurança
use um protocolo seguro para vpn
evite roteadores baratos
crie uma lista branca de endereços MAC
modifique o endereço de ip local e padrão do roteador
coloque um nome aleatorio no SSID e depois oculte
adicione o termo "_nomap" no final do SSID para evitar cair em listas de scan
desabilite WPS
Desabilite uPnP
utilize uma rede de convidados para visitas
termine processos e serviços não utilizados no seu roteador
não tenha portas abertas
desabilite protocolos de acesso remoto
desative gerenciamento baseado em nuvem
gerencie o range de IPs corretamente
encaminhe todo o tráfego através do tor
desabilite a wifi para todos os dispositivos
não use wifi publica
use firewall, ngwf, hids, nids, 



<p><b><h4>1.7 DISPOSITIVOS MÓVEIS:</h4></b></p>

criptografe o seu dispositivo
desligue funcionalidades de conexão que não estão em uso
instale apenas aplicativos necessários, sendo a menor quantidade possivel
gerencie as permissões de aplicativos
apenas instale aplicativos da fonte oficial
cuidado com o carregamento do seu dispositivo
sim hijacking
desabilite anuncios personalizados
formatação apos varias tentativas de login
use firewall
reduza a atividade em segundo plano
ative o isolamento em sandbox para alguns aplicativos
utilize tor para roteamento de trafego
evite teclados personalizados
reinicie o seu dispositivo regularmente
evite sms
mantenha seu numero privado
cuide com stalkerwares
considere utilizar uma rom modificada



<p><b><h4>1.8 COMPUTADORES PESSOAIS:</h4></b></p>

mantenha seu sistema atualizado
criptografe seu dispositivo
faça backup dos dados importantes
cuidado com os dispositivos usb
ative o bloqueio de tela enquanto estiver ausente
desative cortana/siri
mantenha uma quantidade minima de aplicativos instalados e desinstale aqui que você não usa
gerencie permissões
não permita que seus dados de uso sejam enviados para a nuvem
evite biometria, reconhecimento facial
desligue seu computador ao invés de hibernar
não linque seu pc com contas da microsoft ou apple
cheque quais serviços de compartilhamento está em uso
não utilize conta de administrador para tarefas que não necessitam de privilegios
bloqueie sua webcam e microfone + filtro de privacidade
garanta segurança fisica para seu dispositivo
randomize seu mac na wifi
use um firewall
proteja-se de keyloggers
verifique a conexão do seu teclado
previna-se de ataques de injeção de teclas
não utilize antivirus gratuitos
verifique periodicamente por rootkits
coloque senha na bios
use um sistema focado em segurança
use vm
use compartimentalização
desabilite funções desnecessárias
ative o boot seguro
garanta segurança de acesso ao ssh
feche portas abertas que não estão em uso
implemente regras de controle de acesso
utilize canary tokens



<p><b><h4>1.9 INTERNET DAS COISAS:</h4></b></p>

renomeie os dispositivos para não especificar marca e modelo
desabilite camera e microfone quando não estiver em uso
entenda quais dados serão coletados, armazenados e transmitidos
configure opções de segurança e não deixe dados serem enviados para aplicativos terceiros
não linque seu IoT a sua identidade real
mantenha o firmware atualizado
proteja sua rede
cuidado com dispositivos vestiveis
não conecte seus iots criticos diretamente na internet
mitigue os riscos de alexa/siri/google
monitore a rede piamente
negue acesso a internet ao maximo de dispositivos
tenha ciencia dos riscos



<p><b><h4>1.10 FINANÇAS:</h4></b></p>

assine alertas de fraudes e monitoramento de cartões
aplique congelamento em cartões
use cartões virtuais
utilize dinheiro para transações locais
use criptomoedas para transações online
armazene suas criptos seguramente
compre crypto anonimamente
utilize varias moedas
aplique um alias para dar detalhes em compras online
utilize endereços alternativos de entrega



<p><b><h4>1.11 PROTEÇÃO DE DADOS SENSÍVEIS:</h4></b></p>

verifique o ambiente
não confie em notificações de popup
nunca deixe um dispositivo de boas
previna espiões de camera/microfone
deixe seus ombros protegidos
cuidado com stalkerwares
instale somente softwares com reputação e de plataformas oficiais
armazene seus dados pessoais seguramente
camufle dados pessoais de seus documentos
não assuma que um site é seguro por ter um certificado com nome reconhecido ou por utilizar HTTPS
use cartões virtuais para compras online
gerencie periodicamente permissões de aplicativos
nunca de informações pessoais quando for se desinscrever de um serviço
saia de listas de marketing
revise e atualize sua privacidade em redes sociais
compartimentalize
use endereços alternativos
use formas de pagamentos anonimos



<p><b><h4>1.12 SEGURANÇA FÍSICA:</h4></b></p>

destrua documentos sensiveis
saia de registros publicos
não revele informações em ligações
fique alerta
utilize um perimetro de segurança
assegure a segurança fisica dos seus dispositivos
mantenha seus dispositivos fora de visão
proteja seu pin
proteja-se de fraudes em caixas eletronicos
proteja seu endereço de casa
use pin, não biometria
reduza a exposição a cameras
burle o sistema de reconhecimento facial
proteja seu dna
 










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
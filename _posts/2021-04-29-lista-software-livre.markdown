---
layout: page
hide_footer: true
menubar_toc: true
toc_title: Índice
title:  "Lista de aplicações e recomendações de software livre"
date:   2021-04-29 16:00:00
author: Eduardo Lopes Dias
categories: ajuda
description: "Aqui colocaremos nossas recomendações de software livre para cada tarefa normalmente realizada com software proprietário"
published: true
canonical_url: https://csl-rp.github.io/ajuda/2021/04/29/lista-software-livre.html
hero_link: false
hero_image: false
image: false
comments: false
hero_title: true
---

## Introdução
Após conhecer o conceito de Software Livre e ter ao menos certa noção de sua imporância, a pergunta natural a se fazer é "O que posso fazer a respeito disso?". O primeiro passo é libertar sua própria computação pessoal utilizando software livre ao invés de suas contrapartidas proprietárias, que muitas vezes são mais usuais. 

Escrevemos este artigo para servir de referência em sua transição para software livre. Navegue pelo índice acima para encontrar software livre para suas aplicações específicas. Estas recomendações são voltadas a usuários de Windows (a propósito, [não perca tempo e experimente logo uma distribuição GNU/Linux](https://csl-rp.github.io/conceitos/2021/04/12/saber-gnu-linux/)) e GNU/Linux iniciantes.

Peço que tenha em mente que não tivemos a pretensão de sermos imparciais em nossas recomendações. Evidentemente, dêmos preferência aos programas que nós mesmos usamos ou que julgamos serem as melhores alternativas para iniciantes. Além disso, alguns programas "não recomendados" _são de fato livres_ com base em suas licenças -- neste caso, nossa recomendação contra seu uso parte do histórico e/ou modelo de negócios de suas distribuidoras (ex. Microsoft, Google, IBM, Oracle...), ou por incompatibilidade com GNU/Linux, ou por simples falta de funcionalidades. Escrevemos nomes de software proprietário em vermelho para facilitar identificação neste artigo. Pedimos ainda que envie os erros e sugestões adição e/ou modificação para o email csl@disroot.org.

## Edição de texto

### Texto simples
<center><img
 	src="https://csl-rp.github.io/assets/css/img/artigos/lista-software-livre/texto-simples.png"
	style="width: 40vw">
	</center> 
<br> 

Por _texto simples_ entenda editores voltados à manipulação de arquivos de texto curtos, não formatados e que não são códigos de programação (os famosos .txt). Usuários de GNU/Linux editam texto com notável frequência, então é bom que recomendemos um editor leve mas poderoso. O **Gedit** satisfaz estas estipulações com uma interface simples e com suporte a esquemas de cores, _syntax highlighting_, correção ortográfica, abas, além de plugins. 

As aventureiras podem ainda experimentar o **Vim** ou o **Emacs**, nossos editores favoritos. Estes são os editores mais populares entre entusiastas de software livre; eles são completamente orientados a teclado e permitem uma produtividade, conforto e extensibilidade incomparáveis entre editores simples ou mesmo IDEs, mas a custo de uma íngrime curva de aprendizado. Recomendamos pesquisar mais a respeito se esta breve descrição atiçou sua curiosidade.

Por fim, o **Atom** é um notório editor/IDE muito popular entre programadores, principalmente por fornecer extensibilidade sem sacrificar facilidade de uso. Hesitamos recomendá-lo por ser um editor bem mais pesado que as alternativas, o que o torna inadequado a usuários de computadores mais antigos. Mas vale a pena testar, em particular para os programadores.

### IDEs

<center><img
 	src="https://csl-rp.github.io/assets/css/img/artigos/lista-software-livre/ides.png"
	style="width: 40vw">
	</center> 
<br> 
## IDEs

Em um cenário comercial ou até mesmo no ambiente acadêmico frequentemente nos deparamos com prazos de entrega ou datas limite, seja para o desenvolvimento de soluções ou entregas de relatórios e trabalhos. Com o intuito de economizar tempo e acelerar a produtividade individual ou de grupos que trabalham com programação é que apresentamos a categoria de IDE - do inglês _Integrated Development Environment_.

As IDE oferecem uma gama de recursos para facilitar a vida de um programador combinando as atividades mais comuns - como editar, compilar e debugar o código - em um único lugar.

Das IDE que recomendamos temos como principal o **Eclipse** que apesar de feita para programação em Java, também suporta C/C++, PHP, Python, Scala e Kotlin através de plugins. O **Code::Blocks** é similar ao Eclipse no sentido de plugins para trabalhar em diversas linguagens fora do padrão C/C++ e Fortran. Temos ainda o **Atom** como descrito na categoria anterior, um framework que facilita a compatibilidade com os diversos aparelhos e SO mas que pode consumir muitos recursos do seu PC.

Em alternativa ao VSCode temos o **VSCodium** que é uma versão sem a presença de binários proprietários e telemetria que existe na versão original do VSCode. A Jetbrains oferece as Edições da Comunidade (do inglês Community Edition) que diferentemente das versões Ultimate, são livres em licença Apache 2.0.

Fica ainda a proposta do **Vim** e do **Emacs** que podem muito bem serem utilizados como IDE quando configurados com plugins.

_Contribuído por Murilo_

## Documentos

### Suítes Office
<center><img
 	src="https://csl-rp.github.io/assets/css/img/artigos/lista-software-livre/office.png"
	style="width: 40vw">
	</center> 
<br> 

Um dos empecilhos mais comuns na adoção de softwares livres é o fato de que softwares proprietários como Excel, Word, Powerpoint e afins se enraizaram profundamente em empresas e instituições de ensino, a ponto de serem, para muitos usuários, referencia única e imediata dos serviços que oferecem. Entretanto, é fácil mostrar que o Microsoft Office possui contrapartidas livres para todos os seus principais serviços.

Os programas das Suítes [**LibreOffice**](www.libreoffice.org/) e [**OnlyOffice**](www.onlyoffice.com/)  oferecem todas as ferramentas usuais para edição de textos, planilhas e slides em interfaces bastante similares (a com crase)s do Microsoft Office. As principais diferenças entre essas alternativas livres são que os programas do pacote **OnlyOffice** possuem interfaces particularmente parecidas com a de versões mais recentes de suas contrapartidas proprietárias, podendo ser vistas como mais esteticamente amigáveís ao usuário, enquanto o **LibreOffice** possui suporte a uma diversidade ampla de linguagens e permite uma maior variedade de integrações com softwares de terceiros, bem como permite adição de diferentes extensões aos seus programas.

Alguns leitores podem se perguntar da razão pelo qual a Suíte Office [**OpenOffice**](www.openoffice.org/) não foi mencionada, a justificativa simples passa pelo fato desse projeto não oferecer suporte a formatos proprietários como .docx, .xlsx e .pptx, não permitir uso associado a uma nuvem, e de que, na pratica, o projeto **LibreOffice** se trata de um projeto sucessor deste.

_Contribuído por Luis Guilherme Coelho_

### Visualizadores de PDF
<center><img
 	src="https://csl-rp.github.io/assets/css/img/artigos/lista-software-livre/pdfs.png"
	style="width: 40vw">
	</center> 
<br> 

É um verdadeiro crime como o Acrobat da Adobe se tornou sinônimo de visualizador de PDFs entre usuários de Windows, e o Foxit Reader se tornou sua principal alternativa. Com programas como estes, uma atividade tão trivial quanto ler um PDF se torna uma tarefa lenta e onerosa. Felizmente, usuários de GNU/Linux não se submetem a isso devido à grande variedade de visualizadores simples e leves à sua disposição, dentre os quais os principais também estão disponíveis para Windows.

O **Okular** e o **Evince** disponibilizam tudo que se poderia esperar de um visualizador de PDFs em uma interface simples e leve. O **Okular** em particular também tem suporte para o formato EPub e para edição básica de PDFs, o que o torna nossa principal recomendação para usuários de Windows. Usuários de GNU/Linux provavelmente já receberam sua distribuição com um bom leitor de PDFs específico de seu _Desktop Environment_ pré-instalado, caso contrário podem usar qualquer uma das recomendações acima. Você também pode simplesmente usar seu navegador Web (confira as nossas recomendações) como leitor padrão de PDFs.

Documentos em formato PDF geralmente não são feitos para serem editados, mas editores especializados para todas as plataformas estão disponíveis. Experimente o **Libreoffice Draw**, **Scribus**, ou mesmo um editor de imagens no geral, como o **Gimp**.

## Comunicação

### Mensageiros Instantâneos
<center><img
 	src="https://csl-rp.github.io/assets/css/img/artigos/lista-software-livre/instant-messengers.png"
	style="width: 40vw">
	</center> 
<br> 

Atualmente as vias de comunicações proprietárias estão se tornando um
padrão [de facto](https://en.wikipedia.org/wiki/De_facto), muitas vezes sendo obrigatórias no uso de certos serviços, o que é inaceitável. Diversos escândalos de espionagem surgem a todo momento nessas plataformas. O WhatsApp, por exemplo, tem deixado cada vez mais escancarada suas intenções, como consta em seus termos de serviço (mesmo que esses problemas de privacidade não estivessem explicitados em seus termos você jamais deveria confiar suas conversas a uma empresa que não possui nenhum compromisso com o software livre e com a privacidade).

A maneira mais acessível e fácil de se comunicar, no momento, vem sendo através do **Telegram**; este fornecendo mais recursos que a alternativa proprietária, inclusive. Ainda assim, o telegram não é uma alternativa 100% livre, pois o código rodado em seu servidor é proprietário, apenas o *client* (aplicativo) do telegram é livre, mas ainda assim utilizamos por ser o canal "mais livre" que pessoas de fora do movimento utilizam. O **Signal** é similar ao Telegram e também é livre, tendo inclusive o código de seu servidor livre também.

Ainda assim, as alternativas realmente livres são também aquelas que são descentralizadas ou federadas, ou seja, que não estão associadas a um único servidor, funcionando em um grupo de servidores operando em um padrão de comunicação, sendo estes também livres. Os protocolos de comunicação mais utilizados que permitem esse tipo de aplicação são o [**XMPP**](https://xmpp.org/) e a [**\[matrix\]**](https://matrix.org/). Para utilizar a estes meios de comunicação, você deve escolher dentre diversos aplitivos disponíveis que operam nestas redes. É importante ressaltar que independente da aplicação que escolher, você conseguirá se comunicar com qualquer pessoa nesta rede, não necessitando que a outra pessoa utilize a mesma aplicação que você. Você pode consultar [alguns dos *clients* \[matrix\]](https://matrix.org/clients/), podendo escolher tanto as versões para *smartphones* quanto para *desktop*, havendo até mesmo maneiras de se utilizar pela web em seu navegador. [Aqui](https://xmpp.org/software/clients.html) se encontram alguns *clients* que operam no protocolo XMPP.

_Contribuído por Carlos Eduardo Gallo Filho_

## Internet

### Navegadores Web
<center><img
 	src="https://csl-rp.github.io/assets/css/img/artigos/lista-software-livre/navegadores.png"
	style="width: 40vw">
	</center>
<br>

Hoje em dia a Web é o principal vetor de software proprietário e _spyware_ no formato de _cookies_ e rastreadores em _javascript_. Soma-se a isto o fato de que o uso do computador para muita gente se resume a abrir o navegador e depender de serviços Web para tudo, e temos essa situação em que a escolha correta de navegador Web é quase tão importante quanto a de sistema operacional. É necessário que o navegador seja rápido e possa garantir o mínimo de privacidade e anonimidade ao usuário enquanto ele navega este campo minado de rastreadores que é a Web atual.

É por estes motivos que o **Firefox** é nossa principal recomendação de navegador. O **Firefox** possui uma longa história como software livre e é o principal navegador entre distribuições GNU/Linux. Apesar de ser por padrão superior em termos de privacidade que o _spyware_ declarado da Microsoft e Google, ainda há muito que o usuário pode fazer para maximizar sua privacidade e anonimidade utilizando o **Firefox** com prejuízo mínimo às funcionalidades da Web; você pode conferir nossas dicas [neste link](https://csl-rp.github.io/dicas/2021/XX/XX/dicas-firefox.html).

Outro navegador livre que se destaca no quesito de privacidade é o **Brave**. Este é por padrão superior ao **Firefox** neste aspecto, e conta ainda com a funcionalidade [Basic Attention Tokens](https://basicattentiontoken.org/), uma maneira ética de suportar os criadores de conteúdo na Web sem rastreadores e anúncios indesejados. O **Brave** só não é nossa recomendação principal por utilizar a _engine chromium_, o que acaba por favorecer a hegemonia da Google em todos os aspectos da Web -- o **Firefox** é o único navegador atualmente relevante que utiliza uma _engine_ independente. Isso também torna o **Brave** mais pesado e lento em computadores antigos, mas este aspecto parece variar de usuário para usuário.

Por fim, vale destacar que, qualquer que seja o navegador que você utilize em seu computador, é necessário _também utilizá-lo em seu smartphone_. Não adianta nada usar algo que bloqueie rastreadores no PC e continuar usando o _spyware_ da Google ou Apple no celular!

## Multimídia

### Edição de imagens
<center><img
 	src="https://csl-rp.github.io/assets/css/img/artigos/lista-software-livre/imagens.png"
	style="width: 40vw">
	</center>
<br>

É inegável que o software restritivo da Adobe e da Corel são, ao mesmo tempo, ferramentas essenciais e pedras no sapato da maioria das pessoas que trabalham com design gráfico. Felizmente, o trabalho de profissionais e amadores em design gráfico não precisa ser tão oneroso em recursos, sejam eles computacionais, financeiros ou mentais, graças aos excelentes programas livres e desenvolvidos pela comunidade que temos à disposição.

**GIMP** e **Inkscape** são ferramentas completas e indispensáveis para qualquer usuário GNU/Linux que edite imagens _rasterizadas_ ou _vetoriais_, respectivamente. São programas amplamente utilizadas por usuários de Windows também. Um depoimento divertido do poder e suficiência destas ferramentas para uso profissional é a [palestra proferida por Elias Silveira no primeiro ConFLOSS](https://www.youtube.com/watch?v=wJb4t63Owbc&list=PL6myk7S68rf8M0NJm9F29MITfkXpN0Lzk). Como é comum com software livre, ambos possuem suporte a _plugins_, o que possibilita que elas sejam extendidas indefinidamente. Tudo isso com programas que respeitam as liberdades e a privacidade do usuário!

Reconhecemos que o **GIMP** em particular possui uma interface e funcionalidades pouco familiares a usuários veteranos de Photoshop, ou mesmo àqueles que só precisem realizar edições mais simples. Para tal, recomendamos o **Pinta**, um software com interface semelhante à do MS Paint mas também cheio de funcionalidades. Para criação de diagramas e edições mais simples de imagens vetoriais, o **Libreoffice Draw** é um bom quebra-galho. Desenhistas e fotógrafos podem conferir as seções dedicadas nesta lista para estas atividades.


## Computação científica

### Visualização e análise de dados

<center><img
 	src="https://csl-rp.github.io/assets/css/img/artigos/lista-software-livre/data-analysis.png"
	style="width: 40vw">
	</center> 
<br> 

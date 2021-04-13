---
layout: post
title:  "O que você precisa saber para instalar e usar uma distribuição GNU/Linux"
date:   2021-04-12 17:06:00
author: Carlos Eduardo Gallo Filho
categories: conceitos
description: "Neste artigo estarei abordando os principais conceitos necessários para o breve entendimento do processo de instalação e utilização de um sistema operacional GNU/Linux, com foco em usuários iniciantes que nunca tiveram contato com o sistema." 
published: true
canonical_url: https://csl-rp.github.io/conceitos/2021/04/12/sabergnulinux.html
hero_link: false
hero_image: false
image: false
comments: false
hero_title: true
---


# O que você precisa saber para instalar e usar uma distribuição GNU/Linux

Neste artigo estarei abordando os principais conceitos necessários para o
breve entendimento do processo de instalação e utilização de um
sistema operacional GNU/Linux, com foco em usuários iniciantes que
nunca tiveram contato com o sistema.


## Sistema operacional

A este ponto, você já deve ter lido sobre [O que é
GNU/Linux](link-oq-é-gnulinux). Resumidamente, este é um sistema
operacional, que faz o papel de fornecer um ambiente para a execução
de programas e utilização do computador. Distribuições GNU/Linux são
hoje a maneira mais acessível de se instalar um sistema operacional
livre em seu dispositivo. Por ser algo tão importante e complexo, o
sistema operacional é responsável pela maior gama de softwares
contidos em um computador, sendo o principal responsável pela
liberdade do usuário, e portanto, um ótimo primeiro passo para se
iniciar no software livre.

<center><img
src="https://upload.wikimedia.org/wikipedia/commons/f/fd/Operating_system_placement-pt.svg"
style="width: 25vw"></center> <center><i>Golftheman, [CC BY
3.0](https://creativecommons.org/licenses/by/3.0), via Wikimedia
Commons</i></center>


## Distribuições GNU/Linux

Uma distribuição GNU/Linux pode ser entendida como uma "versão" do
sistema operacional GNU/Linux, sendo construída em cima "do" GNU/Linux
e adicionando funcionalidades e modificações de maneira com que se
tenha um sistema operacional completo e estável para o usuário final,
pronto para ser **distribuído**. São diversos os sabores, cada qual
atendendo a necessidade de cada tipo de usuário.

<center><img
 src="https://csl-rp.github.io/assets/css/img/artigos/sabergnulinux/tux.png"
 style="width: 40vw"></center> <center><i>"MuseScore 2.0 Linux
 packages" by MuseScore is licensed with [CC BY
 2.0](https://creativecommons.org/licenses/by/2.0)</i></center>

A maioria das distribuições não são construídas do zero, elas se
baseiam em outras distribuições, como é o caso do [Linux
Mint](https://linuxmint.com.br), que possui versões construídas em cima
do Ubuntu e do [Debian](https://www.debian.org/index.pt.html), que são outras duas
distribuições GNU/Linux. Muita parte do conteúdo encontrado para uma
dada distribuição serve para as outras da mesma família e até mesmo
outras distribuições sem parentesco, sendo a família Debian de longe a
mais popular em _desktops_.

### Escolhendo uma distribuição
Dentre as distribuições mais voltadas à facilidade do usuário, estão o
Linux Mint, [Pop!_OS](https://pop.system76.com) e o
[Manjaro](https://manjaro.org). Estas em geral são pensadas em
funcionarem com o mínimo de esforço do usuário, não necessitando de
configuração excessiva e possibilitando uma instalação fácil, contando

também com diversos programas já pré-instalados. A escolha de uma
distribuição com esse fim normalmente é a mais indicada para usuários
que estão acostumadas a utilização do sistema operacional proprietário
Window$ ou não possuem experiência com o uso de computadores.

Caso se sinta confortável em ir a fundo no aprendizado do sistema
operacional GNU/Linux, é mais recomendável que se escolha uma
distribuição com uma documentação mais detalhada e até mesmo técnica,
como é o caso do próprio Debian e do [Arch
Linux](https://archlinux.org), que contem uma das mais completas wikis
disponíveis dentre as distribuições.

## Ambiente de trabalho

O ambiente de trabalho, ou _desktop environment_ (DE), é a camada
superior do sistema operacional responsável pela interação direta com
o usuário, através de aplicativos, _widgets_ e da própria disposição
das coisas, representando também o visual do sistema. Muitas vezes o
ambiente de trabalho é chamado erroneamente de "interface gráfica".

Por ser a camada mais superficial do sistema, essa é a parte na qual o
usuário realmente vai mais interagir, ditando de certa forma a maneira
com que você faz o uso do computador, sendo que os mais variados
ambientes de trabalho possuem suas peculiaridades que não se abstém ao
visual em si.

<center><img
src="https://csl-rp.github.io/assets/css/img/artigos/sabergnulinux/distros.png"
style="width: 75vw"></center> <center><i>Em ordem, KDE, Xfce,
Gnome e LXQt</i></center>

Muitas distribuições contam com certos ambientes de
trabalho suportados, como o Manjaro, por exemplo, que conta com os
ambientes [Gnome](https://www.gnome.org/), [KDE](https://kde.org/pt-br) e
[Xfce](https://xfce.org/?lang=pt_BR), que são uns dos ambientes mais
populares. Um ponto relevante na escolha do ambiente de trabalho é seu
_hardware_, ou seja, as especificações do computador que você está
usando. Para computadores mais antigos e mais modestos, ambientes como
o Xfce, [MATE](https://mate-desktop.org/pt) e
[LXQt](https://lxqt-project.org/) são mais recomendados pois são bem
leves.

É importante ressaltar que, por mais que a DE defina a estética e
fluxo de trabalho do sistema, a mesma também é altamente customizável
pelo usuário, claro que algumas mais e outras menos. Essa liberdade de
customização só é encontrada em softwares livres.

## Documentação

Software livre e documentação andam sempre de mãos dadas. Uma
documentação boa deve ser capaz de introduzir e explicar ao usuário
sobre o uso do software, através de manuais e wikis; fornecendo também
documentação técnica para o desenvolvimento do software em sí. Um
exemplo de ótima documentação é a [wiki do Arch
Linux](https://wiki.archlinux.org/), já citada anteriormente neste
artigo.

O uso da documentação da distribuição GNU/Linux ou de qualquer outro
software que seja é imprenscindível para a boa utilização e
aprendizado do mesmo. Portanto, você deve aprender a buscar ajuda não
apenas em fóruns e blogs, mas também nos próprios sites oficiais dos
softwares dos quais você busca por informação. Isso potencializa sua
liberdade e independência, pois evita que você apenas siga passos a
passos e permite que você entenda de fato o que está fazendo.

## Partindo para a instalação

Existem alguns processos que independem da escolha de distribuição,
sendo a [criação de uma mídia de inicialização]() e o _boot_.

Após ter a mídia de inicialização da sua distribuição escolhida, você
precisará fazer o _boot_ nesta. _Boot_ remete literalmente ao processo
de inicialização do sistema, ou seja, quando você liga o computador,
ele realiza o _boot_ e inicia o sistema que foi configurado para
carregar. Para selecionar o dispositivo que se deseja inicializar, no
caso, a mídia de instalação da distribuição escolhida, veja [como
_bootar_ em uma mídia de inicialização]().

Quando você já tiver inicializado na mídia de instalação, será o
momento em que você seguirá a documentação da distribuição escolhida,
onde necessariamente terá um guia de instalação mostrando e explicando
o "passo a passo" da instalação.

## O temido terminal

O terminal é algo que pode espantar um pouco usuários iniciantes no
GNU/Linux por aparentar ser algo difícil. Longe disso, o terminal é
algo que facilita, e muito, a sua vida. Claro, ao se escolher uma
distribuição mais voltada à facilidade de uso, você praticamente nunca
terá que usar o terminal. A linha de comando é uma interface
universal, um comando executado em uma distribuição GNU/Linux irá
fazer exatamente o mesmo que o mesmo comando executado em outra
distribuição.

<center><img
src="https://csl-rp.github.io/assets/css/img/artigos/sabergnulinux/terminal.png"
style="width: 40vw"></center>

Justamente por ser algo universal e que te dá maior controle sobre o
sistema, muitas coisas podem ser feitas mais eficientemente em um
terminal, como por exemplo, solucionar um problema. Portanto, é muito
aconselhável que você não tenha medo e tente se ambientar com o uso do
terminal, com certeza é algo que valerá muito a pena.

## Gerenciamento de pacotes

Nos sistemas GNU/Linux, todo software é instalado em forma de
pacote. Cada pacote denota, por exemplo, um programa em si; mas não
necessariamente, pois a maioria dos pacotes são **dependências**. As
dependências são softwares que são instalados para possibilitar o
funcionamento de um terceiro, isso seguindo a [filosofia Unix](), sistema
operacional predecessor ao GNU/Linux, os softwares devem ser simples,
específicos e eficientes, sendo que, sempre que um software precise de
uma função que já seja realizada por um terceiro, este deve fazer uso
do mesmo ao invés de realizar a mesma funcionalidade.

Para exemplificar, imagine que um software precise realizar a
visualização de uma imagem. Existe para isso, uma biblioteca que
permite o programa interpretar tal tipo de imagem e poder fazer com
que esta apareça na tela. Sendo assim, o visualizador de imagem fará
apenas o papel de usar tal biblioteca para visualizar tal formato de
imagem. Nessa forma, se há algum outro software que também precisa ler
imagens, este pode fazer uso da mesma biblioteca que o visualizador de
imagem utilizou, evitando que você tenha vários softwares para a mesma
coisa instalados e tornando o sistema como um todo mais eficiente. Por
isso, é esperado que inúmeros programas façam uso de uma mesma
dependência.

### Gerenciador de pacotes
Manusear os pacotes individualmente com certeza não é uma tarefa
fácil, e por isso, toda distribuição conta com um gerenciador de
pacotes. O gerenciador de pacotes é responsável por realizar a
instalação, remoção e atualização de pacotes, bem como administrar as
dependências do mesmo.

<center><img
src="https://csl-rp.github.io/assets/css/img/artigos/sabergnulinux/pacotes.png"
style="width: 60vw"></center> <center><i>Imagem traduzida de:
<https://itsfoss.com/package-manager> sob licensa [CC BY-SA
4.0](https://creativecommons.org/licenses/by-sa/4.0)</i></center>

Cada distribuição fica encarregada de fornecer os pacotes para os
usuários instalar, estes estão armazenados em servidores chamados de
**repositórios**. Basicamente, os repositórios atuam como um grande
banco de pacotes, possuindo todos os possíveis softwares que você
possa vir a desejar instalar. Cada distribuição possui seus próprios
repositórios, que são acessados pelo seu sistema quando se deseja
instalar ou atualizar os pacotes. Sendo assim, você não precisa buscar
cada programa que deseja instalar na internet, todos estão disponíveis
nos repositórios. Você pode fazer a instalação de softwares através de
algum aplicativo semelhante a uma "loja" ou pelo próprio terminal,
basta saber o nome do aplicativo que se deseja instalar.

Já que a administração do sistema é tão fácil, é importante que tudo
esteja sempre atualizado. Isso evita que falhas de segurança e bugs já
solucionados se mantenham no seu sistema. A utilização do gerenciador
de pacotes depende de qual sua distribuição, sendo que a este ponto,
você deve consultar a documentação da mesma para aprender de fato a
utilizar o gerenciador para instalar, remover e atualizar aplicativos.

## Conclusão

Com os assuntos tratados neste artigo, você deve ser capaz de entender
superficialmente os conceitos necessários para a utilização de um
sistema GNU/Linux. Claro que seria impossível explicar profundamente
cada tópico em apenas um artigo, a idéia é que isso possa te instigar
sua curiosidade e trazer certo conforto ao iniciar nesse mundo do
software livre, te fazendo perceber que usar software livre é muito
mais simples do que parece ser. Espero ter conseguido cumprir este
objetivo!

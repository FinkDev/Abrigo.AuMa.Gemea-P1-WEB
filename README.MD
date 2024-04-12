# Sobre o Site 💻

## Site de Avaliação P1 || Progamação Web 1 🌐

É apresentado aqui o Mini projeto de introdução a **Progamação Web 1** do curso de DSM na Fatec de Itaquera Miguel Reale.

Aqui você encontrará uma variedade de metodos de progamação baseados em HTML semântico e CSS, a fim de criar uma pagina de Website baseada em um dos modelos passados na atividade, neste caso o 4° modelo:

![Modelo de Website](/Imagens/modelo4.jpg">)

## Tema do projeto || Abrigo de Animais Au!Ma Gêmea 🐾

Com tema livre para composição do modelo base, foi escolhido a caracterização de um site web do estilo vitrine para um abrigo e centro de adoção de animais: **Au!Ma Gêmea**.

> [!NOTE]
> Empresa e caracterização puramente fictícios, criados por mim com intuito de tematizar a página.
>> Todos os animais apresentados no modelo final são apenas exemplos fícticios da pagina.

## Externos || Svg's, Icons e imagens 🎨

A fim de detalhar e dar maior profundidade ao resultado final, foram utilizados componentes e ferramentas externas as utilizadas comumente, como Visual Studio Code, Etc.

Para Icones e SVG's foi utilizado o site **[Flaticon.](https://www.flaticon.com/br/)** e **[Shape Divider App](https://www.shapedivider.app/)**

Para Imagens e demais Foram utilizados **[Freepik](https://br.freepik.com/)**, **[pngtree](https://pngtree.com/)** e demais **[repositórios de imagens](https://www.google.com/search?q=repositorios+de+imagens&oq=repositorios+de+imagens&gs_lcrp=EgZjaHJvbWUyBggAEEUYOdIBCDI1MDJqMGoxqAIAsAIB&sourceid=chrome&ie=UTF-8)**.

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  

# Contrução || Por que HTML Semântico? 🤨

Antes de mais nada o HTML semântico refere-se ao uso apropriado de elementos HTML de acordo com seu significado e propósito, em vez de apenas usar elementos com base em sua apresentação visual. Isso significa que cada elemento HTML usado em um documento deve descrever com precisão o tipo de conteúdo que ele contém. Segue abaixo algumas considerações sobre o assunto:
  
&nbsp;  
  
## Usabilidade do HTML Semântico:
### ***Melhor Estruturação do Conteúdo***  
A utilização de elementos semânticos apropriados (como header, nav, main, footer) ajuda os desenvolvedores a criar páginas bem estruturadas e significativas.

### ***Mais Clareza e Significado***  
Cada elemento tem um propósito específico e semântico, o que facilita a compreensão do conteúdo tanto por humanos quanto por máquinas (como motores de busca).

### ***Integração com Outras Tecnologias***  
Elementos semânticos facilitam a integração com outras tecnologias, como CSS e JavaScript, para criar interações mais ricas e acessíveis.

&nbsp;  


## Principais Benefícios do HTML Semântico:
### ***Acessibilidade***  
Um código semântico melhora a acessibilidade da web, tornando o conteúdo mais compreensível para tecnologias assistivas, como leitores de tela utilizados por pessoas com deficiência visual, sem contar que elementos semânticos ajudam a estruturar o conteúdo de maneira mais significativa.

### ***SEO (Search Engine Optimization)***  
Motores de busca como o Google podem entender melhor o conteúdo de uma página se o HTML estiver semântico. O uso adequado de tags e outros elementos semânticos pode melhorar o ranking nos resultados de pesquisa.

### ***Manutenção e Leitura do Código***  
Um HTML semântico é mais fácil de entender e manter, mesmo por outros desenvolvedores que não tenham criado o código originalmente. A estrutura clara do código torna mais simples realizar atualizações e correções.

### ***Flexibilidade e Adaptação***  
Um HTML semântico facilita a adaptação do conteúdo para diferentes dispositivos e plataformas. Frameworks responsivos, como Bootstrap, usam marcação semântica para fornecer uma base sólida para layouts responsivos. 

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  

# Sobre o CSS // "class", "id" e tags, o que é tudo isso? 🏷

É atravez do CSS que se customiza cada elemento presente na pagina HTML, desde elementos simples como div's até os mais diversos elementos semanticos etc... Mas como o CSS aplica cada único detalhe a cada único elemento? Simples, através dos seletores como class, id e das tags.

Na contrução do site, a "class", o "id" e as "tags" são diferentes tipos de seletores utilizados para se identificar e organizar elementos presentes no HTML, criando grupos ou até elementos unicos que podem ser identificados e customizados no CSS através destes identificadores cadastrados.

&nbsp;  


## Tags

As tags do Html não são nada mais nada menos que os elementos que o compõem, tais como: < div >, < ul >, < li >, < h1 > e etc. Cada um exerce uma função específica e pode assumir diferentes formas através da estilização CSS.  

Ao fazer uma referência direta na tag dentro do CSS, isso fará com que as características sejam herdadas por todos os elementos semelhantes presentes no site

***Por exemplo:***
```
p {
  color: blue;
  font-size: 16px;
}
```
Agora, todos os elementos de parágrafo "< p >" terão o texto da cor azul, e com 16 pixels de tamanho

&nbsp;  

## Classes

As classes por sua vez, são uma forma mais prática de caracterizar um certo elemento, ou até um grupo deles...  
Sendo aplicado dentro das tags de abertura de um elemento, a class dá um nome específico ao mesmo, que poderá ser utilizado no CSS precedidos por um ponto "." para referir a todos os elementos que possuam a mesma classe.

***Por exemplo:***

* No HTML:
```
<div class="destaque">Este é uma div com classe "destaque".</div>
<p class="destaque">Este é um parágrafo com classe "destaque".</p>
```

* No CSS: 
```
.destaque {
  background-color: yellow;
  font-weight: bold;
}
```

Neste caso, todos os elementos que possuem a classe "destaque", vão receber um fundo da cor amarela, e texto em negrito

&nbsp;

## ID's

As Id's por sua vez são bastante parecidas com as classes, porém, com um nivel de exclusividade a mais, podendo ser atribuídos a apenas um único elemento do HTML e sendo utilizados no CSS precedidos de uma hashtag "#" para referir aquele elemento específico.

***Por exemplo:***

* No HTML:
```
<div id="cabecalho">Este é o cabeçalho da página.</div>
<p id="cabecalho">Este é o cabeçalho da página.</p>
<h3 class="cabecalho">este é o subtitulo do cabeçalho<h3>
```

* No CSS:
```
#cabecalho {
  font-size: 24px;
  text-align: center;
  color: red;
}

.cabecalho {
    background-color: black
    color: white
}
```

Neste caso, por mais que ambos o < p > e a < div > tenham o mesmo id, e até a < h3 > tenha uma classe com o mesmo nome, apenas a < div > receberá as características especificadas com uma fonte centralizada, vermelha e com 24 pixels de tamanho.
## &nbsp;

&nbsp;  
&nbsp;  

## &nbsp;
### Projeto feito por Pedro Fink Silva || 1º DSM
&nbsp;
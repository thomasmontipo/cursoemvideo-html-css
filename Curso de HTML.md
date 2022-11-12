Curso de HTML - Curso em Vídeo

# Módulo 1

## Cabeçalho

Para abrir o cabeçalho digite "!" e depois pressione “enter”

	Alterar 

<html lang="pt-br">

    <meta charset="UTF-8">

## Parágrafos

Para adicionar um parágrafo digite <p> </p>

    <p> Um parágrafo aqui </p>

## Quebras de linha

Para quebra de linha insira < br > (broke row)

**Entrada**

    < p >Se precisar quebrar <br> o tecxto em algum <br> lugar  < /p>

        específico como esse <br>

**Saída**

![image alt text](https://github.com/thomasmontipo/curso-em-video-HTML-CSS/blob/estudo-html-css/images/image1.png?raw=true)

## Imagens

Bancos de imagens:

Unsplash

pexels

Para adicionar uma imagem basta adicionar a tag <img>

    <img src="" alt="">

Onde src= significa source ou "fonte" e alt= é a legenda para casos de acessibilidade.

Podemos adicionar imagens da mesma pasta que está o arquivo, clicando apenas ctrl + barra de espaço e selecionando o arquivo:

![image alt text](image_1.png)

Ou adicionar de uma pasta clicando na pasta e na imagem desejada ou colocar de um link externo (da web) apenas colocando a URL da imagem dentro de src="”

## Títulos

Vão de H1 até H6 e tem funções de títulos iguais a do word, por exemplo

## Comandos rápidos

Para inserir comandos rápidos, basta digitar ctrl + Shift + P, selecionar "Quebrar linha com abreviação" (Wrap with abreviature)

## Marca texto

**Entrada:**

        <h2>Texto marcado</h2>

        <p><mark>Este texto vai estar marcado</mark></p>

**Saída:**

![image alt text](image_2.png)

## Formatações

    <h1>Principais formatações</h1>

        <h2>Negrito</h2>

            <p>Nessa frase temos um <b>Termo em negrito</b> usando a tag B (não semântica)</p><!--b bolt (negrito)-->

            <p>Nessa frase temos um <strong>Termo em negrito</strong> usando a tag B (semântica)</p><!--strong (forte)-->

        <h2>Itálico</h2>

            <p>Nessa frase temos um <i>Termo em itálico</i> usando a tag B (não semântica)</p><!--Ide itálico-->

            <p>Nessa frase temos um <em>Termo em itálico</em> usando a tag B (semântica)</p><!--EM Em enfase-->

        <h2>Texto marcado</h2>

        <p><mark>Este texto vai estar marcado</mark></p>

        <h2>Texto grande e pequeno</h2>

        <p>Estamos criando um <big>texto grande</big> e um <small>texto pequeno</small></p> <!--Big é não semântica e Small é semântica-->

        <h2>Texto deletado</h2>

        <p><del>Este texto foi deletado</del></p> <!--Função "<del></del>" é semântica-->

        <P>Diz que o texto foi excluído (tipo nos artigos do governo).</P>

        <h2>Texto inserido</h2>

        <p><ins>Este texto foi inserido</ins></p> <!--Função "<ins></ins>" é semântica-->

        <p>Diz que o texto foi inserido APÓS</p>

        <h2>Texto sobrescrito</h2>

        <p>Este função é: x<sup>20</sup>+247</p>

        <h2>Texto subrescrito</h2>

        <p>Este função é: H<sub>2</sub>O</p>

# Citações e Códigos - @Curso em Vídeo HTML5 e CSS3

link https://www.youtube.com/watch?v=4ynvsrkamt8&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&index=24

## Outros tipos de formatações

<!DOCTYPE html>

<html lang="pt-br">

<head>

    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Outras Formatações</title>

</head>

<body>

    <h2>Código-fonte</h2>

    <p>O comando <code>document.getElementById('teste')</code> é escrito em liguagem JavaScript</p>

    <h2>Escrevendo formatado</h2>

    <p>Podemos escrever e preservar a formatação com a tag &lt;pre&gt; &lt;/pre&gt;.</p>

    <p>Exemplo:</p>

    <p>

        <pre><!--Usado para manter exatamente a formatação que está descrita no código-->

            <code>

    num= int (input('Digite um número: '))

    if num % 2 == 0

        print(f'O número {num} é PAR')

    else

        print(f'O número {num} é IMPAR')

            </code>

        </pre>

    </p>

    <h2>Citações</h2>

    <p>Como diria o pai de um amigo: <q>o computador é um burro muito rápido</q></p> <!--A tag <q> é usada para citações simples (sem quebras de linhas)-->

    

    <h2>Citações completas</h2>

    <p>Segundo o Developer.mozilla, <blockquote cite="https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals">Depende realmente de você, o quê, exatamente, representam os elementos envolvidos, desde que a hierarquia faça sentido. Você só precisa ter em mente algumas das melhores práticas ao criar tais estruturas:</blockquote> <!--A função <blockquote></blockquote> faz a citação em mais de uma linha além de deslocar para a direita o texto. A função "cite" não cria nada visual para o sistema, o que ela cria é para o navegador saber que essa citação é daquele link-->

    <h2>Abreviações</h2>

    <p>Estou estudando <abbr title="Hyper Text Markup Languange">HTML5</abbr> e <abbr title="Cascading Style Sheets">CSS</abbr>, estou adorando</p>

    </p>

    <p></p>

    </body>

</html>

## Listas

Existem 3 tipos de listas:

* Listas Ordenadas <ol>

* Listas Não-Ordenadas <ul>

* Listas de definição

Colocando colunas nas listas

columns: 2;

Posição do marcador da lista

	List-style-position: inside; (padrão: outside)

## Navegar entre as páginas

Página 1

<!DOCTYPE html>

<html lang="pt-br">

<head>

    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Trabalhando com links</title>

</head>

<body>

    <h1>Usando links externos</h1>

    <p>Você pode acessar o meu <a href="https://dfautogarage.com/" target="_blank" rel="external">site</a>.</p>

    <!--Target é a meta ( Abrir em nova página em branco "_balck" e rel é a referencia (externa))-->

    

    <h2>Usando links internos</h2>

    <p>Esta é a minha <a href="pag2.html" target="_isblank" rel="next">segunda página</a></p>

    <p>Esta é a <a href="noticias/pag3.html" rel="next">terceira página</a></p>

</body>

</html>

Página 2

<!DOCTYPE html>

<html lang="pt-br">

<head>

    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Página</title>

</head>

<body>

    <h1>Esta é a página 2.</h1>

    <p>teste</p>

    <p>Clique <a href="index.html" rel="prev">aqui</a> para voltar à primeira página </p>

    <p>Esta página é um oferecimento de <a href="https://www.hostnet.com.br" target="_blank" rel="nofollow">hostnet</a></p>

</body>

</html>

Página 3

<!DOCTYPE html>

<html lang="pt-br">

<head>

    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Página 3</title>

    <h1>Está é a terceira página</h1><!--Usa-se "../" para voltar uma página-->

    <p>Retornar à <a href="../index.html">página principal</a></p>

</head>

<body>

    

</body>

</html>

## Links para downloads

<!DOCTYPE html>

<html lang="pt-br">

<head>

    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Trabalhando com links</title>

</head>

<body>

    <h1>Usando links externos</h1>

    <p>Você pode acessar o meu <a href="https://dfautogarage.com/" target="_blank" rel="external">site</a>.</p>

    <!--Target é a meta ( Abrir em nova página em branco "_balck" e rel é a referencia (externa))-->

    

    <h2>Usando links internos</h2>

    <p>Esta é a minha <a href="pag2.html" target="_isblank" rel="next">segunda página</a></p>

    <p>Esta é a <a href="noticias/pag3.html" rel="next">terceira página</a></p>

    <h1>Links para download</h1>

    <ol>

        <li><a href="Livro/04 - Primeiros passos HTML.pdf" download="04 - Primeiros passos HTML.pdf" type="application/pdf">Baixar o livro em PDF</a></li>

        <li><a href="#" type="application/pdf">Baixar o livro compactado em zip</a></li>

    </ol>

</body>

</html>

### Fazer download de arquivos do seu site

**Código:**

    <h1>Links para download</h1>

    <ol>

        <li><a href="Livro/04 - Primeiros passos HTML.pdf" download="04 - Primeiros passos HTML.pdf" type="application/pdf">Baixar o livro em PDF</a></li>

        <li><a href="#" type="application/pdf">Baixar o livro compactado em zip</a></li>

    </ol>

Saída:

![image alt text](image_3.png)

## Adicionar vídeos

<!DOCTYPE html>

<html lang="pt-br">

<head>

    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Document</title>

</head>

<body>

    <h1>Inserindo vídeos hospedados localmente</h1>

    <p>Este vídeo está hospedado no meu próprio servidor</p>

    <video controls poster="imagens/img_p.png" width="500">

        <source src="/midia/Kart.mp4" type="video/mp4">

    </video>

</body>

</html>

### Incorporar vídeos de terceiros

    <h1>Inserindo vídeos de terceiros</h1>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/3hng-hmSv2Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</body>

</html>

	

# Módulo 2

Módulo 2, capítulo 13, aula 03

## Estudo de cores

Círculo cromático 

	Utilizado para escolher a harmonia das cores.

Simetria é muito importante, traz a beleza para as coisas!

![image alt text](image_4.png)

### Cores primárias

![image alt text](image_5.png)

### Cores secundárias

![image alt text](image_6.png)

### Cores terciárias

Cores terciárias estão entre uma cor primária e uma cor secundária. Para escrever o nome da cor, coloca-se primeiro o nome da cor primária e depois o nome da cor secundária

![image alt text](image_7.png)

### Temperaturas de cores

![image alt text](image_8.png)

### Paleta de cores

Paleta é de 3 a 5 cores, mas o recomendado são 4 cores!

	Para um cliente, vamos usar principalmente as cor primária da logo.

### Cores complementares

É a cor exatamente oposta no ciclo cromática.

![image alt text](image_9.png)

### Cores análogas

![image alt text](image_10.png)

	Escolha uma cor e as duas imediatamente ao lado direito e esquerdo.

### Cores análogas e uma complementar

![image alt text](image_11.png)

Técnica utilizada para criar uma paleta, pega-se as cores análogas e uma complementar.

### Cores Análogas Relacionadas

![image alt text](image_12.png)

Pega-se duas cores análogas, pula-se uma cor e pega a outra conforme imagem acima, isso pode acontecer para qualquer lado.

### Cores intercaladas

Pega-se uma e pula a outra

![image alt text](image_13.png)

### Cores triádicas

Pega-se uma, pula-se 3:

![image alt text](image_14.png)

### Cores tetrádicas

![image alt text](image_15.png)

### Monocromia (degradê)

Escolha uma cor e depois altere a saturação e a luminosidade (Utilizar o HSL) para isso.

![image alt text](image_16.png)

## Ferramentas para design

### Adobe Colors

	[https://color.adobe.com/pt/create/color-wheel](https://color.adobe.com/pt/create/color-wheel)

### Palleton

[https://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF](https://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF)

### Coolors

	[https://coolors.co/](https://coolors.co/)

## Funções em CSS

Módulo 2 capítulo 13 aula 7

### background-color

Exemplo: Background-color: White;

Altera o fundo do elemento/página

### border-radius

Exemplo: Border-radius: 10px

Arredonda a borda de um objeto o valor pode ser dado em pixel (px) ou em porcentagem.

### box-shadow

Exemplo: Box-shadow: 5px 10px 15px black;

Coloca uma borda no objeto argumentos ( deslocamento direita (5px); deslocamento para baixo (10px) e espalhamento (15 px) e cor)

### width

	Exemplo: width: 600px;

	Largura do objeto.

### Padding

	Exemplo: padding: 10px;

	Acolchoamento, distancia do objeto interno para o objeto externo

### Margin

	Exemplo: margin: auto;

Define a margem do objeto, pode ter argumentos para cima (margin-top), para baixo (margin-botton), para direita (margin-right) e para a esquerda (margin-left), pode ser dada em pixels ou automaticamente (auto)

### text-align

Exemplo: text-align: justify

Faz o alinhamento do texto, pode ser para os lados (left, right), centralizado (center) ou justificado (justify)

### text-shadow

Exemplo: text-shadow: 1px 2px 3px black;

Coloca uma borda no texto argumentos (deslocamento direita (1px); deslocamento para baixo (2px) e espalhamento (3 px) e cor)

## Tipografia

Módulo 2 capítulo 14 aula 1

### Anatomia do tipo

![image alt text](image_17.png)

#### Componentes geométricos

![image alt text](image_18.png)

#### Componentes anatômicos

![image alt text](image_19.png)

### Categorias das fontes

![image alt text](image_20.png)

### Font-family

Exemplo:

h1, h2{

    font-family: 'Times New Roman', Times, serif;

}

	Usar sempre a família da fonte e terminar com "sans-serif", “serif” ou “monospace”

### Tamanho das fontes

    /* Medidas absolutas

    cm -> Centímetros

    mm -> Milímetro

    in -> Polegada

    px -> Pixel

    pt -> Ponto

    pc -> Paica

 

    Medidas Relativas

    em -> Medida relativa ao tamanho atual da fonte (relativa ao M maiúculo da fonte)  

    ex -> Medida relativa a altura x de uma fonte

    rem -> Medida relativa ao root (altura que está configurada no Body)

    vw -> ViewWidth -> Porcentagem da Viewport (Relativo a largura da ViewPort -> altura da tela do dispositivo que está sendo usado)

    vh -> ViewHeight -> Porcentagem da ViewHeight (Relativo a altura da ViewPort -> altura da tela do dispositivo que está sendo usado)

    % -> Porcentagem da ViewPort*/

Recomendação: Usar sempre px e o em. 1em = 16px/

### font-weight

Exemplo:     font-weight: Lighter;

Argumentos possíveis: Lighter, Normal, Bold, Bolder ou numéricos que variam de 100 – 900 de 100 em 100

É o peso da fonte, se ela é "fina" ou “grossa”

### font-style

	Exemplo:     font-style: italic

	Argumentos possíveis: normal, italic;

Diz se a fonte é normal ou itálico

### text-decoration

	Exemplo:     text-decoration: underline;

Argumetos possíveis: underline, overline, line-through, underline [color]	

### Font -> shorthand

	Exemplo:     font: italic bolder 3em 'Work Sans', sans-serif;

	Argumentos: font-style –> font weight –> font size –> font Family

	Neste caso substituiu o seguinte código:

    font-style: italic;

    font-weight: Lighter;

    font-size: 3em;

    font-family: 'work sans', sans-serif;

## Importando fontes externas

Para importar, acesse o site [https://fonts.google.com/](https://fonts.google.com/) e escolha a fonte, depois selecione no ícone de + as configurações desejadas e por fim clique em ![image alt text](image_21.png) e depois em "importe". Copie o código entre as tags <style></style> e cole no CSS.

Exemplo: Importando a fonte roboto

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap'); /*font-family: 'Roboto', sans-serif;*/

body{

    font: normal 2em 'Roboto', sans-serif; /*isso é uma shorthand*/

}

## Importando Fontes Baixadas

Baixar a fonte desejada e colocar na pasta. 

Utilizar a regra @font-face no início do CSS

@font-face {

    font-family: 'alice';

    src: url(font/Alice\ in\ Wonderland.ttf) format('truetype');

}

@font-face {

    font-family: 'cute';

    src: url(font/Cute\ And\ Active.otf) format('opentype');

}

/*Tipos de formatos

    -   opentype (otf)

    -   truetype (ttf)

    :   embedded-opentypr

    -   truetype-aat(Apple Advanced Typography)

    -   SGV

*/

h1 {

    font-family: 'alice', 'cute';

}

## Descobrir a fonte de um site

Extensão font ninja – Sites escritos (HTML)

Para extrair fontes de imagens – whatfontis.com

## Alinhamentos de fontes com CSS

Text-align

	Exemplo: 

	h1 {

    text-align: center;

    

}

	Argumentos possíveis: center, left, right, justify;

Text-indent;

	Exemplo: text-indent

p{

    text-indent: 6em;

OU

    text-indent: 60px;

}

## ID e # em HTML e CSS

Colocar dentro do parágrafo (<p>) h1 ou outro elemento o (id="”) e em CSS pegar o parágrafo e por #

Em HTML fica:

    <h2 id="princial">Título 3 </h2>

    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iure at totam quasi dolore, ab doloremque eaque aliquam omnis? Eveniet unde iusto at consequatur, neque rem et doloremque quas eum quos!</p>

Em CSS fica:

h1#principal{

    text-align: right;

    color: red;

}

/*

    Em HTML id=""   -> Em CSS é #

    EM HTML class=""-> Em CSS é . (ponto)

    */

## class em HTML e CSS

De forma semelhante ao "id", ele funciona para estilizar uma classe.

Exemplo:

Em HTML

    <h2 class="princial">Título 3 </h2>

    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iure at totam quasi dolore, ab doloremque eaque aliquam omnis? Eveniet unde iusto at consequatur, neque rem et doloremque quas eum quos!</p>

Em CSS

.principal{

    text-align: justify;

    color: white;

    background-color: black;

}

Saída

![image alt text](image_22.png)

## Pneudo-Class em HTML

/*: = Pneudo-class é indicado por dois pontos (":")*/

Uma pseudo-classe está relacionada com o estado da classe. Por exemplo, se ela está marcada, se está vazia e etc

Um exemplo é o hover, que é uma configuração que significa "quando o mouse estiver em cima do elemento, faça"

## Pneudo-element em HTML

	Um pseudo-elemento mexe no conteúdo do elemento (no texto periférico). Por exemplo, quero colocar um link de download que tenha um indicativo do formato na frente, pode-se fazer da seguinte forma

<table>
  <tr>
    <td>HTML</td>
    <td>CSS</td>
  </tr>
  <tr>
    <td><!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personalizando links</title>
</head>
<body>
    <h1>Personalizando links</h1>
    <ul>
        <li><a href="https://gustavoguanabara.github.io" class="pdf">Repositório GitHub</a></li>
        <li><a href="https://youtube.com/cursemvideo" class="video">Canal do Youtube</a></li>
        <li><a href="https://www.cursoemvideo.com" class="audio">Site do CursoemVídeo</a></li>
    </ul>

</body>
</html>
</td>
    <td>body{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

a{
    color: black;
    text-decoration: none;
}

a:hover{
    color: blue;
    text-decoration: none;
}

a:active{
    color: red;
}

.audio::after {
    content: '.mp3';
    color: gray;
}

.video::after{
    content: '.mp4';
    color: gray;
}

.pdf::after{
    content: '.pdf';
    color: gray;
}
</td>
  </tr>
</table>


Saída

![image alt text](image_23.png)

## > Children

É basicamente uma tag dentro da outra, por exemplo

    <div class="escondido" >Passe o Mouse aqui<p>Achou abestado</p></h1>

No CSS ficaria

div > p{

    color: white;

}

Picture

Consegue alterar a imagem/foto de acordo com o tamanho da tela. Utiliza-se o seguinte código:

## Modelo de caixas – Capítulo 16

Caso tenha dúvida, pesquisar por HTML e CSS box-model

Aninhamento -> Caixa dentro de caixas

width -> Largura

height -> Altura

![image alt text](image_24.png)

## Border

É a borda do elemento e fica colada na caixa

![image alt text](image_25.png)

## Padding 

É um espaço interno que distanciam a borda e a caixa. Pode ser calculada em qualquer uma das dimensões (top, botton, right and left)

![image alt text](image_26.png)

## Margin

É um espaço externo da borda. Pode ser calculada em qualquer uma das dimensões (top, botton, right and left)

![image alt text](image_27.png)

Outline

É um tracejado fora da borda, mas dentro do tracejado do margin. Sua tradução é contorno ou traçado. A borda é dentro do elemento, o traçado (outline) é fora do elemento. 

![image alt text](image_28.png)

Tipos de caixas

<table>
  <tr>
    <td>Box-level</td>
    <td>Inline-level</td>
  </tr>
  <tr>
    <td>Sempre se inicia numa nova linha;

Sempre ocupa a largura total da tela, portanto se o navegador estiver em tela cheia, ocupará toda a tela. Caso esteja em tela pequena, tipo meio a meio, vai ocupar a metade toda. Width sempre é 100%.

Resumo: Ocupa a página toda e todo box-level começa em uma nova linha</td>
    <td>Não pula pra próxima linha;

Não ocupa a largura da página inteira, apenas o necessário para colocar o conteúdo.</td>
  </tr>
  <tr>
    <td>Exemplo de tag
<div> sempre é do tipo box-level</td>
    <td>Exemplo de tag
<span> sempre é do tipo inline-level</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
</table>


## Display: block;

É um elemento do tipo box-level.

## Display: inline-box

É um elemento do tipo inline-level

# Grooping tag

São as tags de agrupamento.

## header

É o cabeçalho

## main

Conteúdo principal

## footer

Rodapé

## Nav

Menu

## article

artigo

## aside

conteúdo perifeférico/relativo ao artigo

## box-shadow

Cria uma sobra na caixa.

No DEVtools dá para acessar passando o mouse em cima dos e pontinhos (em pé) e clicando em:

![image alt text](image_29.png)

Depois basta configurar o seletor como preferir

![image alt text](image_30.png) Dica: Sempre usar a sombra preta e diminuir a transparência.

## Caixas com vértices arredondados

Border-radius

	Arredonda os vértices de uma div

Ordem do shorthand: superior esquerda, superior direita, inferior direita inferior esquerda.

# Módulo 3

## Git e GitHub

Git é uma ferramenta local de versionamento

GitHub é a ferramenta WEB

## Publicar sites no GitHub

Só funciona nas linguagens html, css e JS

Procedimento: Criar o repositório dentro do github desktop, deixar como público e abilitar o github pages.

## Imagem como fundo de página

### 	Função: background-image

	Usado para colocar uma imagem, que pode ser local ou da web, no fundo de uma página. A imagem pode se multiplicar na página diversas vezes, para controlar isso temos as funções 

Background-size: diz o tamanho mda imagem, por exemplo

	Background-size: 100 px 100 px;

## Background-reapet

 A quantidade de vezes que pode repetir, argumentos aceitos: no-reapet(não repete), reapet-x (se repete no eixo X), reapeat-y (repete no eixo Y)

## Configurando a posição de fundo de imagem

Função:	 background-position: 

Argumentos possíveis: 

<table>
  <tr>
    <td>left top </td>
    <td>Center top</td>
    <td>Right top</td>
  </tr>
  <tr>
    <td>left center</td>
    <td>Center center</td>
    <td>Right center</td>
  </tr>
  <tr>
    <td>Left bottom</td>
    <td>Center bottom</td>
    <td>Right bottom</td>
  </tr>
</table>


.bloco#b1{

    background-position: left top;

}

## Background size

	Content: ocupa 100% da vh mas para isso distorce a imagem 

	Cover: cobre 100% da vh e para isso corta a imagem, mas não distorce. Mas se a tela for muito comprida, ele pode repetir a imagem ou deixar a tela em branco.

## Background-attachment

	Faz com que a imagem de fundo fique fixa e o conteúdo role através das tela.

Exemplos:

    background-attachment: fixed; /* A tela fica fixa e o conteudo rola*/

    background-attachment: scroll; /* A tela fica rolando junto com o conteúdo*/

## shorthand background

/*

Shorthand background    

    color-> image -> postion -> [size] -> attachment    

*/

## Alinhando divs

<table>
  <tr>
    <td><!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style7.css">
    <title>alinhamento vertical</title>
</head>
<body>
    <section class="container">
        <article class="conteudo">


        </article>
    </section>
</body>
</html>
</td>
    <td>.container{
    width: 95%vh;
    height: 500px;
    background-color: purple;
    position: relative;
    background-image: url(imagens/target001.png);
    background-size: 100% 100%;
}

.conteudo{
    width: 400px;
    height: 200px;
    background-color: rgba(255, 255, 0, 0.44);
    position: absolute;
    background-size: 100% 100%;
    background-image: url(imagens/target001.png);
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}
</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
</table>


Saída:

Letras maiúsculas

	Temos duas formas de fazer isso, a primeira é com text-transform: uppercase e a segunda é com font-variant: smallcase.

	 text-transform: uppercase

		Todas as letras iguais em maiúsculo;

![image alt text](image_31.png)

	 Font-variant: smallcase;

		Todas as letras em maiúsculo mas as inciais maiores;

![image alt text](image_32.png)

# Módulo 4

## Iframe

	Inline-frame (frame em linha)


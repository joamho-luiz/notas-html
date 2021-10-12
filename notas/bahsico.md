# Características da Linguagem

## Nomenclaturas

**Nome de arquivos** 

* tudo minusculo
* `-` por &nbsp; ` `

**Class, Id e Name**

* Tudo em minusculo
* Espaço apenas para separar classes. (`class="classe1 classe2 classe3"`)
* nome-do-objeto__atributo--valor

## Arquitetura do projeto  

\> css  
\> imagens  
\> js  

\> Index.html

## Comentários

`<!-- comentário -->`

# Estruturas 

## Estrutura da página

<img src="../mais/imagens/divisamho.gif">

Também há a \<div>

## Estrutura da tag

```html
<tag atributo="valor"> conteúdo	</tag>

<tag/>
```

## Tipos de tags/elements

### Block-level Elements

```html
<address>
<article>
<aside>
<blockquote>
<canvas>
<dd>
<div>
<dl>
<dt>
<fieldset>
<figcaption>
<figure>
<footer>
<form>
<h1>-<h6>
<header>
<hr>
<li>
<main>
<nav>
<noscript>
<ol>
<p>
<pre>
<section>
<table>
<tfoot>
<ul>
<video>
```

### Inline Elements

As demais tags.

<br/>

# EMMET

* `div>h1`
```html
<div>
    <h1></h1>
</div>
```

* `p*3`
```html
<p></p>
<p></p>
<p></p>
```

* `h1+h2`
```html
<h1></h1>
<h2></h2>
```

* `()`  
~ agrupar elementos e famílias.

* `p#identificador` ~ div por padrão
```html
<p id="identificador"></p>
```

* `h1.classe.outra-classe`
```html
<h1 class="classe outra-classe"></h1>
```

* `lorem`
```html
Lorem ipsum, dolor sit amet consectetur adipisicing elit. Non optio veritatis earum rerum vero magni voluptatem ad laborum voluptatum eveniet delectus dicta cum perferendis voluptatibus consequatur nihil, recusandae aut suscipit?
```

* `a[href="#"]`
```html
<a href="#"></a>
```

* `li.item$*3`
```html
<li class="item1"></li>
<li class="item2"></li>
<li class="item3"></li>
```

* `li.item$@4*3`
```html
<li class="item4"></li>
<li class="item5"></li>
<li class="item6"></li>
```

* `p{meu texto}`
```html
<p>meu texto</p>
```

# Deslocados

## Esconder do leitor de tela
<span class="icon icon-key" aria-hidden="true"></span>
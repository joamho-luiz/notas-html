# Conexões

## Referênciar arquivos

CSS:
```html
<link rel="stylesheet" type="text/css" href="_css/estilo.css" />
```

JavaScript: 
```html
<script language="javascript" src="_javascript/funcomhes.js"></script>
```

<br/>

## Usar no HTML

CSS:
```html
<style> css </style>
```

JavaScript:
```html
<script> JvaScript </script>
```

<br/>

## Usar em Tag HTML

Edição CSS:
```html
<h1 style="color:rgb(255, 166, 0);"> oi </h1>
```

Chamar método JavaScript:
```html
<h1 onmousemove="Chamou()"> oi </h1>
```

<br/>

## Outros

Links em nova aba:
```html
<a href="http://glass.google.com" target="_blank">Project Glass</a>
```

Frame (html dentro do html):  
```html
<iframe src="google-glass.html" scrolling="no"></iframe>
<iframe src="demo_iframe.htm" height="200" width="300" title="Iframe Example"></iframe>
```

Um link que aparece em um iframe.
```html
<iframe src="demo_iframe.htm" name="iframe_a" height="300px" width="100%" title="Iframe Example"></iframe>
<p><a href="https://www.w3schools.com" target="iframe_a">W3Schools.com</a></p>
```

## Observação

**href** - (Referência de Hipertexto) faz referencia a outro documento sem se interferir no carregamento do atual.
**src** - (Source) este implica que o documento referenciado deve ser carregado para dar continuidade ao carregamento do documento atual.
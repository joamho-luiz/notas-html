# Imagens

## Adicionar
```html
<img src="_imagen/glass.png" alt="Smiley face" />
```

## Legenda
```html
<figcaption>
    <h3>Google Glass</h3>
    <p>Uma nova maneira de ver o mundo.</p>
</figcaption>
```

## Grupo de imagens
```html
<figure class="foto-legenda">
    <img/>
    <img/>
    <img/>
</figure>    
```

## Regiões sensíveis a click
```html
<img usemap="#meu-mapa">
<map name="meu-mapa">
    <area shape="rect" coords="179, 202, 270, 260" href="google-glass.html#tela" target="janela" />
    <area shape="circle" coords="158, 245, 12" href="google-glass.html#camera" target="janela" />
    <area shape="poly" coords="28, 145, 83, 216, 83, 251, 28, 169" href="google-glass.html#sensores" target="janela"  />
</map>
```
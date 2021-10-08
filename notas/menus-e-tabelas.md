# Menus

## Lista

`<ul>` unordered list (lista não ordenada)  
`<ol>` ordered list  
`<li>` list Item 

```html
<ul type="disc">
    <li><a href="index.html">Home</a></li>
</ul>
```

## Links

`<a>` anchoring
```html
<a href="index.html">Home</a>
```

* target - qual o alvo, _blank (outra aba).

* title - titulo quando o mouse encima.

* href="#id" - vai para o elemento que possui determinado id na própria página.

# Tabelas

`<tr>` table row  
`<td>` table data

```html
<table id="tabla">
    <caption>
        Tabela Técnica do Google Glass <span>Mar/2013</span>
    </caption>

    <tr>
        <td class="ce">Tela</td>
        <td class="cd">Resolução equivalente a tela de 25"</td>
    </tr>

    <tr> <!-- Rowspan Colspan para mesclar células -->
        <td class="ce" rowspan="2" >Câmera</td>
        <td class="cd">5MP para fotos</td>
    </tr>
    
    <tr>
        <td class="cd">720p para vídeos</td>
    </tr>
</table>
```
## Cotador de Seguros Viagens

### Como utilizar?

1. Baixe o arquivo que está dentro da pasta **/dist**  `quotation-travels.js`

2. Coloque o arquivo dentro da sua aplicação

3. No seu **index.html** copie e cole o código a seguir:

```
(function (w,d,s,o,f,js,fjs) {
  w['JS-Widget']=o;w[o] = w[o] || function () { (w[o].q = w[o].q || []).push(arguments) };
  js = d.createElement(s), fjs = d.getElementsByTagName(s)[0];
  js.id = o; js.src = f; js.async = 1; fjs.parentNode.insertBefore(js, fjs);
}(window, document, 'script', 'mw', './quotation-travels.js'));
mw('init', { someConfiguration: 42 });
mw('widgetname', 'Quotation Travels Widget');
```

##### Dica
*Procure colocar o arquivo **quotation-travels.js** no mesmo diretório do index.html.*

##### Ajuda
Dentro da pasta **dist** tem um **index.html** demonstrando como utilizar o widget quotation travels.

## Cotador de Seguros Viagens

### Como utilizar?

1. Faça o download do arquivo `quotation-travels.js` e coloque-o dentro do seu projeto.

3. No seu código **.html** copie e cole o código a seguir:

```
(function (w,d,s,o,f,js,fjs) {
  w['JS-Widget']=o;w[o] = w[o] || function () { (w[o].q = w[o].q || []).push(arguments) };
  js = d.createElement(s), fjs = d.getElementsByTagName(s)[0];
  js.id = o; js.src = f; js.async = 1; fjs.parentNode.insertBefore(js, fjs);
}(window, document, 'script', 'mw', './quotation-travels.js'));
mw('init', { someConfiguration: 42 });
mw('clientid', 'COLOQUE SEU CLIENT ID AQUI');
mw('widgetname', 'Quotation Travels Widget');
```

*` Trocar 'COLOQUE SEU CLIENT ID AQUI' pelo seu clientID fornecido.`*

##### Dica
*Procure colocar o arquivo `quotation-travels.js` no mesmo diretório do `index.html` ou do seu arquivo que deseja importar o Widget de Cotação.*

##### Ajuda
Dentro da pasta **dist** tem um `index.html` demonstrando como utilizar o widget quotation travels.

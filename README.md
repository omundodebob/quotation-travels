## Cotador de Seguros Viagens

### Como utilizar?
 
1. No seu código **.html** copie e cole o código a seguir:

```
(function (w,d,s,o,f,js,fjs) {
  w['JS-Widget']=o;w[o] = w[o] || function () { (w[o].q = w[o].q || []).push(arguments) };
  js = d.createElement(s), fjs = d.getElementsByTagName(s)[0];
  js.id = o; js.src = f; js.async = 1; fjs.parentNode.insertBefore(js, fjs);
}(window, document, 'script', 'mw', 'https://public.ciclic.com.br/templates/widget-quotation/quotation-travels.js'));
mw('init', { someConfiguration: 42 });
mw('clientid', 'COLOQUE SEU CLIENT ID AQUI');
mw('widgetname', 'Quotation Travels Widget');
```

*` Trocar 'COLOQUE SEU CLIENT ID AQUI' pelo seu clientID fornecido.`*

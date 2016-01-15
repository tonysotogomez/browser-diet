---
order: 9
title: Selectors
---

Los selectores es uno de los temas más importantes en el uso de Jquery. Hay muchas diferentes maneras de seleccionar un elemento del DOM, pero eso no significa que tengan el mismo rendimiento, se puede utilizar un elemento usando clases, IDs o métodos como `find()`, `children()`.

Entre todos ellos, seleccionar un ID es el más rápido, porque está basado en una operación nativa del DOM:

```js
$("#foo");
```

*[> Results on JSPerf](http://jsperf.com/browser-diet-jquery-selectors)*

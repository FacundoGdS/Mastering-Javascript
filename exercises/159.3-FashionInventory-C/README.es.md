# `159.3` FashionInventory-C

Esta es una variaci贸n del problema del "Fashion Inventory".

Sin embargo, NO pegues el c贸digo de antes. Afronta cada problema por su cuenta.

Es la misma estructura de datos de inventario que antes.

## 馃摑 Instrucciones

1. Completa la funci贸n `renderInventory` para que retorne el resultado esperado.

2. Retorna una matriz (Lista de listas) las listas contendr谩n los datos del zapato que incluya el nombre `black` en 茅l, con su repectivo precio. En el siguiente orden:

```js
[
  [brandName, shoeModel, price],
  [brandName, shoeModel, price],
  ...
]
```

## Ejemplo de entrada:

```js
var inventory = [
  {
    name: 'Brunello Cucinelli',
    shoes: [
      {name: 'tasselled black low-top lace-up', price: 1000},
      {name: 'tasselled green low-top lace-up', price: 1100},
      {name: 'plain beige suede moccasin', price: 950},
      {name: 'plain olive suede moccasin', price: 1050}
    ]
  },
  {
    name: 'Gucci',
    shoes: [
      {name: 'red leather laced sneakers', price: 800},
      {name: 'black leather laced sneakers', price: 900}
    ]
  }
];
```
[comment]: <Ahora encuentra todos los zapatos negro ( con el name `black`). Es el mismo resultado que la parte 1, pero se filtr贸 solo a los nombres de zapatos que contienen "negro" en ellos.>
 
## Ejemplo de Salida:

```Js
[
   [Brunello Cucinelli, tasselled black low-top lace-up,1000],
   [Gucci, black leather laced sneakers,900]
]
```

## 馃挕 Hint:

+ Si no hay ning煤n zapato que contenga `black` en su nombre, la funci贸n deber铆a devolver un array vac铆o `[]`.

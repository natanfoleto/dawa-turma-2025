## margin

* O padding é o preenchimento interno da caixa.

Podemos dividir o margin em 4 valores:

- padding-top | padding-right | padding-bottom | padding-left
- values: <length> | <percentage> | auto

* Geralmente usamos uma forma abreviada (shorthand) para escrever o padding. 
* Esse formato segue o sentido horário iniciando pelo top, seguindo para right, bottom e left.

```css
div {
  /* Shorthand */

  padding: 12px 16px 10px 4px; 
  /* TOP = 12px | RIGHT = 16px | BOTTOM = 10px | LEFT = 4px */
  
  padding: 12px 16px 0; 
  /* TOP = 12px | RIGHT = 16px | BOTTOM = 0px | LEFT = 16px */
  
  padding: 8px 16px; 
  /* TOP = 8px | RIGHT = 16px | BOTTOM = 8px | LEFT = 16px */
  
  padding: 8px; 
  /* TOP = 8px | RIGHT = 8px | BOTTOM = 8px | LEFT = 8px */
}
```

O padding pode ter valores (values) de comprimento (px, em, rem) ou de porcentagem (%)

**Padding poderá causar diferença na largura de um elemento**

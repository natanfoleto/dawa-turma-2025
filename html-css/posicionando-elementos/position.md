# Posicionamentos

Controlar onde, na página, o elemento irá ficar,
alterando o fluxo normal dos elementos.

- Name: position
- Value: static|relative|absolute|fixed

## static

  - Por padrão os elementos herdam esse posicionamento

## relative

  - Ativando esse position, conseguimos usar as seguintes propriedades
    - top
    - right
    - bottom
    - left
    - z-index

## absolute

  - O absolute faz com que também possamos usar as propriedades
    - top
    - right
    - bottom
    - left
    - z-index

  - O elemento tem o seu espaço eliminado
  - Uma segunda camada é criada, e o elemento é inserido nela
  - O elemento fica relativo á página
  - Caso setarmos o elemento pai desse elemento como relative,
    ele fica relativo ao elemento pai

## Fixed

  - Mesma ideia do absolute, cria-se um novo contexto
  - É setado no novo contexto, mas com uma ideia diferente
  - O elemento fica fixo na página
  - Podemos usar as propriedades
    - top
    - right
    - bottom
    - left
    - z-index

## Element Stacking ( z-index )

  - Ideia de empilhamento
  - Temos o eixo X que é referente a posição horizontal
  - Temos o eixo Y que é referente a posição vertical
  - E temos o Z que é referente as camadas

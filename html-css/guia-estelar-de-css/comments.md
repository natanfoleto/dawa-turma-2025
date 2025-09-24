# Comentários

* Não irá afetar o seu código
* Ajuda a lembrar blocos de códigos
* Deixa dicas para leitura
* Ajuda outros a entenderem
* Nunca esqueça de fechar um comentário aberto

Comentários começam com `/*` e termina com `*/`

```css

/* Básico */
/* --------------------------------------- */

body {
  font: 1rem Helvetica, Arial, sans-serif;
  padding: 1em;
  margin: 0 auto;
  max-width: 33em;
}

@media (min-width: 70em) {
  /* Comentário explicando essa função */

  body {
    font-size: 130%
  }
}
```

* Você poderá usar comentários pra desabilitar partes do seu código

```css

/* .special {
  color: red;
} */

p {
  color: blue;
}

```
# ``grid-column``

- Posiciona o item na coluna desejada.

## ``1 / 3``

- Posiciona o item da linha 1 colunas dispostas na tela até a linha 3 da coluna dispostas na tela.

## ``1 / -1``

- Posiciona o item da linha 1 colunas dispostas na tela até a última coluna dispostas na tela.

## ``span 2``

- Expandir por 2 colunas, neste caso ele niciará na linha 1 da coluna 1 até alinha 4 da coluna 2.

---

## ``align-items e justify-items``

### ``align-items: start | center | end | stretch``

- Alinha os items na horizontal.

### ``justify-items: start | center | end | stretch``

- Alinha os items na vertical.

### ``place-items: align justify``

- Atalho para align-items e justify-items

---

## ``align-self e justify-self``

### ``align-self: start | center | end | stretch``

- Alinha o item na horizontal.

### ``justify-self: start | center | end | stretch``

- Alinha o item na vertical.

### ``place-self: align justify``

- Atalho para align-self e justify-self

---

## ``grid-template-rows``

### ``grid-template-rows: 100px auto;``

- Define o tamanho das linhas.

### ``grid-auto-rows:``

- Linhas são adicionadas automaticamente com o valor de auto.

### ``grid-row: 2``

- Define a linha do item, funciona da mesma forma que o grid-column.

---

## ``Evitando linhas``

- Será mais comum manipularmos colunas do que linhas. Podemos evitar a complexidade do posicionamento em linhas com a reestruturação do HTML.
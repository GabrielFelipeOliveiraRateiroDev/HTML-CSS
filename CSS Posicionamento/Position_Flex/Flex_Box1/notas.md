# Flex Box

## ``display:flex;``

- Os filhos passam a ter um tamanho flexível e ficam um ao lado do outro.

## ``flex-wrap: wrap;``

- Caso não caiba todos os elementos em uma mesma linha, quebre para a próxima.

## ``gap``

- Define uma distância entre os elementos.

---

## Align e Justify

- O Align e Justify funcionam da mesma forma que no CSS Grid Layout. Lembre-se que essas propriedades só funcionam se existir espaço entre os elementos.

## Flex 

### ``flex-grow: 1;``

- Se esse elemento deve crescer para ocupar o espaço vazio. O ``0`` impede o crescimento, valores maiores que ``0`` funcionam como a unidade ``fr`` do css grid.

### ``flex-basis: 200px;``

- Valor inicial antes de distribuir o espaço em branco.

### ``flex-shrink: 0;``

- Caso exista um valor de base, o flex-shrink irá determinar se esse valor pode ser reduzido ou não. ``0`` significa que ele não pode ser reduzido.

### ``flex: 1;``

- Atalho para ``flex-grow: 1;`` ``flex-shrink: 1;`` e ``flex-basis: 0;``

---

## flex vs grid

- Use ambos no seu layout, eles resolvem problemas diferentes. O grid te dá controle em todos os eixos e o flexbox apenas no total de itens por linha.
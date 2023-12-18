# Unidades

## Rem

> Unidade relativa ao tamanho da fonte do elemento raiz ``HTML``. Na maioria dos Browsers a configução padrão de ``1rem = 16px``.

---

#### CSS

![alt text](assets/imgs/CSS_rem.png)

---

#### Resultado

![alt text](assets/imgs/resultado_rem.png)

---

## Em 

> ``em`` é uma unidade relativa ao tamanho da fonte do ``elemento pai``.

---

#### CSS

![alt text](assets/imgs/CSS_em.png)

---

#### Resultado

![alt text](assets/imgs/resultado_em.png)

---

## vh e vw

> ``vh`` representa o tamanho da altura da tela visível (viewport height) e ``vw`` da largura (viewport width). ``100vw = 100% da tela.``.

### Observações

> Antes do vh só existia a porcentagem. A porcentagem é problemática para definir o height, pois: ``height: 100%;`` significa 100% da altura do pai. A altura do pai sempre é definida pelo tamanho do conteúdo, então basicamente ``100% de height`` não muda em nada.

**100vh será 100% da altura da tela, independente da quantidade de conteúdo.**

---

#### CSS

![alt text](assets/imgs/CSS_vh_vw.png)

---

#### Resultado

![alt text](assets/imgs/resultado_vh_vw.png)

---

## Calc

> ``calc()`` é uma função de css que retorna um valor com base no cálculo efetuado entre os ``()``. Podemos combinar unidades.

### calc(100vw / 3)

- Representa 1/3 da tela.

### calc(100% - 20px)

- Representa 20px de 100%.

---

#### CSS

![alt text](assets/imgs/CSS_calc.png)

---

#### Resultado

![alt text](assets/imgs/Resultado_calc.png)

---

## Outras Unidades

> Existem outras unidades, confira no link abaixo:

[Documentação](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units)

---

### Referências / Autoria

- Refrência do [Curso da Origamid](https://www.origamid.com/), modificado e exemplicação e estruração [Gabriel-Dev](@GabrielFelipeOliveiraRateiroDev).
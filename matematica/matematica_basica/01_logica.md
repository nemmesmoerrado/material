(logica-e-demonstracoes)=
# Lógica e demonstrações

(simbolos-logicos)=
## Símbolos lógicos

```{index} Símbolos lógicos
```

As origens dos símbolos lógicos vêm das primeiras tentativas de criar uma linguagem clara para expressar afirmações lógicas. As linguagens cotidianas não são adequadas para isso, pois seu uso pode facilmente levar a ambiguidades e paradoxos. Isso também ocorre na matemática, de modo que a matemática geral foi influenciada por essa linguagem e incorporou parte dela. O uso de símbolos lógicos é mais difundido em áreas da matemática onde há necessidade de uma linguagem precisa, como na teoria dos conjuntos (que é cheia de paradoxos!).

Abaixo listamos alguns dos símbolos lógicos mais comuns.

```{list-table} Símbolos lógicos comuns
:name: simbolos-logicos-tabela
:header-rows: 1
:widths: 10 20 20 25 25
:align: center

* - Símbolo
  - Nome
  - Lê-se como
  - Exemplo
  - Significado
* - $\forall$
  - quantificação universal
  - para todo, para qualquer, para cada
  - $\forall x \in \mathbb{R}, x^2 \geq 0$
  - Para todo número real $x$, $x^2$ é maior ou igual a $0$
* - $\exists$
  - quantificação existencial
  - existe, existe pelo menos um
  - $\forall n \in \mathbb{N}, \exists x \in \mathbb{R} : \vert{} n - x \vert{} < 1$
  - Para todo número natural $n$, existe um número real $x$ tal que $\vert{} n - x\vert{} < 1$
* - $\exists !$
  - quantificação de unicidade
  - existe um único, existe exatamente um
  - $A \subseteq \mathbb{N} \implies \exists ! m \in A : m \geq n, \forall n \in A$
  - Se $A$ é um subconjunto de $\mathbb{N}$, então existe um único $m \in A$ tal que $m \geq n$, para todo $n \in A$
* - $\lnot$
  - negação
  - não
  - $\lnot (x = y) \iff (x \neq y)$
  - $x = y$ não é verdadeiro se, e somente se, $x \neq y$
* - $\land$
  - conjunção
  - e
  - $((x \leq 1) \land (x \geq 1)) \iff x = 1$
  - $x$ é menor ou igual a $1$ e maior ou igual a $1$ se, e somente se, $x = 1$
* - $\lor$
  - disjunção
  - ou
  - $((x \leq 0) \lor (x \geq 0)) \iff x \in \mathbb{R}$
  - $x \leq 0$ ou $x \geq 0$ se, e somente se, $x$ é um número real
* - $\implies$
  - implicação
  - implica, se... então
  - $n \in \mathbb{N} \implies n \in \mathbb{Z}$
  - Se $n$ é elemento de $\mathbb{N}$, então ele é elemento de $\mathbb{Z}$
* - $\iff$
  - equivalência
  - se, e somente se (sse)
  - ($x$ é primo) $\land (x \bmod 2 = 0) \iff x = 2$
  - $x = 2$ se, e somente se, $x$ é um número primo e $x \bmod 2 = 0$
* - $:$, $\vert{}$, t.q.
  - condição
  - tal que
  - $\forall x \in \mathbb{R} : x > 0, \sqrt{x} > 0$
  - Para todo $x$ elemento de $\mathbb{R}$ tal que $x$ é maior que $0$, $\sqrt{x}$ é maior que $0$
```

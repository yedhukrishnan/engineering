#### Computer Science and Engineering > Theory of Computation

---

### Context Free Languages and Push Down Automata

- Context-free languages are both under **Union** operation
  - If $L_1$ and $L_2$ are CFLs, then $L_1 \cup L_2$ is a CFL
- Context-free languages are closed under **Concatenation** operation
  - If $L_1$ and $L_2$ are CFLs, then $L_1L_2$ is a CFL
- Context-free languages are *not* closed under **Intersection**
  - If $L_1$ and $L_2$ are CFLs, then $L_1 \cap L_2$ *may not* be a CFL
- If G is a CFG and $w$ is a string of length 1 in $L(G)$, then the derivation of $w$ in G, if G is in Chomsky Normal Form will have $2n - 1$ steps
- Context-free languages are closed under **Kleen Star**
  - If $L_1$ is CFL, then $L_1^*$ is a CFL
- $L = \{ a^nb^na^n | n \geq 0 \}$  is *not* a CFL
- Context-free languages are *not* closed under **Compliment**
  - If $L_1$ is a CFL, then $\bar{L_1}$ *may not* be a CFL
  - This *does not* mean that the compliment of a CFL is *never* a CFL
- The **intersection** of a CFL and a Regular Language is a CFL
  - If $L_1$ is a CFL and $L_2$ is Regular, then $L_1 \cap L_2$ is a CFL
- There is *no* algorithm to check if a grammar is ambiguous - It is an **Undecidable Problem**
- **Inherently ambiguous** - A language where it is *not possible* to elimate ambiguity
#### Computer Science and Engineering > Theory of Automation

---

### Turing Machines

- Defined as 7 tuples $(Q, \Sigma, \Gamma, \delta, q_0, b, F)$
  - $Q$ = finite non-empty set of states
  - $\Sigma$ = non-empty set of input symbols which is a subset of $\Gamma$ and $b \notin \Sigma$ 
  - $\Gamma$ is a finite non-empty set of tape symbols
  - $\delta$ is the transition function which maps $(Q \times \Gamma) \rightarrow (Q \times \Gamma \times \{L, R\})$ 
  - $q_0$ = initial state
  - $b$ = blank symbol and $b \in \Gamma$
  - $F$ = set of final sets and $F \subseteq Q$    
- Based on functionality, it works as
  - Language recognizer
  - Transducer
  - Enumerator (Generator)   
- **Recursive Language**
  - A language is recursive if there exists a Turing Machine that accepts every string in the language and rejects every string that is not in the language
  - In both cases, Turing Machine halts
- **Recursively Enumerable Language**
  - A language is recursive if there exists a Turing Machine that accepts every string in the language and rejects every string that is not in the language
  - Turing Machine can go into infinite loop
- Properties of Recursive Languages and Recursively Enumerable Languages
  - Compliment of a recursive language is also a recursive language
  - Compliment of a recursively enumerable language is *need not* be recursively enumerable language
  - Union of two recursive languages is recursive
  - If $L$ is recursively enumerable and $\bar{L}$ is also recursively enumerable, then $L$ is a recursive language
  - Recursive languages are closed under *Union, Intersection, Complimentation and Reversal* operation
- The number of symbols necessary to simulate a TM with $m$ symbols and $n$ states is $4mn+m$ 
- **Universal Turing Machine** 
  - Can simulate the behaviour of any Turing Machine
  - Universal Turing Machine influenced the concept of Computability
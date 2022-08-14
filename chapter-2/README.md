# Chapter 2

This chapter focused on finite automata, along with some binary-based examples and some algebraic examples.

The [FiniteAutomata](./src/FiniteAutomata.derw) file implements a pattern matching engine validates against the features discussed in the chapter:

- Symbols e.g "0101"
- Groups e.g "(101)*"
- Eithers of both symbols and groups e.g "1 + 0", "(1 + 0)*", "(1 + 0)*01"
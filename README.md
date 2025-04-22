## SAT Solving Using _XOR-OR-AND Normal Forms_ (XNFs)

This repository contains source code for XNF-based SAT solvers as described in the PhD thesis:  
> *J.Danner, *_SAT Solving Using XOR-OR-AND Normal Forms and Cryptographic Fault Attacks_*, Universität Passau, 2025.*

##### Tools / Solvers

- **`QANFto2XNF` (Algorithm 3.3):**  
  A conversion algorithm from ANF to 2-XNF, implemented in `anf_to_2xnf` by _B. Andraschko_.

- **`CDXCL-lite` (Algorithm 4.6):**  
  A conflict-driven XNF SAT solver, implemented in the submodule `Xorricane` by _J. Danner_.

- **`Graph2XNFSAT` (Algorithm 5.5):**  
  A graph-based DPLL-style 2-XNF SAT solver, implemented in the submodule `2-Xornado` by _J. Danner_.

##### Benchmark Suites

All random and cryptogrpahic benchmark suites of Chapter 6 are available under the [Releases](../../releases) section.

---

###### Setup

Run `git submodule update --init` to clone all submodules. Instructions to run and build the tools and solvers can be found in their respective submodules.

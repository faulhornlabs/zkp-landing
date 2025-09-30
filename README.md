Zero Knowledge Proofs
---------------------

We do basic research on IOPs and their composability, experiment with code generation for ZKPs, develop basic tools for ZKP systems, like optimized elliptic curve operations; and analyse possible use cases of ZKP.

### Open source projects

Testing:

- [r1cs-solver](https://github.com/faulhornlabs/r1cs-solver) -- soundness testing tool / framework, for R1CS / `circom` circuits

Zikkurat ecosystem for ZK proofs:

- [zikkurat-algebra](https://github.com/faulhornlabs/zikkurat-algebra) -- finite fields, elliptic curves, polynomals etc, in generated C and Haskell
- [zikkurat-groth16](https://github.com/faulhornlabs/zikkurat-groth16) -- `snarkjs` compatible Groth16 prover and verifier in Haskell
- [zikkurat-formats-binary](https://github.com/faulhornlabs/zikkurat-formats-binary) -- handling file formats of the `circom` / `snarkjs` ecosystem

Staged metaprogramming approach for developing custom ZK software:

- [staging-agda](https://github.com/faulhornlabs/staging-agda) -- algebra implementation prototype / PoC / learning device, written in Agda
- [csip](https://github.com/faulhornlabs/csip) -- experimental compiler for a dependently typed language with staging; to be used to develop the next generation of zikkurat algebra backend, custom proof systems, and also circuit frontend DSLs (for R1CS, Plonkish, etc)

Hash functions:

- [hash-circuits](https://github.com/faulhornlabs/hash-circuits) -- various hash functions implemented in `circom` (with reference implementations in Haskell)

### Talks

- [Introduction to zero-knowledge proofs](https://github.com/bkomuves/slides/blob/master/computer_science/zk_proofs_2025.pdf) (2025)
- [Succinct proofs of arbitrary computations (zkVMs)](https://github.com/bkomuves/slides/blob/master/computer_science/zkvm_talk_2024.pdf) (2024)
- [A very brief introduction to zero-knowledge proofs](https://github.com/bkomuves/slides/blob/master/computer_science/bme_zk_talk_2023.pdf) (2023)
- [Introduction to zero-knowledge proof systems](https://github.com/bkomuves/slides/blob/master/computer_science/zk_proofs_intro_2022.pdf) (2022)

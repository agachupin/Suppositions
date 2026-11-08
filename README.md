# Suppositions

**Standard Proof Techniques in Discrete Mathematics and Example Applications**

Alejandro [Esteban] Gachupin
Wake Forest University, 2026

---

## Abstract

This document examines standard proof techniques found in discrete
mathematics. It combines meticulous explanations with example applications
to accessibly define and demonstrate each approach.

## Contents

**1. Existential Statements**

- 1.1 Proof by Construction

**2. Universal Statements**

- 2.1 Proof by Exhaustion
- 2.2 Direct Proof
- 2.3 Proof by Division into Cases
- 2.4 Proof by Contraposition
- 2.5 Proof by Contradiction
- 2.6 Proof by Mathematical Induction
- 2.7 Proof of Subset Containment
- 2.8 Proof of Injectivity
- 2.9 Proof of Surjectivity
- 2.10 Proof of Bijectivity

**3. Example Problems**

- 3.1 Squares of Odd Integers
- 3.2 Distances from a Fixed Point
- 3.3 Lattice Points in Circles
- 3.4 Dot Products of Factorials
- 3.5 Left Inverses of Injections
- 3.6 Intersections of Open Sets

Each technique in Sections 1 and 2 is presented with a description of its
general format, guidance on when it applies, and an annotated example
proof. Section 3 applies these techniques to six problems.

## Repository Structure

```
Suppositions.tex          Main document: preamble, metadata, and structure
Commands.tex              Custom commands, environments, and styling
Subsections/
├── Techniques/
│   ├── Existential/      Techniques for existential statements
│   └── Universal/        Techniques for universal statements
└── Examples/             Example problems and their proofs
```

## Building

The document requires a TeX distribution with LaTeX 2023 or later, such as
TeX Live or MiKTeX. To build it, run:

```sh
latexmk -pdf Suppositions.tex
```

`latexmk` performs the multiple passes needed for the table of contents and
cross-references. Alternatively, run `pdflatex Suppositions.tex` twice.

## Citation

```bibtex
@misc{gachupin2026suppositions,
  author       = {Gachupin, Alejandro Esteban},
  title        = {Suppositions: Standard Proof Techniques in Discrete
                  Mathematics and Example Applications},
  year         = {2026},
  month        = nov,
  howpublished = {\url{https://github.com/agachupin/suppositions}},
  institution  = {Wake Forest University},
  note         = {Unpublished manuscript. Licensed under CC BY-NC-SA 4.0},
  url          = {https://github.com/agachupin/suppositions},
  keywords     = {discrete mathematics, proof techniques},
  abstract     = {This document examines standard proof techniques found in
                  discrete mathematics. It combines meticulous explanations
                  with example applications to accessibly define and
                  demonstrate each approach.}
}
```

## License

This work is licensed under the
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See
[LICENSE.md](LICENSE.md) for the full text.
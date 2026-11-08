<div align="center">

# Suppositions

### Standard Proof Techniques in Discrete Mathematics and Example Applications

**Alejandro [Esteban] Gachupin**<br>
Wake Forest University<br>
2026

[Read the Document](Suppositions.pdf) · [Cite This Work](#citation) · [License](#license)

</div>

---

## Abstract

This document examines standard proof techniques found in discrete
mathematics. It combines meticulous explanations with example applications
to accessibly define and demonstrate each approach.

## Overview

Each proof technique is presented in three parts:

1. **Description:** the logical structure of the technique and a general
   outline of its format.
2. **Applicability:** guidance on the kinds of statements for which the
   technique is suited.
3. **Annotated example:** a complete proof in which each step is labeled
   with the part of the general format it carries out.

The techniques are organized by the logical form of the statement being
proved, existential or universal, and are ordered so that each builds on
those before it. A collection of example problems concludes the document.

## Contents

### 1 Proof Techniques for Existential Statements

- 1.1 Proof by Construction

### 2 Proof Techniques for Universal Statements

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

### 3 Example Problems

- 3.1 Squares of Odd Integers
- 3.2 Distances from a Fixed Point
- 3.3 Lattice Points in Circles
- 3.4 Dot Products of Factorials
- 3.5 Left Inverses of Injections
- 3.6 Intersections of Open Sets

## Status

This document is in active development, and the complete version will be
released on November 23, 2026. The most recent compiled draft is
[Suppositions.pdf](Suppositions.pdf); the complete version will be
published under [Releases](https://github.com/agachupin/suppositions/releases).

## Building from Source

### Requirements

- A TeX distribution with LaTeX 2023 or later, such as
  [TeX Live](https://tug.org/texlive/) or [MiKTeX](https://miktex.org/)
- The following packages, all included in a full installation:
  `amsmath`, `amssymb`, `amsthm`, `geometry`, `hyperref`, `lmodern`,
  `mathtools`, `microtype`, `setspace`, `tcolorbox`, `titlesec`, `tocloft`

### Compilation

```sh
latexmk -pdf Suppositions.tex
```

`latexmk` performs the passes needed to resolve the table of contents and
cross-references. Alternatively, run `pdflatex Suppositions.tex` twice.

## Repository Structure

```
.
├── Suppositions.tex        Main document: preamble, metadata, and structure
├── Commands.tex            Custom commands, environments, and styling
├── Subsections/
│   ├── Techniques/
│   │   ├── Existential/    Techniques for existential statements
│   │   └── Universal/      Techniques for universal statements
│   └── Examples/           Example problems and their proofs
├── CITATION.cff            Citation metadata
├── README.md               This file
└── LICENSE.md              License text
```

## Citation

If you reference this work, please cite it as follows.

**APA (7th edition)**

> Gachupin, A. [E.] (2026). *Suppositions: Standard proof techniques in
> discrete mathematics and example applications* [Unpublished manuscript].
> Wake Forest University. https://github.com/agachupin/suppositions

**MLA (9th edition)**

> Gachupin, Alejandro [Esteban]. *Suppositions: Standard Proof Techniques
> in Discrete Mathematics and Example Applications*. 2026. Wake Forest
> University, unpublished manuscript. *GitHub*,
> github.com/agachupin/suppositions.

**Chicago (17th edition, bibliography)**

> Gachupin, Alejandro [Esteban]. "Suppositions: Standard Proof Techniques
> in Discrete Mathematics and Example Applications." Unpublished
> manuscript, Wake Forest University, 2026.
> https://github.com/agachupin/suppositions.

**BibTeX**

```bibtex
@misc{gachupin2026suppositions,
  author       = {Gachupin, Alejandro [Esteban]},
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

**BibLaTeX**

```bibtex
@online{gachupin2026suppositions,
  author       = {Gachupin, Alejandro [Esteban]},
  title        = {Suppositions},
  subtitle     = {Standard Proof Techniques in Discrete Mathematics and
                  Example Applications},
  date         = {2026-11-23},
  organization = {Wake Forest University},
  url          = {https://github.com/agachupin/suppositions},
  urldate      = {2026-11-23},
  langid       = {english},
  note         = {Unpublished manuscript. Licensed under CC BY-NC-SA 4.0},
  keywords     = {discrete mathematics, proof techniques},
  abstract     = {This document examines standard proof techniques found in
                  discrete mathematics. It combines meticulous explanations
                  with example applications to accessibly define and
                  demonstrate each approach.}
}
```

Citation metadata is also provided in [CITATION.cff](CITATION.cff); use
**Cite this repository** in the sidebar to export it in other formats.

## Errata

Corrections and suggestions are welcome. Please submit them as a
[GitHub issue](https://github.com/agachupin/suppositions/issues) or by
email to the author.

## Author

**Alejandro [Esteban] Gachupin**<br>
Wake Forest University<br>
Winston-Salem, North Carolina, United States

| | |
|:--|:--|
| Academic Correspondence | [gachae25@wfu.edu](mailto:gachae25@wfu.edu) |
| General Inquiries | [contact@gachupin.io](mailto:contact@gachupin.io) |
| GitHub | [agachupin](https://github.com/agachupin) |

Please direct questions about the document's content to the academic
address, and other inquiries, including licensing and reuse, to the
general address.

## License

© 2026 Alejandro [Esteban] Gachupin.

This work is licensed under the
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
License](https://creativecommons.org/licenses/by-nc-sa/4.0/). You may share
and adapt it for noncommercial purposes, provided you give appropriate
credit and distribute any adaptations under the same license. See
[LICENSE.md](LICENSE.md) for the full legal text.
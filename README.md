After adding new packages, one needs to update index:
```bash
opam admin make
```
and push corresponding changes to the repo.

`coq-imm` package in this archive depends on `coq-sflib`, `coq-promising-lib`, and `coq-promising` packages,
which are defined in `github.com/snu-sf/promising-coq-opam-archive`.

This repository exists to provide a fully working OCaml development environment inside GitHub Codespaces. My original setup had issues running utop and installing OCaml tooling on Windows, so I created a reproducible devcontainer that includes:

* OCaml

* opam

* dune

* ocaml-lsp-server

* ocamlformat

* utop (fuck you)

* odoc

The .devcontainer configuration ensures that Codespaces automatically builds a complete OCaml toolchain without requiring system‑level installs or sudo. This makes the environment portable, stable, and identical every time it’s opened.

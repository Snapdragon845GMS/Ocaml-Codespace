FROM ocaml/opam:alpine

# Install system build tools needed by OCaml packages
RUN sudo apk add --update make gcc g++ m4 pkgconfig

# Initialize opam environment
RUN opam init -y --disable-sandboxing
RUN eval $(opam env)

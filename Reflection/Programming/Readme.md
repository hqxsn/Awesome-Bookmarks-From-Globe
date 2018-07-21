# Reflection

Here you can find useful references under Reflection topic.

- [Rust or Go](https://codeburst.io/should-i-rust-or-should-i-go-59a298e00ea9) 

  [Andrew Lader](https://codeburst.io/@andrew.lader?source=post_header_lockup) gave good comments on "Should I Rust, or Should I Go?". And he gave the good reflection around useability, performance, scaling aspects, just as he was a good practitioner.

- [Are functional programs easier to verify than imperative programs?](http://semantic-domain.blogspot.co.uk/2018/04/are-functional-programs-easier-to.html)

  [@arntzenius](https://twitter.com/arntzenius) concluded:

  - > This is, incidentally, why reasoning about performance of Haskell code is much harder than reasoning about its functional correctness.

  - > Note that for building a real program, procedural decomposition is not optional.

  - > The safe fragment of Rust is a mix of a) and c) -- it permits you to create aliases of pointers to data only when you don't use them to mutate.
The `trans` crate contains the code to convert from MIR into LLVM IR,
and then from LLVM IR into machine code. In general it contains code
that runs towards the end of the compilation process.

For more information about how trans works, see the [rustc guide].

[rustc guide]: https://rust-lang-nursery.github.io/rustc-guide/trans.html

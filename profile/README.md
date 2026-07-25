# geckolabs

Tools for people who still write assembly and C on purpose.

We build small, fast, single-purpose developer tools. No frameworks,
no bloat, no telemetry. If it doesn't need to allocate, it doesn't
allocate.

Influences: suckless, TinyCC, the Unix philosophy.


## Projects

**Quench (qh)** — zero-overhead build tool for assembly, C, C++,
Objective-C, and Gloria. Wraps NASM, GAS, FASM, GCC, Clang, Zig, and LD
behind one command-line interface.

    github.com/forgezero-cli/Quench

More projects will be listed here as they're released.


## Principles

* No configuration required to get started.
* No intermediate files unless the user asks for them.
* No dependency the user didn't explicitly opt into.
* Every feature has a documented, testable exit code.
* Performance claims ship with reproducible benchmarks.


## Contributing

Each project has its own CONTRIBUTING guide and coding standards under
`docs/`. Read the project's documentation before opening a pull
request. Patches are reviewed for correctness, performance impact, and
adherence to the zero-allocation hot path where applicable.


## Contact

* Issues: open them on the relevant project's repository.
* Author / maintainer: [alexvoste](https://github.com/alexvoste)

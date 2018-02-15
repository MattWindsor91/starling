## Starling

**Starling** is a project to build tools and logics for automated verification of sequentially consistent, low-level concurrent programs.

Work on Starling has been supported, from 2014 to 2018, by an EPSRC Doctoral Training Grant (Matt Windsor).

### People

The following people have worked on Starling:

- [Matt Windsor](https://github.com/MattWindsor91), as part of an upcoming PhD thesis
- [Mike Dodds](https://github.com/septract)
- [Matt Parkinson](https://github.com/mjp41)
- [Ben Simner](https://github.com/bensimner)

### The tool

As part of the Starling project, we have built a tool that takes proof outlines built using a C-style programming language, and verifies the assertions inside them not only for local correctness, but non-interference against parallel invocations of other parts of the program.  Starling can target different backend solvers to tackle different domains: for example, it can use heap reachability solvers to prove properties of shared-heap programs.

The tool is free and open source software, and exists in the following places:

- [Main repository](https://github.com/septract/starling-tool)
- [Matt's development fork](https://github.com/MattWindsor91/starling-tool): tends to have more features than the main repository, but may also be less stable.

### Publications

- Windsor M., Dodds M., Simner B., Parkinson M.J. (2017) [_Starling: Lightweight Concurrency Verification with Views_](https://link.springer.com/chapter/10.1007/978-3-319-63387-9_27). In: Majumdar R., Kunčak V. (eds) Computer Aided Verification. [CAV 2017](http://cavconference.org/2017/). Lecture Notes in Computer Science, vol 10426. Springer, Cham
  - An overview of the _Starling_ theory and tool, and examples of its use.

### Further work

Starling-related projects will appear here as and when they hit general availability.

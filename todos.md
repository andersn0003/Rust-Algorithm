### Todo list

- algorithms visualization

  algorithms / runtime data / anim render engine...,
  independent of each other, connected by gRPC

  algorithms impl as Server
  anim render engine as Client, render algorithms runtime data
  protobuf choose tonic

  The arch of system must contain all kinds of algorithms,
  a kind of algorithm, impl as a plugin, follow spec，amin engine
  can render it.

  data format for Excel & Numbers & plotting libs & csv...

- fix mod/struct/fn doc error to make doc work well, add more docs

- The [Cheat Sheet](https://algs4.cs.princeton.edu/cheatsheet/) is comprehensive,
  rewrite to markdown.

- resort Index section in README.md follow order showed in textbook

- strings algorithms lsd/msd/quick3 based bytes

  refact to support chars, std str.chars() poor performance.
  build one struct, traverse char by index  

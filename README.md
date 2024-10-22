# hptl

High performance trolling language

## Features:

- **blazingly**: fast codegen implemented in rust
- **multi-threaded**: hptl executes your programs on all threads on your
  system, the fastest execution is the resulting execution, all others are
  discarded
- **extremely safe**: after each byte code instruction the states of all
  executing hptl programs are compared
- **inherently async**: all functions are async but block on invocation, this yields great
- **weird types**: for the JavaScript lovers, we explicitly decided to allow for the
  addition, multiplication, division and subtraction of each and all types,
  try it out to see the results

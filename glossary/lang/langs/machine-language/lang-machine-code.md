# machine language

Machine language is how we express direct instructions to the CPU.

It is entirely composed of numbers that represent [opcodes](./comp-arch-cpu-opcodes.md), [memory addresses](./comp-arch-memory-address.md) of code and of values, [offsets](./comp-arch-memory-offset.md) to those addresses, and so on.

Since machine language is just such numbers, it is extremely hard for humans to read.

Therefore, we always write code in a [higher-level](./cog-sci-level-of-abstraction.md) language, then [compile](./source-code-compilation.md) down to machine code.

## Aliases

* machine code
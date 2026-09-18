# python-anti-blackbox

I got sick of Python gaslighting me with high-level dynamic "magic." Every time I try to implement a simple neural net, the math is trivial, but Python decides to hide basic memory semantics behind 442132 layers of dynamic garbage and arbitrary abstractions. 

I refuse to treat the runtime like a magical black box. 

This repo is just about disassembling bytecode, digging through `PyObject` structs, and looking at `ceval.c` until the snake language stops feeling like witchcraft and starts looking like the janky C program it actually is.

### What's in here
- Staring at `dis.dis()` so stack machines make sense again
- Finding out why a simple integer takes up 28 bytes of RAM
- Coping, seething, and reverse-engineering the interpreter (so I can finish Karpathy's playlist)
- Much more...


hopefuly I aint get preoccupied with ts bru 🥀
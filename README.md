# VASM
## Visual Assembly
An interperter which converts .vasm instructions into haxe code.
personal project for fun.

vasm is a basic instruction set to draw on a canvas.
for now im making it have some basic instructions but i will add more when the foundation is ready

### Instructions
- CS(W,H)    |  Set Canvas Size
- CC(0x001)  |  Set Canvas Color
- PP(X,Y)    |  Set Pencil Position
- PC(0x001)  |  Set Pencil Color
- MN(N)      |  Move the pencil N pixels North
- ME(N)      |  Move the pencil N pixels East
- MS(N)      |  Move the pencil N pixels South
- MW(N)      |  Move the pencil N pixels West

### Example
#### Result
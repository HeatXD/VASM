## VASM
# Visual Assembly

A personal project to create a simple interperter which converts .vasm instructions into haxe (Kha) code. for fun.

# Instructions

PP(X,Y)    // Set pencil position at X,Y 
PC(0x0001) // Set pencil color in hex
MN(N)      // Move N pixels North
ME(N)      // Move N pixels East
MS(N)      // Move N pixels South
MW(N)      // Move N pixels West
#test      // Comment skipped by interperter


## future instructions
LP(N>>INS)      // Loops instruction INS N times

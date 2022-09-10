## NumDOOM - Doom for the numworks graphing calculator

One of the two "demo that run on everything" is already on that machine (Bad Apple), why not a second one ?


#### Installation

Put the "numdoom"-folder into apps/ and compile with `make PLATFORM=simulator EPSILON_APPS="doom settings"`.

#### Problems

#### Original nwDoom problem (I will try to fix them. That's my goal)
At the moment the port only works on the simulator. There are a lot errors because of all the IO stuff, which obviously doesn't work on the calculator. But even if we fixed those it probably wouldn't work because of memory restrictions.  
I'm pretty sure it is possible to do, but there is still a lot of optimizing required to actually make it work.  
A huge bottleneck for example is the whole RGBA8888 frame we keep in memory.

#### New problem
None, for now

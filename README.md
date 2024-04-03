# compiler-explorer-local
xxx.local.properties for CE/godbolt

# What is compiler-explorer?

https://github.com/compiler-explorer/compiler-explorer

aka godbolt (named after the author). It is an online compiler tool which can 
be useful for checking the effects of compiler optimaztions, checking the validity
of code snippets, etc. in realtime.

# So ... what are these files?

These are local configucation files useful when running a local instance. It includes
paths to local copies of compilers, libraries and tools.

They were created by:
- copy xxx.default.properties -> xxx.local.properties
- take bits and pieces from xxx.amazon.properties -> xxx.local.properties

# Why do I have a local instance?

- Because I can have a local instance!

One of the goals of compiler-explorer was to never break this feature.

- I have control
- Faster

# What do you need to run a local compiler-explorer?

- node ... i used nvm (nvm use --lts) which uses node 20.xx

and your local compilers (gcc, clang, haskell, python, rust, val).

I am running the local instance on WSL2 on my laptop.

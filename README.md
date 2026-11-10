# hashmap
**hashmap** - simple hash map.

## Description
This is a small library for hashmap. Small API, no bugs
([dbg_alloc](https://github.com/TheCRatTime/dbg_alloc/) shows all blocks're freed)

### Features
- **O(1)** value find (**O(N)** where *N* is total collisions).
- **stb-style**: easy to connect

### Build
Needed:
- C Compiler
- CMake 3.10 and greater
- GNU Make

```bash
cmake -B build
cd build/
make
```

### Authors
TheCRatTime

### License
Project is under Apache 2.0 license

# hello-world

Simple C++ "Hello, World!" example.

Build and run (from workspace root):

```bash
cd "hello-world"
g++ main.cpp -o hello-world
./hello-world
```

Or compile from parent without changing directory:

```bash
g++ "hello-world/main.cpp" -o hello-world
./hello-world
```

Quick alternative (no `-o`):

```bash
g++ main.cpp
./a.out
```

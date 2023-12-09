# Python

```py
print("Hello, World!")
```

**Linux/Mac/Windows**

```shell
$ python3 hello_world.py
```

# C

```c
#include <stdio.h>
int main() {
    printf("Hello, World!");
    return 0;
}
```

**Linux/Mac**

```shell
$ gcc hello_world.c -o hello_world && ./hello_world
```

# C++

```cpp
#include <iostream>
using namespace std;
int main() {
    cout << "Hello, World!";
    return 0;
}
```

**Linux/Mac**

```shell
$ g++ hello_world.c -o hello_world && ./hello_world
```

# Java

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

**Linux/Mac/Windows**

```shell
$ javac Main.java && java Main
```

# Rust

```rust
fn main() {
    println!("Hello, World!");
}
```

**Linux/Mac/Windows**

```shell
$ rustc main.rs && ./main
```

# Scala

```scala
object HelloWorld {
    def main(args: Array[String]): Unit = {
        println("Hello, World!")
    }
}
```

**Linux/Mac/Windows**

```shell
$ scala main.scala
```

# Swift

```swift
print("Hello, World!")
```

**Linux/Mac/Windows**

```shell
$ switf main.scala
```

# Kotlin

```kotlin
fun main() {
    println("Hello, World!")
}
```

**Linux/Mac/Windows**

```shell
$ kotlinc main.kt -include-runtime -d main.jar
$ kotlin -classpath main.jar MainKt
```

# Haskell

```haskell
main = putStrLn "Hello, World!"
```

**Linux/Mac/Windows**

```shell
$ ghc -o Main Main.hs && ./Main
```

# Ruby

```ruby
puts "Hello, World!"
```

**Linux/Mac/Windows**

```shell
$ ruby main.rb
```

# PHP

```php
<?php
echo "Hello, World!";
?>
```

**Linux/Mac/Windows**

```shell
$ php main.php
```

# Go

```go
package main
import "fmt"
func main() {
    fmt.Println("Hello, World!")
}
```

**Linux/Mac/Windows/Windows**

```shell
$ go run main.go
```

# C#

```csharp
using System;
class HelloWorld {
    static void Main() {
        Console.WriteLine("Hello, World!");
    }
}
```

**Linux/Mac/Windows**

```shell
$ dotnet run
```

# Elixir

```elixir
IO.puts "Hello, World!"
```

**Linux/Mac/Windows**

```shell
$ elixir main.exs
```

# Objective-C

```objc
#import <Foundation/Foundation.h>
int main(int argc, const char * argv[]) {
    @autoreleasepool {
        NSLog(@"Hello, World!");
    }
    return 0;
}
```

**Linux/Mac/Windows**

```shell
$ clang -framework Foundation -o myProgram main.m
```

# Ocaml

```ocaml
let () =
    Printf.printf "Hello, World!\n"
```

**Linux/Mac/Windows**

```shell
$ ocaml main.ml
```

# Lua

```lua
print("Hello, World!")
```

**Linux/Mac/Windows**

```shell
$ lua main.lua
```

# Odin

```odin
print("Hello, World!")
```

**Linux/Mac/Windows**

```shell
$ odin main.odin
```

# Nim

```nim
echo "Hello, World!"
```

**Linux/Mac/Windows**

```shell
$ nim c main.nim
```

# Dart

```dart
void main() {
    print("Hello, World!");
}
```

**Linux/Mac/Windows**

```shell
$ dart main.dart
```

# Zig

```zig
const std = @import("std");
pub fn main() void {
    std.debug.print("Hello, World!");
}
```

**Linux/Mac/Windows**

```shell
$ zig run main.zig
```

# x86_64 Assembly

```asm
section .text
global _start
_start:
    mov rax, 1
    mov rdi, 1
    mov rsi, msg
    mov rdx, msg_len
    syscall
    mov rax, 60
    mov rdi, 0
    syscall
section .data
msg: db "Hello, World!", 10
msg_len: equ $-msg
```

**Linux**

```shell
$ nasm -f elf64 -o main.o main.asm
$ ld -o main main.o
$ ./main
```

# JavaScript

```js
console.log("Hello, World!");
```

**Linux/Mac/Windows**

```shell
$ node main.js
```

# TypeScript

```ts
console.log("Hello, World!");
```

**Linux/Mac/Windows**

```shell
$ tsc main.ts
$ node main.js
```

# CoffeeScript

```coffee
puts "Hello, World!"
```

**Linux/Mac/Windows**

```shell
$ coffee main.coffee
```

# Clojure

```clj
(println "Hello, World!")
```

**Linux/Mac/Windows**

```shell
$ clojure main.clj
```

# Common Lisp

```lisp
(format t "Hello, World!~%")
```

**Linux/Mac/Windows**

```shell
$ sbcl --script main.lisp
```

# Cobol

```cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. HelloWorld.

PROCEDURE DIVISION.
    DISPLAY 'Hello, World!'.
    STOP RUN.

```

**Linux/Mac/Windows**

```shell
$ cobc -x -free -o hello hello.cob
```

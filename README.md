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

**Linux/Mac/Windows/Windows**

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

**Linux/Mac/Windows/Windows**

```shell
$ scala main.scala
```

# Swift

```swift
print("Hello, World!")
```

**Linux/Mac/Windows/Windows**

```shell
$ switf main.scala
```

# Kotlin

```kotlin
fun main() {
    println("Hello, World!")
}
```

**Linux/Mac/Windows/Windows**

```shell
$ kotlinc main.kt -include-runtime -d main.jar
$ kotlin -classpath main.jar MainKt
```

# Haskell

```haskell
main = putStrLn "Hello, World!"
```

**Linux/Mac/Windows/Windows**

```shell
$ ghc -o Main Main.hs && ./Main
```

# Ruby

```ruby
puts "Hello, World!"
```

# PHP

```php
<?php
echo "Hello, World!";
?>
```

# Go

```go
package main
func main() {
    fmt.Println("Hello, World!")
}
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

# Elixir

```elixir
IO.puts "Hello, World!"
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

# Ocaml

```ocaml
let () =
    Printf.printf "Hello, World!\n"
```

# Lua

```lua
print("Hello, World!")
```

# Odin

```odin
print("Hello, World!")
```

# Nim

```nim
echo "Hello, World!"
```

# Dart

```dart
void main() {
    print("Hello, World!");
}
```

# Zig

```zig
const std = @import("std");
pub fn main() void {
    std.debug.print("Hello, World!");
}
```

# Assembly

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

# JavaScript

```js
console.log("Hello, World!");
```

# TypeScript

```ts
console.log("Hello, World!");
```

# CoffeeScript

```coffee
puts "Hello, World!"
```

# Clojure

```clj
(println "Hello, World!")
```

# Common Lisp

```lisp
(println "Hello, World!")
```

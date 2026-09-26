# FasWer

### A new compiled programming language built from the ground up.

FasWer is a Java-like programming language designed around **strict typing, object-oriented programming, clean syntax, and high performance**.

The goal of FasWer is simple: provide a familiar programming model while building its own language, compiler, runtime, and development ecosystem from the ground up.

> **FasWer — A new era of coding.**

---

## ✨ Features

* 🧱 Object-oriented programming
* 🔒 Strict static typing
* ⚡ High-performance execution
* 🧠 JIT compilation in development
* 📦 Packages and imports
* 🏗️ Classes, objects, constructors and inheritance
* 🔄 Method overriding with `override`
* 🔐 `public`, `private`, and `static` modifiers
* 🧮 Primitive types
* 📚 Arrays
* 🧵 Strings
* 🛠️ Built-in runtime classes
* ❌ No annotations
* 🧹 Clean Java-like syntax

---

## 💻 Example

```java
package example;

class Main {
    public static void onCreate() {
        Player player = new Player("FasWer");

        player.sayHello();
    }
}

class Player {
    private string name;

    public Player(string name) {
        this.name = name;
    }

    public void sayHello() {
        System.out.println("Hello, " + name + "!");
    }
}
```

FasWer is designed to feel familiar to developers coming from Java while remaining its own language.

---

## 🚀 Performance

Performance is one of the major goals of FasWer.

Performance is actively being improved through runtime optimizations and the development of a JIT compiler.

> Benchmark results depend heavily on CPU, operating system, runtime configuration, and workload. FasWer benchmarks are therefore intended to be compared under the same conditions.

---

## 🧠 Architecture

FasWer is being developed as a complete language ecosystem rather than simply a syntax layer.

```text
FasWer Source
      │
      ▼
   Lexer
      │
      ▼
   Parser
      │
      ▼
     AST
      │
      ▼
   Compiler
      │
      ▼
   Runtime
      │
      ▼
 JIT Compiler
```

The architecture is continuously evolving as performance and language features improve.

---

## 📦 File Extension

FasWer source files use:

```text
.fw
```

Example:

```text
Main.fw
Player.fw
MathUtils.fw
```

Packages correspond to directory structures, keeping projects organized and predictable.

---

## 🛠️ Development Status

FasWer is actively being developed.

### Current

* [x] Lexer
* [x] Parser
* [x] AST
* [x] Static type checking
* [x] Classes
* [x] Objects
* [x] Constructors
* [x] Inheritance
* [x] Method overriding
* [x] Static members
* [x] Packages
* [x] Imports
* [x] Arrays
* [x] Primitive types
* [x] Runtime classes
* [x] Installer
* [x] Performance optimization
* [x] JIT compiler
* [ ] Further runtime optimization
* [ ] Standard library expansion

---

## 🎯 Goals

The long-term goal of FasWer is to become a **fast, practical, general-purpose programming language** with its own:

* Compiler
* Runtime
* JIT compiler
* Standard library
* Package system
* Development tools
* Distribution system

FasWer is not intended to be a Java implementation or a replacement for Java.

It is its **own programming language**, inspired by the parts of Java that make large applications structured and maintainable.

---

## 📊 Benchmarks

FasWer maintains its own benchmark suite to measure improvements over time.

Planned benchmark categories include:

```text
Arithmetic
Loops
Arrays
Method Calls
Object Allocation
Strings
Recursion
Inheritance
Collections
File I/O
Real-world workloads
```

Benchmarks are run against other languages using equivalent implementations and identical hardware conditions whenever possible.

---

## 🗺️ Roadmap

### FasWer 1.0

* [x] Core language
* [x] Object-oriented programming
* [x] Type system
* [x] Packages
* [x] Runtime
* [x] Standard library foundation
* [x] Installer
* [x] JIT compiler
* [x] Performance stabilization
* [x] 1.0 release

### Future

* Expanded standard library
* Better developer tooling
* Debugging tools
* Improved compiler optimizations
* More runtime optimizations
* Cross-platform distribution
* IDE tooling

---

## 📜 License

FasWer is currently **closed-source**.

Source availability and distribution terms may change in future releases.

---

## 👤 Developer

FasWer is developed independently by **Altay**.

The project is built from the ground up with a focus on programming-language design, compiler development, runtime engineering, and performance.

---

# FasWer

**Write it. Compile it. Run it.**

> *A new era of coding.*

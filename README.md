# FasWer

### A modern, Java-like programming language

**FasWer** is a statically typed, object-oriented programming language designed with a familiar Java-like syntax while providing its own interpreter, type system, and runtime.

> **FasWer is currently distributed as a closed-source project.**
> Official releases are provided through this repository.

---

## ✨ Features

* 🧩 **Object-oriented programming**
* 🔒 **Strict static typing**
* 📦 **Packages and imports**
* 🏗️ **Classes, inheritance, and interfaces**
* 🔄 **Method overriding**
* 🧱 **Constructors and nested classes**
* 🧮 **Primitive and reference types**
* 📚 **Arrays**
* ⚙️ **Dedicated interpreter and runtime**
* ❌ **Clear compile-time and runtime errors**
* ☕ **Familiar Java-like syntax**

FasWer is designed to feel familiar to developers coming from Java while remaining an independent programming language.

---

## 📝 Example

```faswer
package example;

public class Main {
    public static void onCreate() {
        Player player = new Player("FasWer");

        player.sayHello();
    }

    public const class Player {
        private string name;

        public Player(string name) {
            this.name = name;
        }

        public void sayHello() {
            System.println("Hello from " + name + "!");
        }
    }
}
```

---

## 🎯 Goals

FasWer aims to provide a programming experience that combines:

* The familiarity of Java-like syntax
* Strong static typing
* Object-oriented programming
* A dedicated interpreter and runtime
* Clear and professional diagnostics
* A growing standard library

The goal is to create a complete programming language and ecosystem while maintaining its own identity.

---

## ⚙️ How FasWer Works

FasWer currently uses an interpreter-based execution model.

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
 Type Checking
     │
     ▼
 Interpreter
     │
     ▼
   Runtime
```

The interpreter evaluates programs and manages the language's runtime environment, objects, classes, methods, and values.

---

## 📦 Releases

Official FasWer releases are published through GitHub Releases.

A release may include:

* FasWer interpreter
* FasWer runtime
* Standard library
* Platform-specific distributions
* Documentation

Check the **Releases** section of this repository for available versions.

---

## 📚 Documentation

Documentation covers:

* Language syntax
* Types
* Classes and objects
* Inheritance
* Interfaces
* Packages
* Arrays
* Standard library
* Installation
* Runtime behavior

---

## 🔒 Source Code

FasWer is a **closed-source project**.

The source code of the language implementation is not publicly available. This repository is primarily used for:

* 📦 Official releases
* 📖 Documentation
* 🐛 Bug reports
* 💬 Community discussions
* 📋 Project information

---

## 🐛 Bug Reports

Found a problem with FasWer?

Please open an **Issue** and include:

1. FasWer version
2. Operating system
3. A minimal example that reproduces the problem
4. The error message or unexpected behavior
5. Any additional information that may help reproduce it

---

## 💬 Discussions

Use GitHub Discussions for:

* Questions
* Ideas
* General FasWer discussions
* Language design discussions
* Community feedback

---

## 🗺️ Roadmap

FasWer is actively evolving.

Planned and ongoing work may include:

* [ ] Interpreter optimizations
* [ ] Expanded standard library
* [ ] Improved diagnostics
* [ ] Better tooling
* [ ] Cross-platform distribution
* [ ] IDE/editor support
* [ ] Further runtime improvements

The roadmap may change as FasWer develops.

---

## 📄 License

FasWer is distributed under its own license.

See the license included with each official release for the terms governing the use and distribution of FasWer.

---

## FasWer

**A new programming language.**

Familiar syntax.
Strong typing.
Its own runtime.

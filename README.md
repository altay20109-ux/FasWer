# FasWer

**FasWer is an independent programming language built to give developers its own syntax, execution environment, and programming experience.** Its main goal is to provide a reliable, accessible, and extensible language for developers and programming enthusiasts to create software, explore programming concepts, and build their own projects.

## Command-Line Interface

FasWer provides a command-line interface for initializing projects, building programs, executing compiled files, and inspecting the language environment.

### Available Commands

| Command | Description |
|---|---|
| `faswer init <path>` | Initializes a new FasWer project at the specified path. |
| `faswer init` | Initializes a FasWer project in the current directory. |
| `faswer build <path>` | Builds a FasWer project at the specified path. |
| `faswer build` | Builds the project in the current directory. |
| `faswer run <file.fwa>` | Runs a compiled FasWer program. |
| `faswer run` | Runs a compiled program using the default CLI behavior. |
| `faswer quick_run <path>` | Runs a compiled FasWer project from the specified path. |
| `faswer quick_run` | Runs a compiled project using the current directory. |
| `faswer --version` | Displays the installed FasWer version. |
| `faswer --platform` | Displays the platform FasWer is running on. |
| `faswer --info` | Displays information about the FasWer language. |
| `faswer --help` | Displays available commands and usage instructions. |

### Getting Started

#### 1. Initialize a project

Create a new FasWer project:

```bash
faswer init MyProject
```

Or initialize the current directory:

```bash
faswer init
```

#### 2. Build the project

Navigate to the initialized project directory and build it:

```bash
cd MyProject
faswer build
```

Alternatively, specify a project path:

```bash
faswer build MyProject
```

#### 3. Run a compiled program

Run a compiled `.fwa` file:

```bash
faswer run path/to/program.fwa
```

#### 4. Quick-run a project

Run a compiled project by specifying its path:

```bash
faswer quick_run MyProject
```

### Environment Information

Display the installed version:

```bash
faswer --version
```

Check the current platform:

```bash
faswer --platform
```

Display information about the language:

```bash
faswer --info
```

### Important Notes

- A project must be initialized before using `build` or `run`.
- `build` compiles a FasWer project.
- `run` executes a compiled `.fwa` file.
- `quick_run` provides an alternative way to execute a compiled project.
- Use `faswer --help` to view available commands and usage instructions.

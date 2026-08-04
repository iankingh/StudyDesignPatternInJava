# StudyDesignPatternInJava

A small Java workspace intended for studying design patterns.

## Current contents

The repository currently contains only the generated starter program:

| Path | Class | What it does |
| --- | --- | --- |
| [`src/App.java`](src/App.java) | `App` | Defines `main` and prints `Hello, World!` |

No design-pattern implementation has been added yet. This index describes the files currently present; it is not a catalogue of Java design patterns.

## Project layout

```text
.
├── .vscode/settings.json
├── README.md
└── src/
    └── App.java
```

The VS Code workspace configuration uses:

- `src/` for Java source files
- `bin/` for compiled classes
- `lib/**/*.jar` for optional referenced libraries

There is currently no `lib/` directory, third-party dependency, test suite, Gradle build, or Maven build.

## Prerequisites

- A JDK with `javac` and `java` available on `PATH`
- Optionally, VS Code with Java support

The repository does not pin a JDK version.

## Compile and run

From the repository root on a POSIX shell:

```bash
mkdir -p bin
javac -d bin src/App.java
java -cp bin App
```

Expected output:

```text
Hello, World!
```

VS Code users can also open the folder and run `App.main`; `.vscode/settings.json` supplies the source, output, and referenced-library paths.

## Adding study examples

Place new Java sources under `src/`. When pattern examples are added, this README should be extended with links to the actual packages/classes and any commands or tests introduced with them.

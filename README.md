# Tadayaya Language

A compiler for the Tadayaya Language written in D. **Works only on Windows for now**

*This is obviously a joke program as it ignores any input and just spits out the smallest possible Windows PE executable I found. Might become a real thing in the future, who knows.*

## How to use

Either compile yourself or download the compiler from the [releases page](https://github.com/CodeMyst/TadayayaLang/releases).

Run it with:

```ayaya
tadayayalang.exe --input yourfile.ayaya --output executablename
```

After that you will get an `executablename.exe` file you can run.

Here's a small video demonstrating how it works: [Tadayaya Language Compiler - Streamable](https://streamable.com/xltrh)

## Sample Tadayaya Program

```ayaya
// SAMPLE TADAYAYA PROGRAM THAT DOES NOTHING

DEAR COMPILER,

PLEASE DON'T COMPILE THIS

LOVE, SALTY
```

## Requesting / Discussing features and reporting bugs

Please feel free to create an issue on the [issues page](https://github.com/CodeMyst/TadayayaLang/issues)

## How to build

Download dmd (or any D compiler, only dmd is tested) and simply build it.

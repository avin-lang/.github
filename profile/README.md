# Avin

A natively compiled, garbage-collected language with a light, indentation-based syntax.

```text
data Shape
    Circle(radius: real)
    Rect(width: real, height: real)

area(shape: Shape) -> real = shape match
    Circle(r) -> 3.14159 * r * r
    Rect(w, h) -> w * h

main() = print([Circle(1.0), Rect(2.0, 3.0)].map(area).sum())
```

## The AVIN philosophy

**AVIN** stands for **Abstraction, Versatility, Intuition and Naturalness**: four principles that
guide the design of the language. Avin is designed to make sophisticated programming techniques
accessible through a simple, expressive and coherent language, in the belief that powerful software
should be possible to write without unnecessary complexity.

- **Abstraction** — *express complex ideas simply.* Classes, traits, generics, higher-order
  functions and pattern matching, in service of programs that are easier to understand.
  Powerful abstractions should simplify code, not complicate it.
- **Versatility** — *one language, many possibilities.* Object-oriented, functional, imperative and
  generic programming coexist, compiled to native code, from command-line utilities to desktop
  software. The language should adapt to the problem, not the other way around.
- **Intuition** — *code should behave as you expect.* A coherent type system, straightforward
  semantics, helpful inference and few surprises. The obvious way to express something should
  usually be the correct way.
- **Naturalness** — *code that flows naturally.* Concise syntax without needless punctuation,
  repetition or boilerplate. Writing code should feel like expressing an idea, not negotiating with
  a compiler.

Abstraction provides expressive power, versatility freedom of approach, intuition predictability,
and naturalness elegance: together, **a powerful, expressive programming language in which
sophisticated ideas can be expressed simply and naturally.**

## Repositories

- [**avin**](https://github.com/avin-lang/avin) — the compiler, runtime, standard library,
  specification and editor support
- [Documentation](https://avin-lang.github.io/avin/)

Avin is young: the specification is the design, and the compiler is being built to it.

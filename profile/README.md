# Orrery

**A diagram language for creating diagrams with a simple text-based DSL, rendered to SVG.**

Write your diagrams as text, get clean SVGs out.

```
diagram sequence;

client: Actor;
app: Component;

client -> app: "Get Request";
client <- app: "Response";
```

## What is Orrery?

Orrery is a domain-specific language and toolchain for describing and rendering software architecture diagrams.

It has a CLI and a library that you can use in your Rust projects.

## Why "Orrery"?

An [orrery](https://en.wikipedia.org/wiki/Orrery) is a mechanical model of the solar system — a clockwork device that makes the invisible relationships and movements of celestial bodies visible and tangible. In the same spirit, Orrery the language makes the structure and interactions within software systems visible through diagrams.

**Orreryworks** is the community and ecosystem around the language — the workshop where the *Orrery* clockwork is built.

## Get Started

```bash
cargo install orrery-cli
orrery input.orr -o output.svg
```

## Links

- 📦 [Main Repository](https://github.com/orreryworks/orrery)
- 📖 [Language Specification](https://github.com/orreryworks/orrery/blob/main/docs/specifications/specification.md)
- 📚 [API Documentation](https://docs.rs/orrery)

## License

Licensed under either of [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0) or [MIT](http://opensource.org/licenses/MIT) at your option.

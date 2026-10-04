# CShell

CShell is an experimental C# shell for .NET.

It explores using C# directly as an interactive shell, with persistent state and an object-oriented approach to interacting with the system.

> [!WARNING]
> CShell is highly experimental and under active development.

## Example

```text
> 2 + 2
4

> "hello".ToUpper()
"HELLO"

> var value = 42

> value * 2
84
```

CShell preserves state between evaluations, allowing C# to be used as a persistent interactive environment.

## License

CShell is licensed under the [MIT License](LICENSE).
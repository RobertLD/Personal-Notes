#software 

### Tools
1. Vscode
2. Devcontainer for F#
	- Extensions:  "Ionide.Ionide-fsharp","ms-dotnettools.csharp


### Starting off

1. Applications are created with a dotnet utility
`dotnet new console -lang F# -o MyFSharpApp`


### Features of F#
1. Variables are by default immutable after creation, to make them mutable you have to clearly state it's mutable
```f#
   let mutable name = "foo"
```
2. Types are inferred if possible, but you can specify one with the following syntax
```f#
let sum:float = 0
```
3. 


This is an example .NET app that has dependencies managed by `PackageReference` in project file. It uses multiple target frameworks.

## Getting started

Prerequisites:

- [.NET](https://dotnet.microsoft.com/download) installed

### Build

```bash
dotnet build
```

### Run the app

Run for target framework net451

```bash
dotnet run --framework net451
```

Run for target framework net5.0

```bash
dotnet run --framework net5.0
```

Run for target framework net472

```bash
dotnet run --framework net472
```

### Restore dependencies

This will create `project.assets.json` in obj folder with a depenedency tree.

```bash
dotnet restore
```

restore from lock file

```bash
dotnet restore --locked-mode
```

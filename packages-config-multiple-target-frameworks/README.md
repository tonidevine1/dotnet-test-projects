This is an example .NET app that has dependencies managed by `packages.config` and uses multiple target frameworks.

## Getting started

Prerequisites:

- [.NET](https://dotnet.microsoft.com/download) installed
- [Nuget CLI](https://docs.microsoft.com/en-us/nuget/install-nuget-client-tools#nugetexe-cli) installed

### Install dependencies

```bash
nuget install -OutputDirectory packages
```

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

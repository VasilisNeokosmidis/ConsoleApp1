# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

C# console application targeting .NET 9.0, created from the default Visual Studio template.

## Build & Run

```bash
# Build
dotnet build ConsoleApp1/ConsoleApp1.csproj

# Run
dotnet run --project ConsoleApp1/ConsoleApp1.csproj

# Build in Release mode
dotnet build ConsoleApp1/ConsoleApp1.csproj -c Release
```

## Project Configuration

- **Target framework:** .NET 9.0
- **Nullable reference types:** enabled
- **Implicit usings:** enabled (no need to explicitly import `System`, `System.Collections.Generic`, etc.)

## Code Structure

- `ConsoleApp1/Program.cs` — entry point using C# top-level statements (no explicit `Main` method or namespace required)
- No test projects exist yet

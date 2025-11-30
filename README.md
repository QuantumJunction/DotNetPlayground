# .NET Playground

A small sandbox for trying out C#, F#, or general .NET snippets, testing ideas, and exploring features. This space is for experimentation, not polished production code.

## Features

- Minimal structure
- Quick experiments with the .NET SDK
- Space for isolated console apps
- Room for standalone .cs, .fs, or .vb files
- Can grow into multi-language .NET tests if needed

## Getting Started
1. Clone the repo
```bash
git clone https://github.com/QuantumJunction/DotNetPlayground.git
cd DotNetPlayground
```

2. Create a new console project
```bash
dotnet new console -o experiments/exp1
```

3. Run the project
```bash
dotnet run --project experiments/exp1
```

## Structure
```bash
/
├── experiments/        # Small .NET console apps or tests
│   ├── exp1/
│   │   └── Program.cs
│   └── exp2/
├── scratch/            # Standalone .cs / .fs / .vb files
├── utils/              # Reusable helpers
├── LICNESE
└── README.md
```

## Usage
Run a project
```bash
dotnet run --project experiments/<project>
```

Run a standalone C# script (optional)
```bash
dotnet script scratch/<file>.cs
```

Run tests (if test projects exist)
```bash
dotnet test
```

## Guidelines

- Keep experiments isolated
- Remove anything that’s just noise
- Put reusable helpers into utils/

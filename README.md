# purescript-hylograph-simulation-core

Kernel-agnostic types and interfaces for force simulation.

## Overview

Defines the core types, interfaces, and orchestration logic shared between different simulation kernels (D3 and WASM). This package has no FFI dependencies and can be used to build custom simulation engines.

## Installation

```bash
spago install hylograph-simulation-core
```

## Modules

- `Hylograph.Simulation.Core.Types` - Core type definitions (Node, Link, Force, etc.)
- `Hylograph.Simulation.Core.Engine` - Engine interface
- `Hylograph.Simulation.Core.Tick` - Tick/update logic

## Part of Hylograph

- **hylograph-simulation-core** - Core types (this package)
- **hylograph-d3-kernel** - D3 physics implementation
- **hylograph-wasm-kernel** - WASM physics implementation
- **hylograph-simulation** - High-level API

## License

MIT

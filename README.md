# dart-optimization

Legacy optimizer plugins and bindings extracted from the DART project. This repository preserves the optional Ipopt, NLopt, pagmo, and SNOPT backends (and their tests/bindings) that were removed from the core `dartsim/dart` repository in DART 7.0.

The code here is provided as-is for reference. It mirrors the structure that existed under `dart/optimizer/` inside DART, including CMake modules and the supporting python bindings/tests.

## Contents

- `dart/optimizer/{ipopt,nlopt,pagmo,snopt}` plugin sources.
- Multi-objective optimization helpers (`GenericMultiObjectiveProblem`, `MultiObjectiveProblem`, `MultiObjectiveSolver`, `Population`).
- CMake find modules for Ipopt, NLopt, pagmo, and SNOPT.
- Legacy integration tests, python bindings, and helper data files needed by the plugins.

## License

The code retains the original BSD-style license from DART (see `LICENSE`).

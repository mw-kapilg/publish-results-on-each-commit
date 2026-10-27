# signal-utils

Small MATLAB utilities for unit conversion and signal smoothing.

- `src/` — library functions
- `tests/` — unit tests (MATLAB unit testing framework)

Run the tests locally from the repository root:

```matlab
addpath("src")
results = runtests("tests")
```

CI runs on GitHub Actions — see `.github/workflows/ci.yml`. Each run publishes:

- a **MATLAB test results** check on the commit/PR (pass/fail counts, failure annotations)
- test and `src/` line-coverage tables on the run's **Summary** page
- the raw JUnit and Cobertura XML as the `matlab-test-and-coverage-reports` artifact

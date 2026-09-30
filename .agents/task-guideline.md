# Task Guideline

## Guideline

When adding/modifying code, try to follow these instructions:

- For each package, follow the convention of existing files first.
- For each file, the order is: types, type methods, helper methods. In each type: public take precedence before private ones.
- If moving files is needed, use the source control move command to retain history.
- When assigning variables into object, try to follow order of field declarations if possible.
- Order of test functions will follow the order of code file.
- Execute tests per package to prevent timeout.

<!-- Project-specific / Guideline -->

## Checklist

Before considering any coding task complete, please verify the following:

- [ ] Whole project is built successfully (see [commands.md](commands.md)).
- [ ] Code files are formatted, passed static analysis (see [commands.md](commands.md)).
- [ ] Changed code files follow project convention (see [coding-conventions.md](coding-conventions.md)).
- [ ] Imports are tidy (see [commands.md](commands.md)).
- [ ] Relevant tests are passing, except the ones documented as known failures.
- [ ] New/changed behavior has test coverage.
- [ ] Changes are scoped to the task, no unrelated refactors bundled in.
- [ ] No unused code, debug prints, or commented-out blocks left behind.

<!-- Project-specific / Checklist -->

## Project-specific

<!-- Project-specific -->

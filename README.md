# Python Problem-Solving Exercises

A compact archive of early Python programs exploring terminal input, loops, digit operations and contest-style problems. The source is kept in three descriptively named files rather than an installable package.

## Files

| File | Focus |
|---|---|
| [ContestProbs](ContestProbs) | Digit-comparison problem: search forward for a number with distinct digits |
| [Number converter](Number%20converter) | An experimental decimal-to-hexadecimal conversion attempt |
| [Qualifying](Qualifying) | Several input/list-processing and counting exercises, including commented alternatives |

## Run an exercise

Use Python 3. The files have no `.py` extension, but Python can execute them by their full filename:

```bash
python ContestProbs
```

Enter the input expected by the chosen program. Inspect the source first: `Qualifying` contains multiple exercise fragments and input stages, rather than a single reusable command-line interface.

## Scope and learning notes

These are learning exercises with assumptions tied to their original problem statements. The digit search assumes four-character decimal inputs; the converter and some counting fragments remain exploratory and should not be treated as general-purpose utilities.

The useful comparison is between the intended algorithm and the actual sequence of operations: how loop conditions change, when state is reset, how numeric input becomes text and where edge cases need explicit handling. No third-party packages are required by the current files.

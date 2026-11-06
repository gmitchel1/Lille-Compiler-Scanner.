# Scanner Phase Corrections — Gracie Mitchell (CSC-4510)

This revision preserves the original starter layout and fixes the scanner defects described in grading feedback. The original author headers remain in place.

## Build / execute

```sh
make clean && make
./compiler program1
./compiler scanner_tests/valid.lille
./compiler scanner_tests/invalid_exponent.lille
./compiler scanner_tests/invalid_empty_string.lille
./compiler scanner_tests/invalid_decimal.lille
```

Expected: valid programs report 0 errors; each invalid fixture reports at least 1 lexical error with position. A scanner only checks lexical tokens, not full program syntax.

## Recording / repository

Record a **screen** demonstration showing `make`, a valid example, and invalid tests. Commit actual edits incrementally, with descriptive commits. Invite GitHub collaborator `Kowsar-HPU`. The ZIP itself does not contain Git commit history or a recording.

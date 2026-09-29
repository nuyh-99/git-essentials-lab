# Run Guide

## Prerequisites

- JDK 17 or later (`java` and `javac` on PATH)
- Python 3.9 or later
- No Maven, Gradle, or IDE is required

## Run the demo

```text
python3 run.py demo

On Windows, py -3 run.py demo works the same way.

What the demo does

The runner compiles the Java sources in src/library/ into a temporary
directory and runs a short scenario: it builds a catalog, borrows and
returns books for a student and a faculty member, applies the loan
period and overdue fee, searches the catalog, and prints a loan receipt.
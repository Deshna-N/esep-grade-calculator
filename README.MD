# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

## Runtime requirements:
Golang 1.24+

## Files to Note:
- grade-calculator/go.mod: Go mod configuration.
- grade-calculator/grade-calculator.go: Implementation of grade calculator
- grade-calculator/grade-calculator_test.go: Unit tests automated for implementation.


## Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```

## Development Notes
This repo also uses conversions for letter grades and lets you add assignments, essays, and/or exams to calculate. 
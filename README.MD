# ESEP Grade Calculator

This project is a grade calculator written in Go. It calculates a student's final grade based on assignments, exams, and essays.

## Requirements

You need Go 1.24.4 or newer installed on your computer.

## Project Files

The main files are located in the `grade-calculator` folder:

- `go.mod` - Contains the Go module information and required version.
- `grade_calculator.go` - Contains the code used to calculate grades.
- `grade_calculator_test.go` - Contains the unit tests for the calculator.

## Getting Started

Clone the repository and open the project folder:

```bash
git clone https://github.com/jontascon/esep-grade-calculator.git
cd esep-grade-calculator/grade-calculator
```

## Running Tests

To run the unit tests:

```bash
go test ./...
```

To see the results of each test:

```bash
go test -v ./...
```

## Code Coverage

To check how much of the code is covered by the tests:

```bash
go test -coverprofile=coverage.txt ./...
```

To see the coverage results:

```bash
go tool cover -func=coverage.txt
```

## Additional Information

The calculator uses three categories: assignments, exams, and essays.

The current weights are:

- Assignments: 50%
- Exams: 35%
- Essays: 15%

The repository currently has six unit tests. All tests pass, and the project has 100% code coverage.

## Resources

- Go documentation: https://go.dev/doc/
- Go testing: https://pkg.go.dev/testing
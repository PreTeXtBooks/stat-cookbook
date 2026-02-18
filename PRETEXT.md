# PreTeXt Version

This directory contains the PreTeXt version of the Probability and Statistics Cookbook.

## Directory Structure

- `source/` - Contains the PreTeXt source files
  - `main.ptx` - Main book file with all chapters
- `publication/` - Contains publication settings
  - `publication.ptx` - Configuration for HTML and PDF output
- `project.ptx` - Project configuration file
- `.github/workflows/` - Contains GitHub Actions workflow for automated builds

## Building the Book

### Prerequisites

Install the PreTeXt CLI:

```bash
pip install pretextbook
```

### Build Commands

Build the HTML version:
```bash
pretext build web
```

View the built HTML:
```bash
pretext view web
```

Build the PDF version (requires LaTeX):
```bash
pretext build print
```

## Structure

The book contains the following chapters:

1. Distribution Overview
2. Probability Theory
3. Random Variables
4. Expectation
5. Variance
6. Inequalities
7. Distribution Relationships
8. Probability and Moment Generating Functions
9. Multivariate Distributions
10. Convergence
11. Statistical Inference
12. Parametric Inference
13. Hypothesis Testing
14. Exponential Family
15. Bayesian Inference
16. Sampling Methods
17. Decision Theory
18. Linear Regression
19. Non-parametric Function Estimation
20. Stochastic Processes
21. Time Series
22. Math

## Deployment

The book is automatically built and deployed to GitHub Pages when changes are pushed to the `main` branch. The deployed version is available at:

https://pretextbooks.github.io/stat-cookbook/

## Development

To add content to a chapter:

1. Open `source/main.ptx`
2. Find the chapter you want to edit (e.g., `<chapter xml:id="ch-probability-theory">`)
3. Add PreTeXt content within the chapter tags
4. Build locally to test: `pretext build web`
5. View the result: `pretext view web`
6. Commit and push your changes

## Resources

- [PreTeXt Guide](https://pretextbook.org/doc/guide/html/)
- [PreTeXt Documentation](https://pretextbook.org/documentation.html)
- [PreTeXt CLI Documentation](https://github.com/PreTeXtBook/pretext-cli)

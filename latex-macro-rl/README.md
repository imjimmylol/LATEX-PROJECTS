# LaTeX Macro RL Project

This project contains a LaTeX document for a research paper titled "Semi-RL Autonomous Macro System: A Hybrid Approach for Reinforcement Learning in Macroeconomics." The document is organized into multiple sections for better maintainability and readability.

## Project Structure

```
latex-macro-rl
├── main.tex
├── sections
│   ├── abstract.tex
│   ├── introduction.tex
│   ├── methodology.tex
│   ├── rl_optimization.tex
│   └── appendix.tex
├── pepadun.bib
└── README.md
```

## File Descriptions

- **main.tex**: The main document file that imports all sections and compiles them into a single document. It includes the preamble, metadata, and commands to include each section.

- **sections/abstract.tex**: Contains the abstract of the paper, defining the abstract environment and including the content of the abstract.

- **sections/introduction.tex**: Contains the introduction section of the paper, detailing the background and motivation for the research.

- **sections/methodology.tex**: Details the research methodology, describing the hybrid framework and the stages of the research process.

- **sections/rl_optimization.tex**: Discusses the RL-based policy optimization, describing the algorithm and the learning objectives.

- **sections/appendix.tex**: Includes additional details, algorithms, and derivations that support the main text.

- **pepadun.bib**: The bibliography file containing references used in the paper.

## Compilation Instructions

To compile the LaTeX document, follow these steps:

1. Ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX).
2. Navigate to the project directory in your terminal.
3. Run the following command to compile the document:

   ```
   pdflatex main.tex
   biber main
   pdflatex main.tex
   pdflatex main.tex
   ```

4. Open `main.pdf` to view the compiled document.

## Dependencies

This project uses the following LaTeX packages:

- `pepadun`: Custom package for formatting.
- `biblatex`: For bibliography management.

Make sure these packages are available in your LaTeX distribution.
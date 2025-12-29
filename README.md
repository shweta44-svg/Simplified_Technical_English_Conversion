## Simplified Technical English Conversion

## Overview

This project develops a Large Language Model (LLM) pipeline to translate Standard English into **Simplified Technical English (STE)**, specifically tailored for the aircraft industry.

It enhances a domain-specific dataset to align with **Aerospace Simplified Technical English (ASTE)** standards, ultimately improving text readability, safety compliance, and efficiency in maintenance documentation.

## What is Simplified Technical English (STE)?

Simplified Technical English (STE), also known as ASD-STE100, is a controlled language specification designed for aerospace and defense documentation. It uses a limited vocabulary, simple grammar rules, and standardized phrasing to reduce ambiguity, improve clarity, and enhance comprehension for non-native English speakers and technical audiences.

## Project Goals

- Build an LLM-based pipeline for automatic conversion of standard technical text to STE.
- Curate and enhance datasets compliant with STE rules for the aerospace domain.
- Improve readability and safety in aircraft maintenance manuals and technical documents.

## Repository Contents

- `Final_Optimal_Code.ipynb`: The main Jupyter Notebook containing the optimized LLM pipeline code, data processing, model fine-tuning/inference, and evaluation.
- `dataset_591.csv`: Primary dataset with 591 examples (likely parallel sentences: Standard English ↔ STE).
- `250.csv`: Additional or subset dataset with 250 examples.
- `ASD-STE100_issue8.pdf`: Official ASD-STE100 Simplified Technical English specification (Issue 8) for reference.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries commonly used for LLM tasks (e.g., transformers, datasets, pandas, torch – install via `pip` as needed)

## Usage

1. Open `Final_Optimal_Code.ipynb` in Jupyter Notebook or Google Colab.
2. Run the cells sequentially to:
   - Load and explore the datasets.
   - Preprocess data according to STE rules.
   - Fine-tune or prompt an LLM for conversion.
   - Test the pipeline on new input text.
3. Customize the model or prompts for your specific aerospace documentation needs.

## Contributing

Contributions are welcome! Feel free to:
- Report issues or suggest improvements.
- Submit pull requests for enhanced models, larger datasets, or better STE rule enforcement.

## License

This project is open-source. (If a specific license applies, add it to the repository.)

## References

- ASD-STE100 Simplified Technical English Specification (included as `ASD-STE100_issue8.pdf`).

For more details, explore the Jupyter Notebook or contact the repository owner.

# Entropy-Based Pre-tokenization for BPE

This project implements entropy-informed pre-tokenization strategies for Chinese text using BPE (Byte Pair Encoding) tokenization. The approach leverages predictive entropies from pretrained transformer models or statistical methods to detect boundary uncertainty and improve tokenization quality.

## Overview

The project focuses on improving tokenization for unsegmented languages like Chinese by using entropy information from transformer models or statistical methods to guide the pre-tokenization process. This helps achieve better alignment with linguistic units and enhances overall tokenization quality.

## Key Features

- **Entropy Calculation**: Computes next-token entropy using transformer models or statistical methods
- **Model Support**: Compatible with both GPT-2 and BERT models for entropy calculation
- **Visualization Tools**: Includes utilities for visualizing entropy distributions along token positions
- **Evaluation Metrics**: Implements precision, recall, and F1 score evaluation against standard BPE tokenization
- **Text Processing**: Provides utilities for text preprocessing and analysis

## Implementation Details

The implementation is evaluated on a subset of the PKU corpus, comparing the performance of entropy-guided pre-tokenization against standard BPE tokenization methods.

## Project Structure

- `entropy_model.ipynb`: Main implementation notebook containing the entropy-based tokenization logic
- Additional files and directories to be added as the project develops

## Requirements

(To be added based on project dependencies)

## Usage

(To be added with implementation details)

## License

(To be added)

## Citation

(To be added if applicable)



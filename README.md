# Information Theory Calculator

## Overview
This project is an **Information Theory Calculator** that provides various entropy and coding computations. It supports multiple encoding algorithms, including Huffman coding, Shannon-Fano, and Gilbert-Moore, and calculates entropy, mutual information, and redundancy.

## Features
- **Entropy Calculation:** Computes Shannon entropy for given symbol probabilities.
- **Huffman Coding:** Generates an optimal prefix code for efficient encoding.
- **Shannon-Fano Coding:** Implements both binary and ternary versions.
- **Gilbert-Moore Coding:** Provides an alternative encoding strategy.
- **Mutual Information Calculation:** Measures the information shared between two random variables.
- **Error Handling:** Ensures valid probability distributions and matrix formats.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/information-theory-calculator.git
   cd information-theory-calculator
   ```
2. Open `index.html` in a web browser (if it's a web-based app), or run the script in a JavaScript environment.

## Usage
1. **Input Data**: Provide a probability distribution or a joint probability matrix.
2. **Select Algorithm**: Choose from entropy, coding methods, or mutual information.
3. **Compute**: Click the button to run calculations.
4. **View Results**: The computed values will be displayed in the UI.

## Example Inputs
```json
{
  "probabilities": {"A": 0.4, "B": 0.3, "C": 0.2, "D": 0.1},
  "matrix": [[0.1, 0.2], [0.3, 0.4]]
}
```

## Future Improvements
- Improve ternary Shannon-Fano algorithm efficiency.
- Enhance UI with a step-by-step breakdown of Huffman coding.
- Add more visual representations for mutual information.

## License
This project is licensed under the MIT License.





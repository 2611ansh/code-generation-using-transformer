# CodeCraft

CodeCraft is a Python project that demonstrates code generation using transformers. It leverages the power of the Transformer architecture to generate Python code snippets based on given prompts or questions.

## Project Structure

The project consists of the following files and directories:

- `code_generation_using_transformers.ipynb`: Jupyter Notebook containing the code implementation and explanation of the code generation using transformers.
- `english_python_data.txt`: Text file containing a dataset of prompts and corresponding Python code solutions.
- `README.md`: This file, providing an overview of the project.

## Getting Started

To run the code and generate Python code snippets, follow these steps:

1. Clone the repository: `git clone https://github.com/2611ansh/code-generation-using-transformer.git`
2. Navigate to the project directory: `cd code-generation-using-transformer`
3. Open the `code_generation_using_transformers.ipynb` file in Jupyter Notebook or any compatible environment.
4. Run the notebook cells step-by-step to execute the code and generate code snippets based on prompts.

## Dependencies

The project requires the following dependencies:

- Python (version 3.6 or above)
- PyTorch (version 1.7.0 or above)
- TorchText (version 0.8.0 or above)
- matplotlib (version 3.3.0 or above)
- spacy (version 3.0.0 or above)
- tqdm (version 4.50.0 or above)
- numpy (version 1.19.0 or above)
- pandas (version 1.1.0 or above)

You can install the required dependencies using `pip`:

```
pip install torch torchtext matplotlib spacy tqdm numpy pandas
```

## Dataset

The project utilizes the `english_python_data.txt` file as the dataset for prompts and corresponding Python code solutions. The dataset is formulated in a manner where every question starts with the '#' symbol, and lines between two consecutive '#' symbols form the solution to the question.

## Usage

The `code_generation_using_transformers.ipynb` notebook provides a step-by-step guide on how to use the code generation functionality. It includes code snippets for reading the dataset, preprocessing the data, training the transformer model, and generating code snippets based on prompts.

## Contributing

Contributions to CodeCraft are welcome! If you have any ideas, improvements, or bug fixes, please open an issue or submit a pull request. Make sure to follow the existing code style and guidelines.

## License

CodeCraft is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for personal or commercial purposes.

## Acknowledgments

This project is inspired by the power of transformers in natural language processing and code generation. Special thanks to the authors and contributors of the libraries and frameworks used in this project.

## Contact

If you have any questions, suggestions, or feedback, feel free to contact the project maintainer at [anshjabalpur@gmail.com].

Happy coding with CodeCraft!

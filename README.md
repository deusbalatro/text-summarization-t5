
# Text Summarization with T5

This Python script demonstrates how to perform text summarization using a pre-trained T5 model from the Hugging Face Transformers library.

## Usage

1. Clone this repository or download the script directly.

2. Make sure you have an input text file (`input.txt`) that contains the text you want to summarize.

3. Run the script:

```bash
python text_summarization.py
```

## Requirements

You can install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

4. The script will generate a summary of the input text and print it to the console.

## Customization

- You can adjust the maximum length of the summary by modifying the `max_length` parameter in the `generate_summary()` function.
- Ensure that your input text file is properly formatted and encoded in UTF-8.

## Sources

- This script utilizes the Hugging Face Transformers library: https://huggingface.co/transformers/
- The pre-trained T5 model used in this script is from the T5 model family: https://huggingface.co/google-t5

## Coding Standards

- **PEP 8 Compliance**: This script adheres to the guidelines outlined in [PEP 8](https://www.python.org/dev/peps/pep-0008/), the official style guide for Python code. Following PEP 8 ensures that the code is clean, readable, and consistent.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

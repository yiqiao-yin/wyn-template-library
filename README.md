# WYN-Template-Library

## Overview

`WYN-Template-Library` is a Python library that leverages the power of `numpy`, `pandas`, `matplotlib`, and `openai` to provide robust data analysis and visualization capabilities. This library aims to simplify complex data processing tasks and help users visualize their data effectively.

## Features

- **Data Manipulation**: Use `pandas` for easy and efficient data manipulation.
- **Numerical Computations**: Leverage `numpy` for high-performance numerical computations.
- **Data Visualization**: Create stunning visualizations with `matplotlib`.

## Installation

To install the `WYN-Template-Library` library, you can use `poetry`. First, ensure you have `poetry` installed. If not, you can install it using `pip`:

```terminal
pip install poetry
```

Then, create a new project and add the necessary dependencies:

```terminal
poetry new WYN-Template-Library
cd WYNTemplate
poetry add numpy pandas matplotlib
```

## Usage

Here is a simple example of how to use `WYN-Template-Library`:

```python
# YOUR CODE HERE

# Install
! pip install wyn-template-library

# Inspect
ChatBot

# Grab your API key
from google.colab import userdata
OPENAI_API_KEY = userdata.get('OPENAI_API_KEY')

# Define bot
bot = ChatBot(
    OPENAI_API_KEY=OPENAI_API_KEY,
    PROTOCOL="You are a helpful assistant",
    MODEL="gpt-3.5-turbo"
)

# Try it out!
bot.generate_response("Tell me a joke")
# Sure! Here's a joke for you: Why did the scarecrow win an award? Because he was outstanding in his field!

bot.generate_response("My name is John, what's your name?")
# I'm just a virtual assistant, you can call me Assistant. How can I help you today, John?

bot.generate_response("What questions did I ask you?")
# You asked me to tell you a joke and you also told me your name is John. How can I assist you further, John?
```

## Publishing to PyPI

To publish your library to PyPI, follow these steps:

1. **Configure Poetry**: Add your PyPI token to Poetry configuration.

    ```terminal
    poetry config pypi-token.pypi pypi-<TOKEN_HERE>
    ```

2. **Build the Project**: Build your project using Poetry.

    ```terminal
    poetry build
    ```

3. **Publish the Project**: Publish your project to PyPI.

    ```terminal
    poetry publish
    ```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact [Yiqiao Yin] at [eagle0504@gmail.com].
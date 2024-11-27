
# WLTech.Ai ARC Challenge Solver

This repository contains a Python implementation designed to solve the [ARC Challenge (2024)](https://arcchallenge.com). 
The script integrates with APIs and libraries to process and analyze problem sets. The original notebook can be viewed 
and executed directly on Google Colab [here](https://colab.research.google.com/drive/1-rQoqrGRGQE6M8bMpfzqf6tV3TnUi-Mp?authuser=1#scrollTo=mfDUGTFgYfZw).

## What This Code Does
This script is designed to solve ARC challenges by leveraging AI capabilities through the following steps:
1. **Task Loading**: Loads challenge tasks and corresponding solutions from JSON files.
2. **AI Integration**: Uses Anthropic's Claude and OpenAI's GPT models for reasoning and solution generation.
3. **Result Processing**: Generates solutions to the given challenges, which can then be validated or further analyzed.

## Features
- Automated solving of ARC tasks using advanced AI models.
- Flexible task loading from user-provided JSON files.
- Seamless integration with Anthropic and OpenAI APIs.

## Requirements
To run this script, ensure the following dependencies are installed:
- Python 3.8+
- Libraries: 
  - `anthropic`
  - `pydantic`
  - `openai`

Install them using:
```bash
pip install -U anthropic pydantic openai
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/WLTech.Ai-ARC-Challenge.git
   cd WLTech.Ai-ARC-Challenge
   ```

2. Prepare your API keys:
   - Store `ANTHROPIC_API_KEY` and `OPENAI_API_KEY` in a secure location. You can use the `google.colab.userdata` method or set them as environment variables.

3. Run the script:
   ```bash
   python WLTech.Ai-ARC-Challenge.py
   ```

4. Input your challenge and solution files as JSON:
   ```python
   load_tasks('path/to/challenges.json', 'path/to/solutions.json')
   ```

## Project Structure
- **`WLTech.Ai-ARC-Challenge.py`**: Main script to solve ARC challenges.
- **Dependencies**: All required libraries are listed in the script.

## Contributions
Contributions are welcome! Feel free to submit issues or pull requests for improvements.

## License
This project is licensed under the MIT License. See `LICENSE` for more details.

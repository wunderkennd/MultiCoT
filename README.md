# MultiCoT

## Overview
`MultiCoT` is a repository that demonstrates [Chain-of-Table](https://arxiv.org/abs/2401.04398) reasoning on multiple tables powered by [LangGraph](https://github.com/langchain-ai/langgraph).

Try the hosted demo: https://cyqiq-cot-demo-c27oq5sqda-uc.a.run.app/

## Installation

Follow these steps to set up `MultiCoT`:

1. **Clone the Repository**
    ```
    git clone https://github.com/CYQIQ/MultiCoT.git
    ```
2. **Install Dependencies**
    Navigate to the repository directory and run:
    ```
    pip install -r requirements.txt
    ```
3. **Configure API Keys**
    Create a `.env` file in the root directory. Add your OpenAI API key and LangChain API details as follows:
    ```
    OPENAI_API_KEY="..."
    LANGCHAIN_API_KEY="..."
    LANGCHAIN_TRACING_V2="..."
    LANGCHAIN_ENDPOINT="..."
    LANGCHAIN_PROJECT="..."
    ```

## Usage
For detailed instructions on how to run `MultiCoT`, refer to the `CYQIQ_COT.ipynb` Jupyter Notebook within the repository.

## Data
The `data` directory includes an example dataset comprised of 6 CSV files necessary to run the notebook. To run MultiCoT with your own data, change the data loading logic and the table descriptions in `CYQIQ_COT.ipynb`

## Help
Feel free to email us at hello@cyqiq.ai

## Acknowledgments
- Big thanks to [@hwchase17](https://github.com/hwchase17) and team [LangChain](https://github.com/langchain-ai) for their amazing guides.
- Big thanks to [@zaturalma2](https://github.com/zaturalma2) for helping put the notebook together.

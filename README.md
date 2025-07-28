# LLUMO-AI-Assignment
An Assignment
# RAGAs Evaluation Assignment

##  Objective
Evaluate LLM-generated responses using RAGAs metrics:
- Faithfulness
- Answer Relevancy
- Context Precision

## Input
- `logs.json`: Contains conversation logs with system/user input and LLM output.

## Output
- `ragas_scores_output.json`: Contains RAGAs metric scores for each item.

##  Libraries Used
- `ragas`
- `datasets`
- `langchain-core`
- `langchain-openai`
- `OpenAI API`

## ⚙️ Setup Instructions
1. Install requirements:
    ```bash
    pip install ragas datasets langchain-core langchain-openai
    ```
2. Set your OpenAI API key:
    ```python
    import os
    os.environ["OPENAI_API_KEY"] = "your-key"
    ```

3. Run the notebook cell by cell in [Google Colab](https://colab.research.google.com)

##  Notes
- My OpenAI API quota was **exhausted**, so scores are currently showing `NaN`.
- The full code works and is ready for evaluation once a valid key is provided.
- I also explored integrating Gemini for manual evaluation (optional idea).

## 🔗 Colab Notebook Link
[Open in Google Colab]([PASTE_YOUR_COLAB_SHARE_LINK_HERE](https://colab.research.google.com/drive/1Q1JoOwcbS26ECShLKVGP1JCpxZWS1APV#scrollTo=qIY5RYDFBGoz))

# Quiz-Generator
A Quiz Generator powered by EvaDB

## Installation

To install the Quiz Generator, follow these steps:

1. Clone the repository to your local machine.
2. Open a terminal
3. Navigate to the downloaded project folder
4. Execute the following command `pip install -r requirements.txt` to install the dependencies required for the application.

## Setup
1. Open the [quizcreator.py](quizcreator.py) file
2. Substitute your OpenAI API Key on line 19.
   ```
   18: #Enter your OpenAI API key here
   19: openai.api_key = "<OPENAI-API-KEY>"
   ```
3. Substitute the path to your PDF on line 22.
    ```
    22: pdf_path = '<PDF-PATH>'
    ```
4. The application is now ready to run

## Run
1. Open a terminal
2. Navigate to the project folder
3. Run the application using the command `python quizcreator.py`.


## Additional Information

Lines 104 to 115 in [quizcreator.py](quizcreator.py) contain the prompt being provided to the GPT 3.5 API. 

This prompt can be altered to modify parameters/format of the quiz like number of questions, output format, number of multiple choice options, and so on. 

## References

The following references were used while building this project were:

- OpenAI Pricing - https://openai.com/pricing
  
- EvaDB documenta9on - https://evadb.readthedocs.io/en/stable/source/overview/gegng-started.html
  
- EvaDB Repository - https://github.com/georgia-tech-db/evadb
  
- OpenAI Embeddings - https://plaoorm.openai.com/docs/guides/embeddings
  
- HuggingFace “bart-large-cnn” - https://huggingface.co/facebook/bart-large-cnn
# Medical_Bot
The Llama2 Medical Bot is a sophisticated tool created to deliver medical information by responding to user inquiries using advanced language models and vector stores

## Prerequisit
Before you can start using the Llama2 Medical Bot, make sure you have the following prerequisites installed on your system:

* Python 3.6 or higher
* Required Python packages (you can install them using pip):
* langchain
* chainlit
* sentence-transformers
* faiss
* PyPDF2 (for PDF document loading)

## Workflow

            +------------------+
            | Llama 2 Model    |
            | (TheBloke on HF) |
            +--------+---------+
                     |
                     v
            +--------+---------+
            | CTransformers    |
            | (Python Bindings)|
            +--------+---------+
                     |
                     v
            +--------+---------+
            | Sentence         |
            | Transformers     |
            | (all-MiniLM-v6)  |
            +--------+---------+
                     |
                     v
            +--------+---------+
            | FAISS Vector     |
            | Store            |
            +--------+---------+
                     |
                     v
            +--------+---------+
            | QA Chain         |
            | (Prompt Template)|
            +--------+---------+
                     |
                     v
            +--------+---------+
            | Chainlit         |
            | (Chat Interface) |
            +------------------+


## End Result (The Product)
![image](https://github.com/Tshar-k/Medical_Bot/assets/117516567/963e0019-eefd-4b02-b55b-d418f8090d73)


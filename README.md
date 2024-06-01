# Medical-chatbot-using-LLama2
Medical chatbot using LLama2


## How to run?

### STEPS:
### Clone the repository

```bash
 https://github.com/sankalpbhambri27/Medical-chatbot-using-LLama2.git
 ```

 ### STEP 01- Create a conda environment after opening the repository

 ```bash
 conda create -n mchatbot python=3.8 -y

conda activate mchatbot
```
### STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

### Create a .env file in the root directory and add your Pinecone credentials as follows:

```bash
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

### Download the quantize model from the link provided in model folder & keep the model in the model directory:

### Download the Llama 2 Model:

```bash
llama-2-7b-chat.ggmlv3.q4_0.bin
```

### From the following link:

```bash
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```

### run the following command

```bash
python store_index.py
```
### Finally run the following command
```bash
python app.py
```

### open up localhost:

### Techstack Used:
### Python
### LangChain
### Flask
### Meta Llama2
### Pinecone
# Medical-personal-assistant-chatbot-

## Prerequisites
 Python 3.6 or higher
- Required Python packages (you can install them using pip):
    - langchain
    - chainlit
    - sentence-transformers
    - faiss
    - PyPDF2 (for PDF document loading)
## Installation
1. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/Kalium-99/Medical-personal-assistant-chatbot-.git
    ```

2. Create a Python virtual environment :
   ```bash
   conda create -n <env-name>
   conda activate <env-name>
   ```
3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```
4. Download the required language models and data.
   ```bash
   https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin
   ```
5.Start the bot by running your application or using the provided Python script.
```bash
chainlit run model.py -w
   ```

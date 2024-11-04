# ChatGist


>> install and extract the test.
>> install 'llama-2-7b-chat.Q4_K_M.gguf' from huggingface.
>> test >> pdf-chat >> backend >> loadllm.py     - change the path of llm as per your model path in system.
here,
5. model_path = "D:\completed\llama_bloke_pdf\llama-2-7b-chat.Q4_K_M.gguf"


Step 1: Set Up Your Development Environment

1. Install Required Software

>> Node.js: Download and install Node.js.

>> Python: Ensure you have Python 3.x installed. Download from Python.org.

>> FastAPI: Install FastAPI and Uvicorn using pip:

>> pip install fastapi uvicorn langchain transformers faiss-cpu

2. node and react addition
   
npx create-react-app pdf-chat
cd pdf-chat
npm install axios


now open 2 terminals:

1st terminal: 
>> cd pdf-chat/backend
>> uvicorn fileingestor:app --reload

2nd terminal:
>> cd pdf-chat
>> npm run start


Done!!!!!




![Screenshot 2024-11-02 235311](https://github.com/user-attachments/assets/3a6d566c-6ba8-43a5-9819-5d72b7711367)


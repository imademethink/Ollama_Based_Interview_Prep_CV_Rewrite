# Free : Game Changer - Ollama based Self Interview, CV rewrite, Interview prep

# YouTube video link :  https://youtu.be/MpQLkG01DzY

Master your next interview with this FREE, 100% private AI assistant! 

Learn to build a local Ollama-powered RAG utility for resume rewriting and voice-interactive prep. 

No subscriptions, just powerful, offline career automation.

# Steps
As explained in above YouTube video, install Ollama (Windows/ Linux) -> Sign In

Download local model or cloud AI model using: 
ollama run gpt-oss:120b

OR 

ollama run gpt-oss:120b-cloud

git clone https://github.com/imademethink/Ollama_Based_Interview_Prep_CV_Rewrite.git

cd Ollama_Based_Interview_Prep_CV_Rewrite

Generate ollama api key and insert in ollama_api_key_file.txt file

pip install -r requirements.txt

# For pure text chat
python TerminalChatText.py

# For Voice input and text output
python TerminalChatVoice.py

# For text input, output and voice input, output as well
streamlit run UIChat.py

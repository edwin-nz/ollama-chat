# ollama-chat

NOTE: This was a prototype UI to the early command-line Ollama backend. Support is now discontinued and users should try the more advanced [Open WebUI](https://github.com/open-webui/open-webui) now available.

Streamlit chat app using LLMs in Ollama docker backend to interact with the various models available. Now you can access Ollama using a browser with the markdown responses rendered in the display. You can even access it from your phone or tablet once you've installed this on your computer. 


<img width="553" alt="image" src="https://github.com/edwin-nz/ollama-chat/assets/36632227/ee764bba-719d-4a69-aeae-997e1f56c50f">



To run:

1. Clone this repository

2. Make sure Docker is installed and run the following
```
docker-compose up -d
```
3. For a new installation, there are no models loaded yet. So, access the Ollama Docker container in terminal mode and run the following to load your first model
```
ollama pull orca-mini
```
4. Access from your browser using
```
http://localhost:8501
```
5. Try out other models by loading them in the same way. See https://ollama.ai/library for details of all the models supported by Ollama


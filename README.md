# Yandex free course

## install
source .venv/bin/activate

pip install requests numpy sentence-transformers faiss-cpu pypdf

- for Jupyter NB only
pip install ipywidgets  

## ollama
ollama --version
ollama pull qwen2.5:1.5b
ollama run qwen2.5:1.5b 
/bye

git clone --depth 1 https://github.com/ollama/ollama.git temp_ollama 

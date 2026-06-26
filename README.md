#llm

## 1.
 python3 -m venv .venv

## 2.
source .venv/bin/activate

## 3.
pip install --upgrade pip

## 4.
pip install web.py ollama

## 5.
.gitignore
*.pyc
__pycache__/
.venv/

## 6.
pip freeze > requirements.txt

## 7.
python3 -V > runtime.txt

## 8.
curl http://ollama/install.sh|sh

## 9.
ollama serve

## 10.
ollama list

## 11.
ollama pull llama3.2:3b

## 12.
ollama run llama3.2:3b

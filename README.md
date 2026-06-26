#llm

## 1. Crea el entorno virtual
 python3 -m venv .venv

## 2. Enciende el entorno virtual
source .venv/bin/activate

## 3. Actualiza paquetes
pip install --upgrade pip
 
## 4. Instala librerias
pip install web.py ollama

## 5. Carpetas que no deben guardarse
.gitignore
*.pyc
__pycache__/
.venv/

## 6. Lista de librerias instaladas
pip freeze > requirements.txt

## 7. Versión de python
python3 -V > runtime.txt

## 8. Descarga ollama
curl http://ollama/install.sh|sh

## 9. Enciende servidor
ollama serve

## 10. Muestra sus modelos
ollama list

## 11. Se conecta a codespace
ollama pull llama3.2:3b
 
## 12. Carga el modelo descargado
ollama run llama3.2:3b

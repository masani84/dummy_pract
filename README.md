......................
conda create -p venv python=3.8
conda activate venv 
or
conda activate C:\SIVA\INEURON\VC_Env_Dummy\venv
crate .gitignore (add venv inside .gitignore)
create README.md
craete requirements.txt
	numpy
	python
	Flask
create setup.py (add code to setup.py file)
python setup.py install
......................
add components
__init__.py
data_ingestion.py
data_tarnsformation.py
model_trainner.py

add pipeline
__init__.py
pred_pipeline.py
train_pipeline.py

exception.py
logger.py
util.py


git init
git add README.md	git add . (add venv folder in gitignore file)
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/masani84/dummy_pract
git push -u origin main
......................
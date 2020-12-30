# Instalação e execução do microblog
git clone https://github.com/rafael-prazeres/microblog.git
cd microblog/
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt 
flask db upgrade
flask run

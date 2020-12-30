### Bem-vindo ao Microblog

Esta é um exemplo de aplicação em destaque no tutorial
Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
de Miguel Grinberg. Veja o tutorial para obter instruções sobre como utilizar
este projeto.

##### Instalação e execução do microblog

* No Linux, a partir do shell:

```shell
foo@bar:~$ git clone https://github.com/rafael-prazeres/microblog.git
foo@bar:~$ cd microblog/
foo@bar:~/microblog$ python3 -m venv venv
foo@bar:~/microblog$ source venv/bin/activate
(venv) foo@bar:~/microblog$ pip install --upgrade pip
(venv) foo@bar:~/microblog$ pip install -r requirements.txt 
(venv) foo@bar:~/microblog$ flask db upgrade
(venv) foo@bar:~/microblog$ flask run
```

* No Windows, a partir do prompt de comando:

```bat
C:\Users\foo> git clone https://github.com/rafael-prazeres/microblog.git
C:\Users\foo> cd microblog/
C:\Users\foo\microblog> py -m venv venv
C:\Users\foo\microblog> venv\Scripts\activate.bat
(venv) C:\Users\foo\microblog> pip install --upgrade pip
(venv) C:\Users\foo\microblog> pip install -r requirements.txt 
(venv) C:\Users\foo\microblog> flask db upgrade
(venv) C:\Users\foo\microblog> flask run
```

##### Requisitos para instalação do microblog:

* No Linux (Ubuntu):
    * Instalar pacotes git e python3-venv

* No Windows:
    * [Baixar e instalar o python](https://python.org)
    * [Baixar e instalar o git](https://git-scm.com/download/win)

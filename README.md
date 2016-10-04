#WebLanches
_Application web_

### Intro
Django é um framework gratuito e de código aberto para a criação de aplicações web, escrito em Python. É um framework web, ou seja, é um conjunto de componentes que ajuda a desenvolver sites de forma mais rápida e mais fácil.

###Instalação
- Instale o python no Ubuntu e seus derivados  
``` sudo apt install python3.5 ```  

- Para saber a versao do python  
``` python3 --version ```  

- Editor de código
	- IDE
		- PyCharm
		- Spyder
	- Outros
		- [Atom](atom.io) (Recomendado)
		- Sublime Text 
		- Gedit

- Configurar o ambiente virtual(tambem chamado de virtualenv)  
``` python3 -m venv myvenv ```  
Em caso de erro execute:  
``` sudo apt install python-virtualenv ```  
``` virtualenv --python=python3.5 myvenv ```  
Agora ative o virtualvenv
	- ``` . myvenv/bin/activate  ```
	- Apos isso seu terminal devera se parecer com isso: ```  (myvenv) ~/local_do_arquivo$ ```

- Instale o Django
``` pip install django==1.8.5 ```  
Em caso de erro instale o pip  
``` sudo apt install pip ```  


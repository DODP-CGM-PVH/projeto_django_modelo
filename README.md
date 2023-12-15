##########CRIAÇÃO DE "PROJETO" DJANGO##########

#Criação da máquina virtual
no windows: python -m venv venv # o ultimo venv é o nome da maquina os mais usados é (.env, .venv, env/, Venv/, ENV/, env.bak/ e venv.bak/).
no linux ou mac: python3 -m venv venv # o ultimo venv é o nome da maquina os mais usados é (.env, .venv, env/, Venv/, ENV/, env.bak/ e venv.bak/).

#Ativação da máquina virtual
windows: .\venv\Scripts\activate
linux ou mac: source venv/bin/activate ou . venv/bin/activate

#caso queira #.gitignore
https://github.com/luizomf/curso-django-projeto1/blob/main/.gitignore

#pip install django #instala o django na maquina virtual a venv

#django-admin startproject projeto . #projeto é o nome e o ponto no final pra definir a pasta de origem para criação se não criarar duas pastas com o mesmo nome.

#python manage.py runserver #executa o servidor


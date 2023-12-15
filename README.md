# CRIAÇÃO DE "PROJETO" DJANGO

## Criação da máquina virtual

no windows:
```
python -m venv venv 
```

no linux ou mac:
```
python3 -m venv venv 
```

## No Windows execute este script no PowerShell como administrador, para poder ativar a máquina virtual 
```
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

## Ativação da máquina virtual

windows: 
```
.\venv\Scripts\activate
```
linux ou mac: 
```
source venv/bin/activate
. venv/bin/activate
```

## .gitignore especifico para Django
```
https://github.com/luizomf/curso-django-projeto1/blob/main/.gitignore
```

## Instalando o Django via terminal 
```
pip install django
```

## Criação de projeto 
```
django-admin startproject projeto .
```


## Executa o servidor
```
python manage.py runserver 
```



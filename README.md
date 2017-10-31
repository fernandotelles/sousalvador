
# Sou Salvador
O site de informa��es sobre a cidade de Salvador.

# Instala��o do ambiente de desenvolvimento

Para instalar a aplica��o, voc� deve clonar o projeto, entrar no diret�rio,e criar um virtualenv.
```
virtualenv env
```

Depois � necess�rio ativar o virtualenv.
```
source env/bin/activate
```

O pr�ximo passo � instalar as depend�ncias, para isso fa�a:
```
pip install -r requirements.txt
```

Por fim, o �ltimo passo � rodar a aplica��o flask:
```
FLASK_APP=hello.py flask run
```
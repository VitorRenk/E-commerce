# Projeto E-commerce

### Introdução
#### Projeto demonstrativo para criação de um site e-commerce de produtos variados, gerenciado pelo administrador, com integração de pagamentos via PayPal e cartão de crédito. A aplicação foi desenvolvida utilizando Django, React, Kubernetes e Docker.

![ecommerce](ecommerce.png)

![django](django.png)
---

### Como utilizar o projeto

Após realizar o clone do repositório, basta que você crie a pasta de ambiente env dentro da pasta do projeto e então instale as dependências necessárias no terminal:
```
python -m venv env
pip install -r requirements.txt
```
Obs: o arquivo requirements.txt estará dentro da pasta backend, portanto tenha certeza de que você esta na pasta correta para a instalação.

Pressione F1 e selecione:
- Python: Select Interpreter
- Selecione o Python da pasta env

Após a instalação dos requirements, ative os scripts da env no terminal:
```
.\env\Scripts\Activate.ps1
```

Agora só falta acionar a api do django:
```
python manage.py makemigrations
python manage.py migrate
```


44e1179 (primeiras mudanças na documentação)

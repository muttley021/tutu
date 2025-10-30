# Projeto Flask - site HTML

Esta pasta contém um exemplo mínimo de site em Flask com templates HTML e assets estáticos.

Como rodar (Windows PowerShell):

1. Criar e ativar ambiente virtual:

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

2. Instalar dependências:

```powershell
pip install -r requirements.txt
```

3. Rodar a aplicação (defina a variável de ambiente FLASK_APP ou execute diretamente):

```powershell
$env:FLASK_APP = "app.py"
$env:FLASK_ENV = "development"
flask run
```

ou executar diretamente:

```powershell
python app.py
```

Acesse http://127.0.0.1:5000

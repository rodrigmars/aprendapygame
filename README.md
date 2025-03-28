# Aprenda Pygame
`Aprenda Pygame` é um laboratório de programação 
em Python com suporte a `git`, `github` e biblioteca [*`pygame`*](https://github.com/pygame/pygame).
O desafio envolve baixar, instalar e executar o módulo *alien*, antes será necessário baixar a *lib* [***`pyenv-win`***](https://github.com/pyenv-win/pyenv-win) para instalação do interpretador [*`Python 3.13.0`*](https://www.python.org/downloads/release/python-3130/). O ambiente de desenvolvimento deve contemplar sistema operacional *`Windows`*, terminal *`PowerShell`* e editor *`VSCode`*.


### Pré-requisitos

Instalar ferramenta [*`pyenv-win`*](https://github.com/pyenv-win/pyenv-win/blob/master/docs/installation.md#powershell) no *`Windows`* com *`PowerShell`*.

Clonar repositório usando o comando de conexão `Secure Shell (SSH)`

```powershell
git clone git@github.com:rodrigmars/aprendapygame.git
```

Abrir projeto com `VSCode`
```powershell
cd .\aprendapygame\ && code .
```

Criar ambiente virtual com `venv`
```powershell
python -m venv .venv
```

Ativar ambiente virtual
```powershell
.\.venv\Scripts\Activate.ps1
```

Instalar dependências
```powershell
pip install -r .\requirements.txt
```

Executar módulo alien
```powershell
python .\src\alien.py
```


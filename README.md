# Aprenda Pygame
Este projeto serve como atividade introdutória para práticas de desenvolvimento
com `git`, `github` e biblioteca [*`pygame`*](https://github.com/pygame/pygame).
O desafio envolve baixar, instalar e executar o módulo game. Necessário instalar a *lib* [***`pyenv-win`***](https://github.com/pyenv-win/pyenv-win) para gerenciamento do interpretador Python. O ambiente de desenvolvimento contempla sistema operacional *`Windows`* e terminal *`PowerShel`*.

## Procedimentos
Clonar repositório, o comando abaixo usa uma conexão do tipo `Secure Shell (SSH)`

```python
git clone git@github.com:rodrigmars/aprendapygame.git
```

Abrir projeto dentro do VSCode
```python
cd .\aprendapygame\ && code .
```

Criar ambiente virtual
```python
python -m venv .venv
```

Ativar ambiente virtual
```python
.\.venv\Scripts\Activate.ps1
```

Instalar dependências
```python
pip install -r .\requirements.txt
```

Executar módulo alien
```python
python .\src\alien.py
```


# 1. Introducción

# 2. Librerías ocupadas

# 3. Ejecución de notebooks en Visual Studio Code:

Para poder poder visualizar los notebooks en Visual Studio Code sin necesitar instalar Jupyter Notebooks se pueden realizar los siguientes pasos:

1.- Generar un entorno virtual y activaro

```
python -m venv nombre_entorno

. /venv/scripts/activate
```

2.- Instalar kernel

```
pip install ipykernel
ipython kernel install --user --name=nombre_proyecto
```

Fuente: https://anbasile.github.io/posts/2017-06-25-jupyter-venv
https://stackoverflow.com/questions/58119823/jupyter-notebooks-in-visual-studio-code-does-not-use-the-active-virtual-environm

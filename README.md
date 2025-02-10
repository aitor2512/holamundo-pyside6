# holamundo-pyside6

## Linux

```sh
sudo apt update
sudo apt install python3 python3-pip

python3 -m venv venv
source venv/bin/activate

pip install PySide6
```

```python
from PySide6.QtWidgets import QApplication, QLabel

app = QApplication([])
label = QLabel("¡Hola, Mundo!")
label.show()
app.exec()
```

```sh
python main.py
```

## Windows

Descargar e instalar Python desde la web oficial:  
[https://www.python.org/downloads/](https://www.python.org/downloads/)  

Durante la instalación, marcar la opción **"Add Python to PATH"**.

```sh
python -m venv venv
venv\Scripts\activate

pip install PySide6
```

```python
from PySide6.QtWidgets import QApplication, QLabel

app = QApplication([])
label = QLabel("¡Hola, Mundo!")
label.show()
app.exec()
```

```sh
python main.py
```

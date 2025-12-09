## 📦 UsbCloner ##
Herramienta para copiar archivos desde una carpeta de origen a múltiples memorias USB simultáneamente.

### 📘 Descripción

UsbCloner es una herramienta creada para facilitar el proceso de duplicación de archivos en unidades USB.
Permite seleccionar una carpeta de origen y enviarla a varias memorias extraíbles al mismo tiempo, con dos modos:

- Append: Mantiene los archivos existentes y copia solo los nuevos.

- Borrar: Elimina el contenido del USB antes de copiar archivos nuevos (solo en unidades extraíbles reconocidas).

La herramienta está diseñada para uso administrativo, distribución de material de estudio, material de empresa, o creación de kits USB.

### 🛡️ Seguridad
 
UsbCloner NO modifica archivos del sistema, no accede a Internet, no recopila datos, y solo opera en unidades USB detectadas como “removibles” usando psutil.

El modo “Borrar” únicamente elimina contenido de unidades extraíbles, nunca del sistema operativo.
Está desarrollado en Python usando Tkinter y PyInstaller.

### 🔧 Funciones principales

- Detección automática de unidades USB

- Copia simultánea a múltiples memorias

- Filtro de extensiones prohibidas (configurable)

- Registro detallado en archivo de log

- Interfaz gráfica sencilla

- Opción de borrar contenido del USB antes de copiar

### 📂 Estructura del proyecto

UsbCloner/
├─ clonusb.py
├─ img/
│   └─ usbcloner.ico
├─ dist/
├─ build/
├─ README.md
├─ LICENSE
└─ requirements.txt

### ▶️ Uso

1. Selecciona la carpeta de origen

2. Selecciona una o varias memorias USB

3. Elige el modo de copia (Append o Borrar)

4. Presiona EMPEZAR

5. Revisa los mensajes del log para ver el progreso

### 💻 Entornos
- Windows 10 / 11
    - Python 3.10+
    - Librerias: psutil, tkinter, shutil, os
- Linux
    - Este entorno todavia esta en desarrollo pero teoricamente funciona correctamente, "falta comprobarlo".


## RECURSOS UTILIZADOS DURANTE LA CREACION DE ESTE PROGRAMA

### RESOURCES USADOS PARA EL PROYECTO:
## CLONAR O COPIAR ARXIVOS: 
- https://python.19633.com/es/Python/1002010766.html
- https://es.stackoverflow.com/questions/406502/copiar-archivos-de-una-carpeta-a-otra-con-python
- https://labex.io/pythoncheatsheet/modules/os-module

### TKINTER:
https://www.udemy.com/course/python-gui-tkinter/?utm_source=bing&utm_medium=udemyads&utm_campaign=BG-Search_DSA_Alpha_Prof_la.EN_cc.ROW-English&campaigntype=Search&portfolio=Bing-ROW-English&language=EN&product=Course&test=&audience=DSA&topic=Python&priority=Alpha&utm_content=deal4584&utm_term=_._ag_1316117806688179_._ad__._kw_Python+en_._de_c_._dm__._pl__._ti_dat-2334057027983561%3Aloc-170_._li_164486_._pd__._&matchtype=b&couponCode=CP251120G2V2

### REVISION DE CODIGO:
- https://sonarcloud.io

### DUDAS QUE HE TENIDO SOBRE COMO HACER OTRAS COSAS
- CHATGPT
- stackoverflow

- ...


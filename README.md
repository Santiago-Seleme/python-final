# Clase 11 Actividad en Python

## 1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como `administrador en Window`
## 2. Creamos una carpeta o directorio: 
`mkdir python-final`
## 3. Entramos en ella: 
`cd python-final`
## 4. Iniciamos el repositorio:
`git init`
## 5. Creamos un archivo:
`touch finales.py`
## 6. Abrimos VSC:
`code .`
## 7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
`python -V`
`python3 -V`
## 8. Creamos el entorno virtual en Python:
`python3 -m venv venv #Creamos el entorno virtual`
## 9. Activamos el entorno virtual:
`source venv/bin/activate #Activamos el entorno virtual en Linux`
`venv/scripts/activate #En windows`
## 10. Hacemos actualización del pip de Python
`python3 -m pip install --upgrade pip #Actualizamos el pip`

## 11. Investigar ¿Qué es el pip y porque lo actualizamos?
```
pip es el gestor de paquetes de Python. Su nombre es un acrónimo recursivo que significa "Pip Installs Packages" (Pip instala paquetes). Este gestor permite a los usuarios instalar, actualizar y desinstalar paquetes de software distribuidos a través del Índice de Paquetes de Python (PyPI). Usar pip facilita la gestión de bibliotecas y dependencias necesarias para proyectos de Python.
La actualización de pip es importante por varias razones:
Corrección de errores: Las versiones más recientes a menudo corrigen errores y problemas de versiones anteriores, mejorando la estabilidad y el rendimiento del gestor de paquetes.
Nuevas funcionalidades: Las actualizaciones pueden incluir nuevas funcionalidades y características que no estaban presentes en versiones anteriores.
Mejoras de seguridad: Las actualizaciones pueden incluir parches de seguridad que protegen contra vulnerabilidades.
Compatibilidad: A medida que Python y las bibliotecas evolucionan, es importante mantener pip actualizado para asegurar la compatibilidad con los nuevos paquetes y versiones de Python.
```
## 12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

## 13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
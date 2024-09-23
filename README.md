# Repositorio de Contenidos de Código de la Universidad

Bienvenido al repositorio de practicas con flask, aqui encontraras diferentes api desarrolladas enteramente con flask.

## Índice

- Descripción
- Estructura del Repositorio
- Requisitos
- Instalación
- Uso
- Contribuciones
- Issues
- Licencia
- Autores

## Descripción

Este repositorio agrupa una serie de API con flask que constituyen una práctica con la tecnologia.

## Estructura del Repositorio

La estructura del repositorio es la siguiente:

````
├── Proyecto1/
│   ├── flaskr1/
│   ├── instance/
│   ├── test/
│   ├── venv/
│   ├── requirements.txt/
│   ├── description.md/
│   ├── MANIFEST.in/
│   └──pyproject.toml/
├── Proyecto2/
│   ├── flaskr1/
│   ├── instance/
│   ├── test/
│   ├── venv/
│   ├── requirements.txt/
│   ├── description.md/
│   ├── MANIFEST.in/
│   └──pyproject.toml/
.
.
.
├── LICENCE
└── README.md
````

## Requisitos

- [Estilo de Commit](https://www.conventionalcommits.org/en/v1.0.0/)
- [Estilo de Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/best-practices-for-pull-requests)

## Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/marcoeferro/flask.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd flask
    ```

## Uso

Cada carpeta contiene una API diferente desarrollada con flask para correrla deberas seguir los siguientes pasos.
1. Instalar las dependencias 
```bash
pip install -r requirements.txt
```
2. Activar el entorno virtual visita la [documentacion](https://virtualenv.pypa.io/en/latest/user_guide.html#quick-start) o el [Video Explicativo](https://youtu.be/N5vscPTWKOk)
3. Correr la aplicacion de flask 
```bash
flask --app flaskr run --debug
```
4. Go to http://127.0.0.1:5000/auth/register

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva funcionalidad'`).
4. Sube tus cambios (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request. [Video Tutorial](https://youtu.be/BPns9r76vSI)

## Issues

Si encuentras algún problema o tienes alguna sugerencia, por favor abre un issue en el repositorio. Para hacerlo, sigue estos pasos:

1. Ve a la pestaña "Issues" en el repositorio.
2. Haz clic en "New Issue".
3. Describe el problema o la sugerencia con la mayor cantidad de detalles posible.
4. Asigna etiquetas relevantes y, si es necesario, asigna el issue a una persona específica.

## Licencia

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

## Autores

- Marco Ferro

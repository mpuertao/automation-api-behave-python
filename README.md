# Proyecto de Pruebas Automáticas de API con Behave (BDD)

Este proyecto utiliza Behave, una herramienta de desarrollo guiado por comportamiento (BDD), para realizar pruebas automáticas de una API. Las pruebas están escritas en Python y utilizan el marco de trabajo Behave para definir el comportamiento de la API en un formato legible para humanos.

## Descripción del Proyecto

El objetivo de este proyecto es automatizar las pruebas de la API de reqres.in, que proporciona servicios simulados de una API REST para propósitos de pruebas y desarrollo. Las pruebas están diseñadas para validar el comportamiento de la API en diferentes escenarios, como la creación, actualización y eliminación de recursos, así como la autenticación y autorización de usuarios.

## Estructura del Proyecto

```
.
├── Features
│   ├── API.feature
│   └── Steps
│       └── APISteps.py
├── README.md
├── Resources
│   └── config.json
├── Utility
│   ├── API_Utility.py
└── requirement.txt
```


## Instalación

1. Clona este repositorio en tu máquina local:

    ```bash
    git clone https://github.com/mpuertao/automation-api-behave-python..git
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd automation-api-behave-python
    ```

3. Instala las dependencias del proyecto utilizando pip:

    ```bash
    pip install -r requirements.txt
    ```

## Ejecución de las Pruebas

Para ejecutar las pruebas, utiliza el siguiente comando:

 ```bash
  behave
   ```

Tambien puedes ejecutar el reporte en allure y servirlo en local para su visualización



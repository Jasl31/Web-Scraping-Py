# Web Scraping de Trabajos Falsos con Python

Este repositorio contiene un script en Python que realiza un web scraping de una página de trabajos falsos utilizando el módulo `BeautifulSoup`. El script obtiene información relevante sobre trabajos (títulos, compañías y ubicaciones) desde una URL proporcionada y guarda los datos extraídos en un archivo `.csv`.

## Funcionalidad

El script realiza las siguientes acciones:

1. Realiza una solicitud `GET` a la URL: `https://realpython.github.io/fake-jobs/`.
2. Utiliza `BeautifulSoup` para analizar el contenido HTML y extraer elementos clave de los trabajos, como:
   - Título del trabajo.
   - Empresa.
   - Ubicación.
   - Enlace de aplicación.
3. Imprime los detalles de cada trabajo extraído.
4. Guarda los resultados en un archivo `.csv`.

## Requisitos

Para ejecutar este script, necesitas tener instaladas las siguientes bibliotecas de Python:

- `requests`
- `beautifulsoup4`

Puedes instalarlas utilizando `pip`:

```bash
pip install requests beautifulsoup4
```

# Uso

1. Clona este repositorio o descarga el archivo del script.
2. Asegúrate de tener instaladas las dependencias necesarias.
3. Ejecuta el script:

python nombre_del_script.py

4. El archivo Data.csv se generará en el mismo directorio, conteniendo los trabajos extraídos en formato CSV.

# Ejemplo del archivo CSV

El archivo Data.csv tendrá el siguiente formato:

Título del trabajo, Empresa, Ubicación
Ingeniero Python, Empresa XYZ, Ciudad ABC
Desarrollador Backend, Empresa DEF, Ciudad XYZ
...

# Blog Django

Proyecto base de un blog web desarrollado con Django.

## Descripción

Este repositorio contiene la estructura inicial de un proyecto Django para construir un blog.
Incluye la configuración base del proyecto (`blog_project`) y una aplicación llamada `posts`.
Está configurado en español de Argentina (`es-ar`) y con la zona horaria `America/Argentina/Buenos_Aires`.

## Instalación

Clonar el repositorio:

```bash
git clone https://github.com/sergioperalta1979/blog_django.git
```

Entrar a la carpeta del proyecto:

```bash
cd blog_django
```

Crear el entorno virtual:

```bash
python -m venv venv
```

Activar el entorno virtual.

En Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

En Linux o macOS:

```bash
source venv/bin/activate
```

Instalar las dependencias:

```bash
pip install -r requirements.txt
```

## Ejecutar el servidor

```bash
python manage.py runserver
```

Abrir en el navegador: http://127.0.0.1:8000/

Si el puerto 8000 está ocupado, se puede usar otro:

```bash
python manage.py runserver 8001
```

## Aplicaciones

- `posts`: aplicación inicial para manejar las publicaciones del blog.
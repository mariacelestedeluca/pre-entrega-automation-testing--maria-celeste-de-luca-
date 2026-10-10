# Pre-Entrega Automation Testing QA

## Propósito del proyecto

Proyecto de automatización de pruebas para el curso de Talento Tech. Automatiza la navegación sobre el sitio de práctica [saucedemo.com](https://www.saucedemo.com): login, verificación del catálogo de productos y manejo del carrito de compras.

## Tecnologías utilizadas

- Python
- Pytest
- Selenium WebDriver
- pytest-html (para generar el reporte)
- Git y GitHub

## Instalación de dependencias

``` python
pip install pytest 
pip install pytest-html 
pip install selenium
```

## Ejecución de pruebas

Para correr todos los tests y generar el reporte HTML:

```
pytest -v --html=reporte.html
```

Al terminar se genera el archivo `reporte.html` con los resultados


## Casos de prueba
- Login exitoso
- Login vacio
- Título de la página de inventario, presencia de productos
- Agregar el primer producto al carrito, verificar el contador y que el producto aparezca en el carrito


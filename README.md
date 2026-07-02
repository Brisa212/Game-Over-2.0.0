# Game-Over-2.0.0

# Tecnologías utilizadas

- Python 3
- Flask
- SQLite
- HTML Vainilla
- CSS3
- Bootstrap 5
- JavaScript
- Selenium
- WebDriver Manager

# Funcionalidades

## Usuarios

- Registro de usuarios
- Inicio de sesión
- Cierre de sesión


## Productos

- Listado de productos
- Filtro por categorías
- Vista individual del producto
- Hasta 4 imágenes por producto
- Descripción desplegable mediante acordeón

## Panel Administrador

- Agregar productos
- Editar productos
- Eliminar productos
- Protección mediante contraseña de administrador

## Carrito

- Agregar productos
- Eliminar productos
- Contador automático
- Almacenamiento mediante LocalStorage

# Base de datos

SQLite

Tablas:

- productos
- usuarios

Los productos almacenan:

- nombre
- precio
- categoría
- imagen principal
- imagen2
- imagen3
- imagen4
- descripción

# Testing

El proyecto cuenta con pruebas automatizadas desarrolladas con Selenium:

- Inicio
- Login
- Logout
- Registro
- Productos
- Producto individual
- Agregar producto
- Editar producto
- Editar y restaurar
- Eliminar producto
- Eliminar y restaurar
- Carrito
- Compra


# Instalación

Clonar el repositorio

```bash
git clone https://github.com/TU-USUARIO/GameOver.git
```

Entrar al proyecto

```bash
cd GameOver
```

Instalar dependencias

```bash
pip install flask selenium webdriver-manager
```

Ejecutar

```bash
python app.py
```

Abrir

```
http://localhost:5000
```

---

# Autor

Proyecto desarrollado por Brisa como trabajo práctico para la carrera de Desarrollo de Software.

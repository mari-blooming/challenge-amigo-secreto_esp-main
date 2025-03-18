# Amigo Secreto 🎁

Este es un proyecto web que permite a los usuarios ingresar nombres de amigos y realizar un sorteo aleatorio para determinar quién será el "amigo secreto".

## 🚀 Funcionalidades

- **Agregar nombres**: Permite ingresar nombres en una lista.
- **Validar entrada**: Evita agregar nombres vacíos.
- **Visualizar la lista**: Muestra los nombres ingresados en una lista.
- **Sorteo aleatorio**: Selecciona un nombre al azar de la lista y lo muestra en pantalla.

## 🛠️ Tecnologías utilizadas

- HTML
- CSS
- JavaScript

## 📜 Instrucciones de uso

1. Clona el repositorio o descarga los archivos.
2. Abre el archivo `index.html` en tu navegador.
3. Ingresa nombres en el campo de texto y presiona "Añadir".
4. Cuando la lista esté completa, presiona "Sortear amigo" para obtener un nombre al azar.

## 📂 Estructura del proyecto

```
📁 amigo-secreto
│── 📄 index.html    # Estructura principal del sitio
│── 📄 style.css     # Estilos del sitio
│── 📄 app.js        # Lógica en JavaScript
│── 📁 assets        # Imágenes e íconos
```

## 📌 Notas

- Se asegura que no se agreguen nombres vacíos.
- Se reinicia el campo de entrada después de añadir un nombre.
- Se usa `Math.random()` para seleccionar un nombre aleatorio de la lista.

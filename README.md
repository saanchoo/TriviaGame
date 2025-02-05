# Quizzler - Juego de Preguntas y Respuestas

**Quizzler** es una aplicación de preguntas y respuestas de tipo verdadero o falso basada en la API de Open Trivia Database (OpenTDB). El juego permite a los usuarios responder preguntas aleatorias y ver su puntaje en tiempo real.

## 📌 Características
- ✅ Obtiene preguntas de la API de OpenTDB.
- 🎨 Interfaz gráfica con Tkinter.
- 📊 Registro de puntaje en tiempo real.
- 🔴🟢 Cambio de color en la interfaz para indicar respuestas correctas e incorrectas.
- 🖱️ Botones con imágenes para seleccionar la respuesta.

## 🔧 Requisitos
Este proyecto requiere **Python 3** y las siguientes bibliotecas:

- `requests` (para obtener las preguntas desde la API)
- `tkinter` (incluido en la instalación estándar de Python)

Puedes instalar las dependencias necesarias con:

```bash
pip install requests
```

## Estructura del Proyecto

Quizzler/
│── data.py             # Obtiene las preguntas desde OpenTDB
│── main.py             # Punto de entrada principal del programa
│── question_model.py   # Define la clase Question
│── quiz_brain.py       # Lógica del juego y gestión de preguntas
│── ui.py               # Interfaz gráfica del juego con Tkinter
│── images/             # Contiene imágenes para los botones

## Explicación de Archivos

**data.py**: Hace una solicitud a la API de OpenTDB y obtiene una lista de preguntas.

**main.py**: Gestiona la creación del cuestionario y la interfaz de usuario.

**question_model.py**: Define la clase Question para almacenar preguntas y respuestas.

**quiz_brain.py**: Contiene la lógica del cuestionario, como verificar respuestas y gestionar el puntaje.

**ui.py**: Maneja la interfaz gráfica del usuario con Tkinter, mostrando preguntas y registrando respuestas.

**images/**: Carpeta que contiene las imágenes true.png y false.png utilizadas en los botones de la interfaz gráfica.

**Captura de Pantalla:**

<img width="349" alt="image" src="https://github.com/user-attachments/assets/d9f0edd4-6dc0-4004-9235-4d0e7021b463" />


## Créditos

Este proyecto fue desarrollado con fines educativos, con el objetivo de aprender a manejar APIs, estructurar la lógica de un juego y crear una interfaz gráfica interactiva con Tkinter. Durante el desarrollo, puse en práctica conceptos como el consumo de datos desde una API externa, la manipulación de preguntas y respuestas, y la integración de una interfaz visual que mejora la experiencia del usuario.

## Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

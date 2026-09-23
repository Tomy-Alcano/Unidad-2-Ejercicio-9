# Unidad-2-Ejercicio-9
Programacion 3 Unidad 2 Ejercicio 9
Ejercicio 9 — Formulario con validación de campos
Este ejercicio integra layouts y eventos para construir un formulario que valide los datos ingresados antes de permitir al usuario continuar. La validación de formularios es una de las tareas más comunes en el desarrollo de aplicaciones reales.

Construí una ventana con un formulario de alta de producto que contenga:

Etiqueta y campo de texto para Nombre del producto
Etiqueta y campo de texto para Precio (solo debe aceptar valores numéricos)
Etiqueta y campo de texto para Stock inicial (solo debe aceptar valores enteros positivos)
Etiqueta y JComboBox para Categoría, con las opciones: Electrónica, Ropa, Alimentos, Hogar, Otros
Un botón con el texto "Agregar producto"
Una etiqueta de mensaje que inicialmente esté vacía
Cuando el usuario presione el botón "Agregar producto", la aplicación debe validar que:

Ningún campo de texto esté vacío
El precio sea un número válido mayor a cero
El stock sea un número entero mayor o igual a cero
Si alguna validación falla, la etiqueta de mensaje debe mostrar en rojo cuál es el error. Si todos los datos son válidos, debe mostrar en verde: "Producto agregado correctamente."

💡 Tip: para manejar la posibilidad de que el usuario ingrese texto en lugar de un número en los campos numéricos, usá un bloque try-catch con NumberFormatException al momento de convertir el valor.
<img width="733" height="487" alt="Captura de pantalla 2026-09-23 193038" src="https://github.com/user-attachments/assets/8ecd31ac-8f36-406f-afe3-cc1f61b279bd" />

<img width="736" height="495" alt="image" src="https://github.com/user-attachments/assets/652acfb8-2ece-4133-ba4a-c38261da6599" />

<img width="736" height="497" alt="image" src="https://github.com/user-attachments/assets/515e188b-0fbc-4026-bf30-464617753abf" />

<img width="737" height="495" alt="image" src="https://github.com/user-attachments/assets/9989b760-6e9c-439c-a99b-a49fb21b1c24" />

<img width="740" height="497" alt="image" src="https://github.com/user-attachments/assets/580ff8c3-7809-4f14-882a-d40cc27d69d2" />


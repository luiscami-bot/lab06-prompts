# Bitacora de prompts
 
Laboratorio 06: Fundamentos de Ingenieria de Prompts.
 
Herramienta de IA usada: ChatGPT
 
## Ejercicio 2: Tokens y ventana de contexto
| Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. | 33 | 7 |
| The students program in Java. | 28 | 6 |
| desafortunadamente | 18 | 4 |
## Ejercicio 3: Temperatura
| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 |100.0% |Bibliotec , LibroYa , PrestaLibro , LectoGO , PaginaLibre , NubeDeTinta |
| 0.5 |65.3% |Bibliotec , LibroYa , PrestaLibro , LectoGO , PaginaLibre , NubeDeTinta|
| 1 |44.5% |Bibliotec , LibroYa , PrestaLibro , LectoGO , PaginaLibre , NubeDeTinta |
| 1.8 |32.2% |Bibliotec , LibroYa , PrestaLibro , LectoGO , PaginaLibre , NubeDeTinta |

Cuando sube la temperatura el % cambia 
|
La computadora solo realiza lo que le pido

 
## Ejercicio 4: Prompt vago vs estructurado
| Criterio                            | Prompt vago | Prompt estructurado |
| ----------------------------------- | ----------- | ------------------- |
| Menciona el objetivo del sistema    | Sí          | Sí                  |
| Menciona a los usuarios principales | No          | Sí                  |
| Tiene exactamente 3 funcionalidades | No          | Sí                  |
| Está en 3 párrafos                  | No          | Sí                  |
| Lo usaría en un informe real        | Sí          | Sí                  |


 
## Ejercicio 5: Anatomia de un prompt
| Componente      | Texto de mi prompt                                                                                                                                                                                                                                        | Qué cambió en la respuesta                                                                                                 |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **Rol**         | Crea un programa en Java.                                                                                                                                                                                                                                 | Se define el papel del modelo como desarrollador Java.                                                                     |
| **Instrucción** | Actua como desarrollador Java. Crea un programa en Java.                                                                                                                                                                                                  | Se agrega una instrucción más específica: actuar como desarrollador Java y crear el programa.                              |
| **Contexto**    | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda.                                                                                                                                                       | Se especifica el contexto y objetivo del programa: gestionar los productos de una tienda.                                  |
| **Ejemplo**     | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda usando una clase Producto con los atributos codigo, nombre, precio y stock.                                                                            | Se agrega un ejemplo concreto de la estructura que debe tener el programa, incluyendo la clase `Producto` y sus atributos. |
| **Formato**     | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda usando una clase Producto con los atributos codigo, nombre, precio y stock. Explica primero la estructura de la clase y luego presenta el codigo Java. | Se indica cómo debe organizarse la respuesta: primero explicar la estructura de la clase y después mostrar el código Java. |


 
## Ejercicio 6: Del prompt basico al profesional
| **Qué revisar** | **Cumple (Sí / No)** |
|---|---|
| ¿Está escrito en Java y usa Swing? | Si|
| ¿Pide correo y contraseña? | Si|
| ¿Explica el funcionamiento antes o después del código? |Si |
| ¿El código está organizado en clases? | Si|
| ¿Valida los datos que ingresa el usuario? |Si |

Prompt:

Actúa como desarrollador Java. Crea un ejemplo de login para una aplicación de escritorio utilizando Swing. El usuario debe ingresar correo y contraseña. Explica brevemente el funcionamiento y presenta el código organizado por clases.

Mejora el código anterior con estas restricciones: no uses librerías externas, valida que el correo contenga @ y que la contraseña tenga al menos 8 caracteres, y muestra los mensajes con JOptionPane.
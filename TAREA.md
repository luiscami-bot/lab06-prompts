# Tarea: Mi prompt profesional

## Funcionalidad elegida

**Pokédex**

La funcionalidad consiste en crear una Pokédex sencilla que permita consultar información básica de un Pokémon, como su número, nombre, tipo y nivel.

## Versión 1: prompt básico

```text
Crea una Pokédex en Java.
```

### ¿Qué cambié?

En esta primera versión solamente indiqué que quería crear una Pokédex utilizando Java.

### ¿Por qué?

Quise comenzar con un prompt básico para comprobar qué resultado obtenía sin proporcionar muchos detalles.

### ¿Qué mejoró en la respuesta?

La respuesta propuso una Pokédex básica, pero era muy general. No especificaba qué información debía mostrar ni cómo debía organizarse el programa.

## Versión 2

```text
Crea una Pokédex en Java que permita registrar y consultar Pokémon. Cada Pokémon debe tener número, nombre, tipo y nivel. El programa debe permitir ingresar los datos y mostrar la información de los Pokémon registrados.
```

### ¿Qué cambié?

Agregué las características que debe tener cada Pokémon y las principales funciones que debe realizar el programa.

### ¿Por qué?

El primer prompt no proporcionaba suficiente información para saber cómo debía funcionar la Pokédex.

### ¿Qué mejoró en la respuesta?

La respuesta fue más específica porque ya indicaba los datos de cada Pokémon y las acciones principales que debía realizar el programa. Sin embargo, todavía faltaba definir el formato y algunas restricciones.

## Versión 3: prompt final

```text
ROL:
Actúa como un desarrollador de software especializado en Java y explica la solución de manera sencilla para un estudiante que está aprendiendo programación.

INSTRUCCIÓN:
Crea una Pokédex sencilla en Java que permita registrar y consultar Pokémon. El programa debe permitir ingresar el número, nombre, tipo y nivel de cada Pokémon. También debe mostrar los datos de los Pokémon registrados.

CONTEXTO:
La Pokédex será desarrollada como una práctica académica de programación orientada a objetos. Se busca una solución sencilla y fácil de entender para un estudiante.

EJEMPLO:
Ejemplo de un Pokémon registrado:
Número: 25
Nombre: Pikachu
Tipo: Eléctrico
Nivel: 20

Al consultar el Pokémon, el programa debe mostrar sus datos.

FORMATO:
Entrega la respuesta en este orden:
1. Código Java completo.
2. Explicación breve del funcionamiento.
3. Ejemplo de ejecución de la Pokédex.

RESTRICCIONES:
- No uses librerías externas.
- Utiliza únicamente características básicas de Java.
- No agregues funcionalidades que no hayan sido solicitadas.
- Mantén el código sencillo y fácil de comprender.
```

### ¿Qué cambié?

Agregué los cinco componentes de un prompt profesional: rol, instrucción, contexto, ejemplo y formato. También agregué restricciones para controlar mejor la respuesta.

### ¿Por qué?

Quería que la respuesta fuera más específica y evitar que se agregaran funcionalidades o información que no había solicitado.

### ¿Qué mejoró en la respuesta?

La respuesta final fue más ordenada y precisa. La solución se enfocó en una Pokédex sencilla, utilizando Java básico y mostrando claramente los datos de cada Pokémon.

## Componentes del prompt final

| Componente  | ¿Dónde aparece?                                               |
| ----------- | ------------------------------------------------------------- |
| Rol         | Actúa como un desarrollador de software especializado en Java |
| Instrucción | Crea una Pokédex sencilla en Java                             |
| Contexto    | La Pokédex será desarrollada como una práctica académica      |
| Ejemplos    | Ejemplo de Pikachu con sus datos                              |
| Formato     | Código, explicación y ejemplo de ejecución                    |

## Evaluación del resultado

| Criterio                                 | Resultado |
| ---------------------------------------- | --------- |
| Está desarrollado en Java                | Sí        |
| Permite registrar Pokémon                | Sí        |
| Permite consultar Pokémon                | Sí        |
| Muestra número, nombre, tipo y nivel     | Sí        |
| Incluye explicación del código           | Sí        |
| Utiliza librerías externas               | No        |
| El código es adecuado para un estudiante | Sí        |

## Errores que evité

### 1. Ser demasiado general

En la primera versión solamente indiqué "Crea una Pokédex en Java". Para evitar este error, agregué en las siguientes versiones los datos que debe tener cada Pokémon y las funciones que debe realizar el programa.

### 2. No indicar el formato

En las primeras versiones no indiqué cómo quería recibir la respuesta. En la versión final especifiqué que primero debía aparecer el código, después una explicación breve y finalmente un ejemplo de ejecución.

## Conclusión

Al realizar las tres versiones del prompt pude observar cómo agregar información específica mejora la respuesta obtenida. La versión final contiene rol, instrucción, contexto, ejemplo y formato, además de restricciones, logrando una solicitud más clara y precisa para desarrollar una Pokédex en Java.


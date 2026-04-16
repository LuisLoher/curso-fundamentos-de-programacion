# 🐍 Curso: Python desde Cero para Análisis de Datos

#### Bienvenidx al repositorio oficial del curso impartido por Luis Loher.

👨‍💻 Modalidad: En línea (Google Meet)     
🕙 Horario: 9-10 pm (México)   
⏳ Duración: 3 meses   
🎯 Nivel: Principiantes absolutos   
📃 Certificado  

📝 Formulario de Inscripción [Enlace](https://forms.gle/nbmyjGGiVyjwoYtb7)   
🤝 Grupo de WhatsApp del Curso: [Enlace](https://chat.whatsapp.com/CRsOAtI2PzsJELa6JMK0HC)   
🤝 Grupo de WhatsApp sobre Análisis de Datos: [Enlace](https://chat.whatsapp.com/E0rW2PSjzBs6saGvV2RWYS)

## 🚀 ¿Por qué aprender a programar?

- Desarrolla pensamiento lógico
- Mejora tu capacidad para resolver problemas
- Es una habilidad altamente demandada
- Te permite crear tus propias herramientas
- Es el lenguaje de hoy y del futuro

## 📚 Evaluación

- Asistencia
- Participación en clase
- Ejercicios para casa
- Proyectos finales

## ⚡ Regla de oro

Si algo no entiendes: pregunta.

## 🛠️ Requisitos Previos
Ninguno.

## 📅 Cronograma de Temas

### Parte 1. Los Fundamentos
Esta semana nos enfocamos en construir los cimientos de la lógica de programación.

- [Clase 1: Algoritmo](#-clase-1-algoritmo)
- [Clase 2: Pseudocódigo](#-clase-2-pseudocódigo)
- [Clase 3: Diagramas de Flujo](#-clase-3-diagramas-de-flujo)

### Parte 2. Los Fundamentos
Semana en donde vemos el entorno de trabajo y aprendemos a crear nuestros primeros programas.

- [Clase 4: Tu primer contacto con Python en Colab](#-clase-4-tu-primer-contacto-con-python-en-colab)
- [Clase 5: Comentarios, Variables e Imprimir](#-clase-5-comentarios-variables-e-imprimir)
- [Clase 6: Más sobre Variables e Imprimir, y Guardar](#-clase-6-más-sobre-variables-e-imprimir-y-guardar)
- [Clase 7: Operaciones Matemáticas]()

---
# 🎉 Hoy es el Inicio de tu camino en la Programación

## ✍ Clase 1: Algoritmo

> Un **algoritmo** es una serie de pasos ordenados para resolver un problema.

Imagina que es una *receta* de cocina: si sigues los pasos en el orden correcto, obtienes el resultado esperado.

**Ejemplo 1:** Algortimo para lavarse los dientes.

1. Tomar cepillo
1. Poner pasta
1. Cepillar
1. Enjuagar

**Ejemplo 2:** Algoritmo para preparar un café.

**Ejercicio 1:** Algoritmo para cambiar una llanta.

### ¿Qué es programar?

> Programar es dar instrucciones claras y ordenadas a una computadora para resolver un problema.

Una computadora es muy rápida…
pero necesita instrucciones exactas.

## ✍ Clase 2: Pseudocódigo

> El **pseudocódigo** es una forma de escribir los pasos de un programa utilizando nuestro propio lenguaje pero siguiendo la estructura de la programación.

No es un lenguaje real/formal.  
Es una herramienta para pensar/acomodar ideas.

Sirve para planear la lógica de un algoritmo sin preocuparse por las reglas técnicas o la sintaxis complicada de lenguajes como Python, C++ o Java.

**Ejemplo 1:** Pseudocódigo para pedir el nombre del usuario y mostrar un saludo.

<pre>
Inicio
    Escribir "Introduce tu nombre:"
    Guardar nombre
    Escribir "¡Hola nombre bienvenidx!"
Fin
</pre>

---

**Ejemplo 2:** Pseudocódigo para solicitar dos valores, sumarlos y mostrar el resultado.

<pre>
Inicio
    Escribir "Primer número:"
    Guardar n1
    Escribir "Segundo número:"
    Guardar n2
    resultado <- n1 + n2
    Escribir "La suma es: resultado"
Fin
</pre>

---

**Ejemplo 3:** Pseudocódigo para validar mayoría de edad (la edad ingresada con el valor 18).

<pre>
Inicio
    Escribir "Dime tu edad:"
    Guardar edad
    Si edad >= 18 Entonces
        Escribir "Eres mayor de edad."
    Sino
        Escribir "Eres menor de edad."
    FinSi
Fin
</pre>

---

### Ejercicios

**Ejercicio 1:** Pseudocódigo para encontrar el área de un triángulo.

**Ejercicio 2:** Pseudocódigo para verificar si el resto de dividir el número entre 2 es cero.

**Ejercicio 3:** Pseudocódigo para iniciar una variable en 1 e incrementarla hasta llegar a 10.

---

### Ejercicios para Casa

**Ejercicio 1:** Pseudocódigo para recibir un número y multiplicarlo por los índices del 1 al 10.

**Ejercicio 2:** Pseudocódigo para sumar números ingresados por el usuario hasta que introduzca un cero.

**Ejercicio 3:** Pseudocódigo para sumar N cantidad de notas y dividir el total entre N.

**Ejercicio extra:** Pseudocódigo para comparar cada número nuevo con un valor "máximo" guardado y actualizarlo si el nuevo es mayor.

---

## ✍ Clase 3: Diagramas de Flujo

> Un **diagrama de flujo** es un dibujo que muestra los pasos de un proceso de principio a fin. 

Imaginalo como un "mapa del tesoro" para resolver un problema o completar una tarea.

### Símbolos Básicos
Para que todos entiendan lo mismo, usamos figuras específicas para cada tipo de acción:

- **Óvalo (Inicio/Fin):** Indica dónde empieza y dónde termina el camino.

- **Rectángulo (Proceso):** Representa una acción o instrucción simple (ej. "Lavar los platos").

- **Rombo (Decisión):** Es una pregunta que se responde con Sí o No. Aquí el camino se divide.

- **Flechas (Flujo):** Conectan las figuras y te dicen hacia dónde ir después.

---

**Ejemplo 1: ¿Funciona la lámpara?**

Este es el ejemplo clásico para entender cómo la lógica de un diagrama nos ayuda a tomar decisiones:

1. **Inicio:** Encuentras una lámpara que no enciende.

1. **Decisión:** ¿Está enchufada?

   - **No:** Enchúfala.

   - **Sí:** Pasa a la siguiente pregunta.

1. **Decisión:** ¿Está quemada la ampolleta/foco?

   - **Sí:** Cámbiala.

   - **No:** Compra una lámpara nueva.

1. **Fin.**

---

### ¿Para qué sirve?

- **Claridad:** Ayuda a ver pasos que quizás habías olvidado.

- **Orden:** Evita que hagas el paso 3 antes que el paso 1.

- **Comunicación:** Es mucho más fácil mostrar un dibujo a un equipo que explicar un manual de 10 páginas.

---

### Consejos para crearlos
- **Sigue una dirección:** Normalmente se dibujan de arriba hacia abajo o de izquierda a derecha.

- **Sé breve:** Usa frases cortas dentro de las figuras.

- **Evita el desorden:** Intenta que las flechas no se crucen demasiado entre sí.

---
---

### Ejercicios

#### **1. Preparar una taza de café**

Este es un proceso **lineal** (paso a paso).

- **Inicio**

- **Proceso:** Poner café en la taza.

- **Proceso:** Calentar agua.

- **Proceso:** Verter agua en la taza.

- **Fin**

#### **2. Cruzar la calle**

Aquí introducimos una **decisión** basada en la seguridad.

- **Inicio**

- **Proceso:** Llegar a la esquina.

- **Decisión:** ¿El semáforo está en verde?

   - **No:** Esperar. (Vuelve a la pregunta).

   - **Sí:** Cruzar la calle.

- **Fin**

#### **3. ¿El número es par o impar?**

Un ejemplo clásico de **matemática y lógica.**

- **Inicio**

- **Proceso:** Leer el número (ej. el 7).

- **Decisión:** ¿El número es divisible entre 2?

   - **Sí:** Mostrar "Es Par".

   - **No:** Mostrar "Es Impar".

- **Fin**

### Ejercicios para Casa

> //Se los debo aún jejeje.

--

## ✍ Clase 4: Tu primer contacto con Python en Colab

> ¡Bienvenidx a tu primera clase **programando con Python**!


**Google Colaboratory** es un entorno idóneo para empezar, no necesitas instalar nada: todo se hace en tu navegador.

Y usas los recursos de las computadoras de Google.

### Colab

[Enlace directo a Colab](https://colab.research.google.com)

**Buenas Prácticas:**
1. Darle un nombre al archivo
1. Conectarse al back de Google

**Código Final de la Clase 4:** 

```
# Variables (guardamos información)
nombre = "Luis"          # texto → tipo string (str)
edad = 30                # número entero → tipo int
altura = 1.75            # número con decimal → tipo float
es_estudiante = True     # verdadero/falso → tipo bool

print("Nombre:", nombre)
print("Edad:", edad)
print("Altura:", altura)
print("¿Es estudiante?", es_estudiante).
```

## ✍ Clase 5: Comentarios, Variables e Imprimir

## Abre un cuaderno en **Google Colab.** 

[Enlace directo a Colab](https://colab.research.google.com)

**Buenas Prácticas:**
1. Darle un nombre al archivo
1. Conectarse al back de Google

---

### Código Inicial

**Comentario**

Todo lo que va después de un **#** hasta el final de la línea es considerado un comentario y es ignorado totalmente por el intérprete. 


```
# Esto es un comentario y se ignora completamente.

print("Hola")   # Esto también es un comentario.

""" 
Esto es un comentario multilínea
y también es ignorado como código ejecutable.
"""
```

---

**Variable**

> Una **variable** es un nombre que usas para guardar un valor y poder usarlo después.

Una variable es como una caja donde guardas un valor.
Tú le pones un nombre a esa caja, y dentro puedes guardar información (un número, un texto, una lista, etc.).

**Ejmplos**
```
nombre = "Luis"          # guarda un texto
edad = 36                # guarda un número
altura = 1.82            # guarda un número decimal
esta_estudiando = True   # guarda Verdadero o Falso
```
**Cómo funciona:**

A la izquierda pones el nombre de la variable.
A la derecha pones el valor que quieres guardar.
El signo **=** significa: "guarda esto dentro de esta caja".

**Reglas básicas de nombres de variables:**

- Debe empezar con letra o guión bajo (_).
- Solo puede tener letras, números y guiones bajos.
- No puede tener espacios ni caracteres especiales (¡@#$/ etc.).
- Python distingue mayúsculas de minúsculas (Edad es diferente a edad).

**Ejemplos buenos:**

- nombre
- edad_usuario
- usuario8

**Ejemplos malos:**

- 2edad (no puede empezar con número)
- mi nombre (no puede tener espacio)
- total$ (no puede tener $)

---

**Imprimir en pantalla (print)** 
```
print("Hola mundo")
print("Mi nombre es Luis")
print("Tengo", 25, "años")   # puedes mezclar texto y números
```

## ✍ Clase 6: Más sobre Variables e Imprimir, y Guardar

Abre un cuaderno en **Google Colab**. 

[Enlace directo a Colab](https://colab.research.google.com)

Buenas prácticas: 
1. Ponerle nombre al archivo.
1. Conectarse al back de Google.

---

### Tipos de Datos Iniciales en Python

En Python tenemos diferentes tipos de datos.   
Cada uno sirve para guardar un tipo de información distinta:   
- Números (int y float)
- Textos (str)
- Verdadero o falso (bool)
- Estructuras para guardar varios datos juntos (list, tuple, dict, set)
  
---  
 ### Tipos de Datos más importantes (Primera clase)

| Tipo de dato     | Nombre en Python | Descripción                              | Ejemplo                              |
|------------------|------------------|------------------------------------------|--------------------------------------|
| Entero           | `int`            | Números sin decimales                    | `5`, `42`, `-10`                     |
| Decimal          | `float`          | Números con decimales                    | `3.14`, `0.5`, `-2.75`               |
| Texto            | `str`            | Cadenas de texto                         | `"Hola"`, `'Python'`                 |
| Booleano         | `bool`           | Verdadero o Falso                        | `True`, `False`                      |
| Lista            | `list`           | Colección ordenada de elementos          | `[1, 2, 3]`, `["manzana", "pera"]`  |

---

### Guardar información del usuario

> Para **guardar** la información que ingrese el usuario se usa la función **input()**
```
nombre = input("¿Cómo te llamas? ")
edad = input("¿Cuántos años tienes? ")

print("Bienvenido", nombre, "ahora sabemos que tienes", edad, "años")
```

**Importante:**

**input()** siempre guarda el dato como texto (string).
Si quieres un número, conviértelo:

```
edad = int(input("¿Cuántos años tienes? "))   # convierte a número entero
altura = float(input("¿Cuánto mides? "))      # convierte a número decimal
```

### Operadores Aritméticos en Python

| Operador | Nombre                  | Ejemplo          | Resultado    |
|----------|-------------------------|------------------|--------------|
| `+`      | Suma                    | `5 + 3`          | `8`          |
| `-`      | Resta                   | `10 - 4`         | `6`          |
| `*`      | Multiplicación          | `6 * 7`          | `42`         |
| `/`      | División                | `10 / 2`         | `5.0`        |
| `//`     | División entera         | `10 // 3`        | `3`          |
| `%`      | Módulo (resto)          | `10 % 3`         | `1`          |
| `**`     | Potencia (exponente)    | `2 ** 3`         | `8`          |


---

**Ejemplos**

**Ejercicios en vivo**

**Ejercicios para casa**

---

## ✍ Clase 7: Operaciones Matemáticas

### Tipos de Datos en Python (versión 2)

| Tipo de dato     | Nombre en Python | Descripción                              | Ejemplo                              |
|------------------|------------------|------------------------------------------|--------------------------------------|
| Entero           | `int`            | Números sin decimales                    | `5`, `42`, `-10`                     |
| Decimal          | `float`          | Números con decimales                    | `3.14`, `0.5`, `-2.75`               |
| Texto            | `str`            | Cadenas de texto                         | `"Hola"`, `'Python'`, `"123"`        |
| Booleano         | `bool`           | Verdadero o Falso                        | `True`, `False`                      |
| Lista            | `list`           | Colección ordenada de elementos          | `[1, 2, 3]`, `["manzana", "pera"]`  |
| Tupla            | `tuple`          | Colección ordenada que no se puede cambiar | `(1, 2, 3)`                          |
| Diccionario      | `dict`           | Datos en forma de clave y valor          | `{"nombre": "Luis", "edad": 25}`     |
| Conjunto         | `set`            | Colección de elementos únicos            | `{"rojo", "azul", "verde"}`          |


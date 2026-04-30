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

### Parte 1. Los Fundamentos de la Programación

En esta parte, nos enfocamos en construir los cimientos de la lógica de programación.

- [Clase 1: Algoritmo](#-clase-1-algoritmo)
- [Clase 2: Pseudocódigo](#-clase-2-pseudocódigo)
- [Clase 3: Diagramas de Flujo](#-clase-3-diagramas-de-flujo)

### Parte 2. Los Fundamentos del Lenguaje Python
Parte, en donde vemos el entorno de trabajo y aprendemos a crear nuestros primeros programas.

- [Clase 4: Tu primer contacto con Python en Colab](#-clase-4-tu-primer-contacto-con-python-en-colab)
- [Clase 5: Comentarios, Variables e Imprimir](#-clase-5-comentarios-variables-e-imprimir)
- [Clase 6: Más sobre Variables e Imprimir, y Guardar](#-clase-6-más-sobre-variables-e-imprimir-y-guardar)
- [Clase 7: Operadores de Comparación, Lógicos y de Asignación](#-clase-7-operadores-de-comparación-lógicos-y-de-asignación)
- [Clase 8: Introducción a la Toma de Decisiones](#-clase-8-introducción-a-la-toma-de-decisiones)
- [Clase 9: Toma de Decisiones (Condicionales)](#-clase-9-condicionales-y-blucle-for)
- [Clase 10: Más sobre el blucle for](#-clase-10-más-sobre-el-blucle-for)

### Parte 3. Los Fundamentos del Lenguaje Python
Lista de ejercicios diseñada para reforzar los temas del curso: desde la lógica pura hasta la implementación en Python.

- [Clase 11: Ejercicios de Fundamentos de Programación y Python](#-clase-11-ejercicios-de-fundamentos-de-programación-y-python)

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

**Ejercicio 1:** Algoritmo para preparar un café.

**Ejercicio para Casa:** Algoritmo para cambiar una llanta.

### ¿Qué es programar?

> Programar es dar instrucciones claras y ordenadas a una computadora para resolver un problema.

Una computadora es muy rápida… pero necesita instrucciones exactas.

---

## ✍ Clase 2: Pseudocódigo

> El **pseudocódigo**, es una forma de escribir los pasos de un programa utilizando nuestro propio lenguaje, pero siguiendo la estructura de la programación.

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

---

### Ejercicios para Casa

**Ejercicio 1:** Pseudocódigo para iniciar una variable en 1 e incrementarla hasta llegar a 10.

**Ejercicio 2:** Pseudocódigo para sumar números ingresados por el usuario hasta que introduzca un cero.

**Ejercicio 3:** Pseudocódigo para sumar N cantidad de notas y dividir el total entre N.

--- 

## ✍ Clase 3: Diagramas de Flujo

> Un **diagrama de flujo** es un dibujo que muestra los pasos de un proceso de principio a fin. 

> Los diagramas de flujo son representaciones visuales de un algoritmo. Utilizan figuras geométricas para indicar el tipo de acción y flechas para marcar el orden de ejecución.

Imaginalo como un "mapa del tesoro" para resolver un problema o completar una tarea.

### Símbolos Básicos

Para que todos entiendan lo mismo, usamos figuras específicas para cada tipo de acción:

- **Óvalo (Inicio/Fin):** Indica dónde empieza y dónde termina el camino.

- **Rectángulo (Proceso):** Representa una acción o instrucción simple (ej. "Lavar los platos").

- **Rombo (Decisión):** Es una pregunta que se responde con Sí o No. Aquí el camino se divide.

- **Flechas (Flujo):** Conectan las figuras y te dicen hacia dónde ir después.

---

**Ejemplo 1: Diagrama de flujo para utilizar una lámpara.**

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

### ¿Para qué sirven los Diagramas de Flujo?

- **Claridad:** Ayuda a ver pasos que quizás habías olvidado.

- **Orden:** Evita que hagas el paso 3 antes que el paso 1.

- **Comunicación:** Es mucho más fácil mostrar un dibujo a un equipo que explicar un manual de 10 páginas.

---

### Consejos para crearlos

- **Sigue una dirección:** Normalmente se dibujan de arriba hacia abajo o de izquierda a derecha.

- **Sé breve:** Usa frases cortas dentro de las figuras.

- **Evita el desorden:** Intenta que las flechas no se crucen demasiado entre sí.

---

**Ejemplo 2: Diagrama de Flujo para preparar una taza de café.**

Este es un proceso **lineal** (paso a paso).

1. **Inicio**

1. **Proceso:** Poner café en la taza.

1. **Proceso:** Calentar agua.

1. **Proceso:** Verter agua en la taza.

1. **Fin**

---

**Ejemplo 3: Diagrama de Flujo para Cruzar la calle.**

Aquí introducimos una **decisión** basada en la seguridad.

- **Inicio**

- **Proceso:** Llegar a la esquina.

- **Decisión:** ¿El semáforo está en verde?

   - **No:** Esperar. (Vuelve a la pregunta).

   - **Sí:** Cruzar la calle.

- **Fin**

---

**Ejemplo 4: Diagrama de Flujo para saber si un número es par o impar.**

1. **Inicio**

1. **Proceso:** Leer el número (ej. el 7).

1. **Decisión:** ¿El número es divisible entre 2?

   - **Sí:** Mostrar "Es Par".

   - **No:** Mostrar "Es Impar".

1. **Fin**

### Ejercicios para Casa

**Ejercicio 1: Diagrama de Flujo para, dado el promedio de un alumno, determinar si aprobó (calificación mayor o igual a 6).**

**Ejercicio 2: Diagrama de Flujo para comparar dos números distintos y decir cuál es el más grande.**

**Ejercicio 3: Diagrama de Flujo para calcular el factorial de un número (multiplicar un número por todos los anteriores hasta el 1).**

**Ejercicio 4: Diagrama de Flujo para leer los tres lados de un triángulo y determinar si es Equilátero (3 iguales), Isósceles (2 iguales) o Escaleno (todos distintos).**

---

## ✍ Clase 4: Tu primer contacto con Python en Colab

> ¡Bienvenidx a tu primera clase **programando con Python.**!

**Google Colaboratory** es un entorno idóneo para empezar, no necesitas instalar nada: todo se hace en tu navegador.

Y usas los recursos de las computadoras de Google.

### Colab

[Enlace directo a Colab](https://colab.research.google.com)

**Buenas Prácticas:**
1. Darle un nombre al archivo.
1. Conectarse al back de Google.

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

### Ejercicios para Casa

**Ejercicio 1: blablabla**

---

## ✍ Clase 5: Comentarios, Variables e Imprimir

## Abre un cuaderno en **Google Colab.** 

[Enlace directo a Colab](https://colab.research.google.com)

**Buenas Prácticas:**
1. Darle un nombre al archivo.
1. Conectarse al back de Google.

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

### Ejercicios para Casa

**Ejercicio 1: ........**

---

## ✍ Clase 6: Más sobre Variables e Imprimir, y Guardar

Abre un cuaderno en **Google Colab**. 

[Enlace directo a Colab](https://colab.research.google.com)

**Buenas prácticas:** 
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

> Para **guardar** la información que ingrese el usuario se usa la función **input().**
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

### Ejercicios para Casa

**Ejercicio 1: ........**

---

## ✍ Clase 7: Operadores de Comparación, Lógicos y de Asignación

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

---

### Tarea

T1: Estudia las definiciones de cada tipo de dato.

---

### Operadores de Comparación

Sirven para comparar valores.  
El resultado siempre será:

- `True` = Verdadero  
- `False` = Falso

---

#### Tabla de Operadores de Comparación

| Operador | Significado | Ejemplo |
|---------|------------|--------|
| `==` | Igual que | `5 == 5` |
| `!=` | Diferente de | `5 != 3` |
| `>` | Mayor que | `8 > 2` |
| `<` | Menor que | `2 < 8` |
| `>=` | Mayor o igual | `7 >= 7` |
| `<=` | Menor o igual | `4 <= 9` |

---

### Ejemplos

```
print(5 == 5)   # True

print(10 != 3)   # True

print(8 > 20)   # False

print(15 <= 15)   # True

edad = 18
print(edad >= 18)   # True

```

---

### Tabla de Operadores Lógicos en Python

Sirven para unir condiciones.

| Operador | Significado | Ejemplo | Resultado |
|---------|------------|--------|----------|
| `and` | Verdadero si ambas condiciones se cumplen | `5 > 2 and 8 > 3` | `True` |
| `and` | Falso si una condición no se cumple | `5 > 2 and 8 < 3` | `False` |
| `or` | Verdadero si al menos una se cumple | `5 > 2 or 8 < 3` | `True` |
| `or` | Falso si ninguna se cumple | `1 > 5 or 8 < 3` | `False` |
| `not` | Invierte el resultado | `not 5 > 2` | `False` |
| `not` | Invierte el resultado | `not 3 > 8` | `True` |

---

### Ejemplos

```
print(5 > 2 and 10 > 3)

print(5 > 2 and 10 < 3)

print(8 < 2 or 10 > 5)

print(1 > 5 or 2 > 9)

print(not 5 > 2)

edad = 22
print(edad >= 18 and edad <= 30)

```

### Tabla de Operadores de Asignación en Python

Sirven para guardar o modificar valores.

| Operador | Descripción | Ejemplo | Equivale a |
|---------|-------------|--------|-----------|
| `=` | Asigna un valor | `x = 5` | `x = 5` |
| `+=` | Suma y asigna | `x += 3` | `x = x + 3` |
| `-=` | Resta y asigna | `x -= 2` | `x = x - 2` |
| `*=` | Multiplica y asigna | `x *= 4` | `x = x * 4` |
| `/=` | Divide y asigna | `x /= 2` | `x = x / 2` |
| `//=` | División entera y asigna | `x //= 3` | `x = x // 3` |
| `%=` | Módulo y asigna | `x %= 2` | `x = x % 2` |
| `**=` | Potencia y asigna | `x **= 3` | `x = x ** 3` |

---

### Ejemplos

```
x = 10
x += 5
print(x)

x = 20
x -= 8
print(x)

x = 4
x *= 3
print(x)

x = 16
x /= 4
print(x)

saldo = 100
saldo += 50
saldo -= 20
print(saldo)

```

---

### Ejercicios en Vivo

Compartir captura de pantalla en el grupo.

---

**Ejercicio 1**
```
a = 8
b = 3

print(a > b)
print(a == b)
print(a < b)
```

---

**Ejercicio 2**
```
edad = 25

print(edad >= 18 and edad < 60)
```

---

**Ejercicio 3**
```
puntos = 10
puntos += 5
puntos *= 2

print(puntos)
```

---

### Tarea

Recuerda, se sube al formulario durante la clase en vivo.

T2: Son los siguientes 4 ejercicios:

```
print(7 != 7)
print(10 > 3 and 2 < 5)
print(not 8 < 3)

x = 50
x -= 10
print(x)
```

---

## ✍ Clase 8: Introducción a la Toma de Decisiones

🎯 **Objetivo de la clase**   
Aprender a usar condicionales para que un programa **tome decisiones** según una condición.

---

### 📌 ¿Qué es un condicional?

> Un condicional permite ejecutar código **solo si algo se cumple**.

**Ejemplo cotidiano:**

- Si llueve → llevo paraguas ☔  
- Si tengo hambre → como 🍔  
- Si apruebo → celebro 🎉

**En Python usamos:**

```python
if
elif
else
````

---

### 1. Estructura básica: `if`

```python
edad = 18

if edad >= 18:
    print("Eres mayor de edad")
```

### Explicación:

* `if` significa **si**
* `edad >= 18` es la condición
* Si es verdadera, se ejecuta el `print()`

---

### Resultado:

```python
Eres mayor de edad
```

---

### 2. Importancia de la indentación

**Python usa espacios o tabulación para indicar bloques.**

✅ Correcto:

```python
if 5 > 2:
    print("Sí se cumple")
```

❌ Incorrecto:

```python
if 5 > 2:
print("Error")
```

---

### 3. Uso de `else`

`else` significa: **si no se cumple lo anterior**

```python
edad = 16

if edad >= 18:
    print("Mayor de edad")
else:
    print("Menor de edad")
```

---

### Resultado:

```python
Menor de edad
```

---

### 4. Uso de `elif`

Significa: **si no, pero si...**

```python
calificacion = 8

if calificacion == 10:
    print("Excelente")
elif calificacion >= 7:
    print("Aprobado")
else:
    print("Reprobado")
```

---

### Resultado:

```python
Aprobado
```

---

### 5. Ejemplos sencillos

**Ejemplo 1**

```python
numero = 5

if numero > 0:
    print("Número positivo")
```

---

**Ejemplo 2**

```python
temperatura = 35

if temperatura > 30:
    print("Hace calor")
else:
    print("Clima agradable")
```

---

**Ejemplo 3**

```python
saldo = 100

if saldo >= 50:
    print("Compra permitida")
else:
    print("Saldo insuficiente")
```

---

### 6. Condicionales con operadores lógicos

```python
edad = 25

if edad >= 18 and edad <= 30:
    print("Edad dentro del rango")
```

---

### 7. Ejercicios Resueltos

**Ejercicio 1**

```python
numero = -2

if numero > 0:
    print("Positivo")
else:
    print("No positivo")
```

### Resultado:

```python
No positivo
```

---

**Ejercicio 2**

```python
precio = 80

if precio >= 100:
    print("Producto premium")
else:
    print("Producto económico")
```

---

**Ejercicio 3**

```python
usuario = "admin"

if usuario == "admin":
    print("Acceso concedido")
else:
    print("Acceso denegado")
```

---

### 8. Mini Ejercicios para Practicar

### Hazlos tú:

### 1.

```python
edad = 20
```

Si es mayor o igual a 18, imprime `"Puede entrar"`.

---

### 2.

```python
nota = 6
```

Si nota >= 7 imprime `"Aprobado"`, si no `"Reprobado"`.

---

### 3.

```python
temperatura = 10
```

Si es menor a 15 imprime `"Hace frío"`.

---

### 9. Aplicación a Datos 📊

```python
ventas = 1500

if ventas > 1000:
    print("Buen mes de ventas")
else:
    print("Mes regular")
```

---

### 🧠 Resumen Final

| Estructura | Uso             |
| ---------- | --------------- |
| `if`       | Si se cumple    |
| `else`     | Si no se cumple |
| `elif`     | Otra condición  |

---

### 🚀 Reto Final

Haz un programa con:

```python
ingresos = 5000
gastos = 3200
```

Si ingresos son mayores a gastos imprime:

```python
Hay ganancias
```

Si no:

```python
Hay pérdidas
```


## ✍ Clase 9: Condicionales y Blucle for

**Ejercicios en Vivo** - Enfoque: análisis de datos y lógica aplicada

Elije 3 ejercicios para realizar en vivo y explicar la creación de uno de ellos.

Los otros 7 ejercicios se quedan de tarea.

---

**1. Validación de Edad para Encuesta**

Solicita la edad de una persona.  

- Si tiene menos de 18 años, mostrar: `Menor de edad`
- Si tiene entre 18 y 59 años, mostrar: `Adulto`
- Si tiene 60 o más, mostrar: `Adulto mayor`

---

**2. Clasificación de Temperatura**

Pide una temperatura en grados Celsius.

- Menor a 10 → `Frío`
- Entre 10 y 25 → `Templado`
- Mayor a 25 → `Caluroso`

---

**3. Evaluación de Ventas**

Solicita el monto vendido por un empleado.

- Si vendió menos de 5000 → `Bajo rendimiento`
- Entre 5000 y 10000 → `Buen rendimiento`
- Más de 10000 → `Excelente rendimiento`

---

**4. Número Par Positivo**

Pide un número entero.

- Si es positivo y par, mostrar: `Número válido`
- Si no, mostrar: `Número no válido`

---

**5. Descuento en Compra**

Solicita el total de compra.

- Si compra es mayor o igual a 1000, aplicar 15% descuento.
- Si es menor, aplicar 5%.

Mostrar total final.

---

**6. Clasificación de Calificación**

Solicita una calificación de 0 a 100.

- Menor de 60 → `Reprobado`
- 60 a 79 → `Aprobado`
- 80 a 94 → `Bueno`
- 95 a 100 → `Excelente`

---

**7. Detección de Outlier Simple**

Pide un número.

- Si es menor a 0 o mayor a 100, mostrar: `Dato atípico`
- En otro caso: `Dato normal`

---

**8. Acceso al Sistema**

Solicita usuario y contraseña.

- Si usuario = `"admin"` y contraseña = `"1234"` → `Acceso concedido`
- Si no → `Acceso denegado`

---

**9. Clasificación de IMC**

Solicita peso (kg) y altura (m).  
Calcula IMC = peso / altura²

- Menor de 18.5 → `Bajo peso`
- 18.5 a 24.9 → `Normal`
- 25 a 29.9 → `Sobrepeso`
- 30 o más → `Obesidad`

---

**10. Bono por Productividad**

Solicita cantidad de tareas completadas.

- Menos de 5 → Sin bono
- 5 a 9 → Bono de $500
- 10 o más → Bono de $1000

---

**Extra: Reto**

En todos los ejercicios:

- Usa `input()`
- Convierte datos con `int()` o `float()`
- Usa `if`, `elif`, `else`
- Muestra resultados con `print()`

---

### ¿Qué es `for`?

> El `for` es una estructura repetitiva que sirve para **recorrer elementos** o **repetir acciones varias veces**.

Se usa cuando quieres trabajar con:

- listas
- textos
- tuplas
- rangos
- diccionarios
- datos en general

---

### Sintaxis básica

```python
for variable in iterable:
    instrucciones
```

**Ejemplo**

```python
for numero in [1, 2, 3]:
    print(numero) # 1 2 3
```    

---

## ✍ Clase 10: Más sobre el blucle for

> El `for` es una estructura de repetición que permite ejecutar un bloque de código varias veces.

Se usa principalmente para:

- Recorrer listas
- Recorrer textos
- Trabajar con rangos de números
- Procesar datos
- Automatizar tareas repetitivas

---

**Ejemplo 1**

```python
for numero in [0, 1, 2, 3, 4, 5]:
    print(numero) # 0 1 2 3 4 5
```   

**¿Cómo se interpreta?**   
Para cada número dentro de la lista, ejecuta el bloque de código.

---

**Ejemplo 2**. Recorrer una lista

```python
frutas = ["manzana", "pera", "uva"]

for fruta in frutas:
    print(fruta)     # manzana pera uva
``` 

---

**Ejemplo 3**. Recorrer un texto

```python
for letra in "python":
    print(letra)    # p y t h o n
``` 

---

**Ejemplo 4**. Usar range()
   
range() genera una secuencia de números.   
Del 0 al 4
```python
for i in range(5):
    print(i)       # 0 1 2 3 4
``` 

---

**Ejemplo 5**. Usando range()
   
Del 1 al 5
```python
for i in range(1, 6):
    print(i)      # 1 2 3 4 5
``` 

---

**Ejemplo 6**. Usando range()
   
Con saltos de 2 en 2
```python
for i in range(0, 11, 2):
    print(i)     # 0 2 4 6 8 10
``` 

---

**Ejemplo 7**. Usando range()
   
**for** con condicionales

```python
for numero in range(1, 6):
    if numero % 2 == 0:
        print(numero)    # 2 4
``` 

---

### Resumen

| Código            | Significado       |
| ----------------- | ----------------- |
| `for x in lista:` | Recorre una lista |
| `for x in texto:` | Recorre letras    |
| `range(5)`        | Del 0 al 4        |
| `range(1,6)`      | Del 1 al 5        |
| `range(0,10,2)`   | Saltos de 2       |

---

## ✍ Clase 11: Ejercicios de Fundamentos de Programación y Python

### Bloque 1: Lógica y Algoritmos (Pensamiento Computacional)

**Enfocados en la Clase 1, 2 y 3 del curso.**

1. **Algoritmo cotidiano:** Escribe los pasos detallados para enviar un paquete por correo.

1. **Pseudocódigo de Área:** Crea el pseudocódigo para calcular el área de un rectángulo pidiendo base y altura.

1. **Diagrama de Flujo Lógico:** Diseña un diagrama que represente el proceso de decidir si salir de casa dependiendo de si llueve y si tienes paraguas.

1. **Intercambio de valores:** Escribe un algoritmo para intercambiar los valores de dos variables A y B usando una variable auxiliar.

1. **Cajero Automático (Lógica):** Escribe el pseudocódigo para retirar dinero, validando si el saldo es suficiente.

---

### Bloque 2: Variables y Operadores en Python

**Basados en las Clases 4, 5, 6 y 7.**

6. **Variables personales:** Crea variables para tu nombre, edad y ciudad, e imprímelas en una sola frase usando f-strings.
   
7. **Calculadora de IMC:** Pide el peso (kg) y la altura (m) y calcula el Índice de Masa Corporal: $IMC = peso / altura^2$.
   
8. **Operadores de comparación:** Escribe un programa que pida dos números y devuelva True si el primero es mayor o igual al segundo.
   
9.  **Días a segundos:** Crea un script que convierta un número de días ingresado por el usuario a segundos.
    
10. **Formateo de precios:** Pide el precio de un producto y aplica un descuento del 15%. Muestra el precio final con solo dos decimales.

---

### Bloque 3: Toma de Decisiones (Condicionales)

**Basados en las Clases 8 y 9.**

11. **Mayor de tres:** Pide tres números y determina cuál es el mayor de todos.

12. **Aprobado o Reprobado:** Pide una calificación. Si es mayor a 60, muestra "Aprobado", de lo contrario "Reprobado".

13. **Clasificador de números:** Determina si un número es positivo, negativo o cero.

14. **Calculadora básica:** Pide dos números y una operación (+, -, *, /). Realiza la operación correspondiente usando if-elif-else.

15. **Día de la semana:** Pide un número del 1 al 7 y muestra el nombre del día correspondiente (1 = Lunes, etc.).

16. **Año Bisiesto:** Crea un programa que detecte si un año es bisiesto (divisible entre 4 y no entre 100, o divisible entre 400).

17. **Sistema de Becas:** Un estudiante califica si su promedio es > 90 y su edad es < 25. Usa operadores lógicos and.

18. **Tienda de Mascotas:** Si el usuario compra más de 3 artículos, aplica un 10% de descuento; si compra más de 5, aplica un 20%.

---

### Bloque 4: Bucles e Iteraciones (Ciclo For)

**Basados en las Clases 9 y 10.**

19. **Conteo simple:** Imprime los números del 1 al 20 usando un bucle for.

20. **Suma acumulada:** Calcula la suma de todos los números del 1 al 100.

21. **Pares en un rango:** Imprime todos los números pares entre 0 y el número que el usuario elija.

22. **Tabla de multiplicar dinámica:** Pide un número e imprime su tabla del 1 al 12.

23. **Contador de caracteres:** Pide una cadena de texto y cuenta cuántas veces aparece la letra "a".

24. **Promedio de notas:** Pide al usuario cuántas notas quiere ingresar, recíbelas y calcula el promedio final.

25. **Buscador de elementos:** Dada una lista de nombres, verifica si "Luis" está presente e imprime su posición.
    
26. **Factorial:** Calcula el factorial de un número usando un bucle for ($n!$).
    
27. **Dibujo de patrones:** Imprime un triángulo de asteriscos de $N$ filas (ej: *, , ***).
    
28. **Inversión de cadena:** Pide una palabra y muéstrala letra por letra en orden inverso.
    
29. **Filtrado de datos:** Dada una lista de números [10, 55, 42, 12, 80, 21], imprime solo aquellos mayores a 50.
    
30. **Validación de entrada:** Simula un login que pida una contraseña y solo termine cuando el usuario escriba la correcta ("Python123").
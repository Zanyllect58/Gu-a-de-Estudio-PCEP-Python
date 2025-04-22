# PYTHON BÁSICO

## Tipos de Variables en Python

En Python, existen varios tipos de datos que se utilizan para almacenar información. A continuación, te explico los más comunes:

### 1. **`int` (Enteros)**
Se utilizan para representar números enteros, sin decimales.  
**Ejemplo de uso**: Edad, años, cantidad de elementos.

```python
edad = 30  # La edad de una persona
anio = 2025  # Año actual o futuro
```

### 2. **`float` (Flotantes)**
Se utilizan para representar números decimales.  
**Ejemplo de uso**: Salarios, precios, tasas de interés.

```python
precio = 99.99  # Precio de un producto o servicio
interes = 0.05  # Tasa de interés anual del 5%
```

### 3. **`str` (Cadenas de texto)**
Son secuencias de caracteres, utilizadas para representar texto.  
**Ejemplo de uso**: Nombre de usuario, moneda, mensajes de bienvenida.

```python
nombre = "Ana"  # Nombre de una persona
moneda = "USD"  # Moneda en la que se expresa el monto (dólares)
mensaje = "Bienvenido a Finanzas con Python"  # Mensaje para la bienvenida
```

### 4. **`bool` (Booleanos)**
Representan valores binarios **True** o **False**, y se usan para condiciones o estados.  
**Ejemplo de uso**: Verificación de condiciones, si una inversión es segura o no.

```python
es_mayor_de_edad = True  # Verificación si una persona es mayor de edad
inversion_segura = False  # Verificación si una inversión es segura o no
```

---

## Conversión de Tipos de Variables (Casting)

A veces es necesario convertir un tipo de variable a otro. Aquí tienes un par de ejemplos de cómo hacerlo en Python:

```python
# Convertir de float a int
precio_int = int(precio)  # Convierte 99.99 a 99

# Convertir de int a str
anio_str = str(anio)  # Convierte 2025 a la cadena "2025"
```

---

## Listas y Tuplas

Las **listas** y **tuplas** son tipos de datos que permiten almacenar colecciones de elementos. La diferencia principal es que las listas son **mutables** (pueden modificarse) y las tuplas son **inmutables** (no se pueden modificar una vez creadas).

### 1. **Listas** (`list`)
Son colecciones ordenadas, y puedes añadir, eliminar o modificar sus elementos.

```python
lista_frutas = ["manzana", "banana", "cereza"]
lista_frutas.append("naranja")  # Añadir un nuevo elemento a la lista
```

### 2. **Tuplas** (`tuple`)
Son colecciones ordenadas, pero inmutables. Una vez que se crean, no puedes cambiar sus elementos.

```python
coordenadas = (10, 20)  # Ejemplo de tupla con coordenadas
```

---

## Diccionarios

Los **diccionarios** (`dict`) son colecciones de pares **clave-valor**. Son ideales para representar relaciones entre elementos, como un conjunto de datos donde cada clave está asociada a un valor.

```python
persona = {"nombre": "Juan", "edad": 28, "profesion": "ingeniero"}
print(persona["nombre"])  # Accede al valor de la clave "nombre", en este caso "Juan"
```

## Verificar el Tipo de Dato 
Puedes usar la función type() para saber qué tipo de dato tiene una variable:

```python
print(type(nombre))  # Resultado: <class 'str'>
print(type(edad))    # Resultado: <class 'int'>
```
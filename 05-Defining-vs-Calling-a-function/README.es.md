# `05` Definir vs llamar a una función

Las funciones solo existen si tú u otra persona las define... es la única forma en que el compilador/intérprete de idiomas sabe que existen, por lo tanto, puede ejecutarlas cuando las llama.

Para definir una función necesitamos escribir esta fórmula básica de código:

```python
def myFunctionName(parameter, parameter2, ...parameterX):
    # codigo de la función aquí
    return something
```

La palabra `def` es una palabra reservada en Python, esto significa que solo se usa para definir una función.

**El nombre** de la función podría ser lo que quieras.

*Consejo:* usa un nombre descriptivo (no intentes ahorrar palabras, usa tantas como necesites) de esta manera entenderás lo que hace la función (y lo que devuelve).

Nombres de ejemplo: `add_two_integers` (suma dos números enteros), `calculate_taxes` (calcular impuestos) , `get_random_number` (obtener número aleatorio), etc.

**Parámetros:** puedes definir tantos parámetros como desees, más aún, si los necesitas. 

La cantidad de parámetros dependerá de las operaciones realizadas dentro de la función. 

Ejemplo: si la función está sumando dos enteros (3 + 4), esto significa que la función necesitará dos parámetros (uno para cada entero).

**Alcance:** Todo el código que contenga la función debe tener una sangría a la derecha, todo lo que esté en una sangría diferente no será considerado como parte de la función, a esto se llama **alcance**, y puede ser local (dentro de la función) y global (fuera de la función).

**El retorno**: no todas las funciones necesitan devolver algo, pero se recomienda que lo hagan.

*Consejo*: devolver `None` es un buen valor por defecto para cuando, aún, no sabes si tu función debe devolver algo.

Ejemplo de una función:

```python
def concatenate_number_to_string(local_number, local_string):
    local_variable = local_string+""+str(local_number)
    return local_variable
```


## 📝 Instrucciones:

1. Define una función llamada `multi`.

2. La función `multi` recibe dos números.

3. Devuelve el resultado de la multiplicación entre ellos.

## 💡 Pista:

+ Recuerda agregar la línea de `return`. Una función siempre debería devolver algo. En este caso debería ser el resultado de la multiplicación.

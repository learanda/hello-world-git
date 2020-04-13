# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- Formato *italica* de la primer forma.
- Formato _italica_ de la segunda forma.
- Formato **bold o strong** de la primer forma.
- Formato __bold o strong__ de la segunda forma.
- Formato ~~tachado~~, formato normal.
- Aqui empleamos los formatos *italico*, **bold** y ~~tachado~~.
- Y tambien se pueden *__~~combinar~~__* como se quisiera.

# Listas
1. Este es un item de lista ordenada.
2. Este es un item de lista ordenada.
3. Este es un item de lista ordenada.
- Este es un item de lista desordenada.
- Este es un item de lista desordenada.
- Este es un item de lista desordenada.

# Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://google.com)
- [Esto es un link al index](index.html)
- [[Esto es un link a "Cabeceras"](#cabeceras)]
- [[Esto es un link a "Listas"](#listas)]
- [Para mas ejemplos, ver este readme en "RAW"](https://github.com/maxwellnewage/javascript_ejercicios/blob/master/README.md#general)

# Imagenes
![Logo GitHub](https://i.pinimg.com/originals/9e/2f/3c/9e2f3c8282f7e7eabf0612872880cc4d.png)

# Code Snippets
Codigo en JSON (se debe especificar el lenguaje para que el highlight lo reconozca como codigo). Extracto tomado de [Highlightjs.org](https://highlightjs.org/static/demo/)
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

Codigo en JavaScript
```javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Leandro | Aranda | 12345678 |
| Maxi | Burgos | 12345678 |
| Leandro | Aranda | 12345678 |
| Maxi | Burgos | 12345678 |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es un texto que no se relaciona con la cita anterior:
> Esto es otra cita.

# Lineas divisoras
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro texto dividido por guiones bajos.

___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
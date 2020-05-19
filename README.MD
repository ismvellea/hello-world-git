# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

#Underlines
Underline 1 
-----------

Underline 2
-----------
-----------

# Formatos de Énfasis
- Letra *itálica* de la primera forma.
- Letra _itálica_ de la segunda forma.
- Formato **Bold** o **Strong** de la primera forma.
- Formato __Bold__ o __Strong__ de la primera forma.
- Formato ~~Tachado~~, formato Normal.
- Aquí podemos usar *formato itálico* pero también **bold** y también ~~tachado~~.

# Listas 
1. Esto es un item de Lista ordenada.
2. Esto es un item de Lista ordenada.
3. Esto es un item de Lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="https://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)
- [Esto es un link a 'Cabeceras'](Cabeceras)

# Imágenes
![Logo Github](https://i.pinimg.com/originals/dc/1a/1a/dc1a1a4287f57e4a80ea5ecfd912ee96.png)

# Code Snippets
Código en JSON 
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

Código en Javascript 
```Javascript
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
| Ismael | Vela     | 12345678Z |
| Test   | Test     | 12341235R |

# Citas
Esto es un texto referente a una cida que pondremos justo debajo:
> Esto es una cita.

Esto es otro texto que nos e relaciona con la cita anterior.
> Esto es otra cita.


I'm a Readme.
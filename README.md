# Aprendiendo Markdown
Podemos usar varios titulos como en html:
## title 2
### title 3
#### title 4
##### title 5
###### title 6

---

<!-- Forma de colcar italica -->
*Texto en italica*

_texto en italica_

<!-- Forma de colocar negrita -->
**Texto en strong**

__Texto en strong__

<!-- Forma de colocar texto tachado -->
~~Texto tachado~~

___

<!-- Listas desordenadas -->
### Listas desordenadas
* item 1
    + item 1.1
- item 2
    * item 2.1
+ item 3
    * item 3.1

---

<!-- Listas ordenadas -->
### Listas ordenadas
1. item 1
    1. item 1.1
2. item 2
    1. item 2.1
3. item 3
    1. item 3.1

---

### Lineas Divisoras
---
___

### Citar
> Esto es un cita

---

### Colocar Vinculos
[Dar click!](https://www.google.com 'Enlace a google')

---

### Colocar código
Bloque de codigo:
``` js
import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';
import App from './App';
import reportWebVitals from './reportWebVitals';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);

reportWebVitals();
```
con tabulardor se puede crear un código de una linea

    console.log('Hello World')

---

### Crear tablas
| title 1 | title 2 | title 3 |
| ------- | ------- | ------- |
| celda 1 | celda 2 | celda 3 |
| celda 4 | celda 5 | celda 6 |
| celda 7 | celda 8 | celda 9 |

---

### Colocar imagenes
![logo](https://cdn.pixabay.com/photo/2015/11/02/14/01/google-1018443_960_720.png 'logo google')

#### Para colocarla localmente
![logo](BMTH.png 'logo bring me the horizon')

---

## Markdown en github

### Crear lista de tareas
* [ ] homework one
* [x] homework two
* [x] homework three
* [ ] homework four

---

### Mencionar un usario, quien recibira una notificación
@jonsdevsigned

---

### emojis
:alien:
:smiley:
:+1:



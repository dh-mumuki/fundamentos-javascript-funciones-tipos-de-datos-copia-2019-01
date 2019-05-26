¿Y que pasa si quiero sumar textos? :hushed:
En éste caso el símbolo `+` nos va a ayudar a concatenar, es decir, juntar nuestras cadenas de texto.

¡OJO, NO TE OLVIDES DE LOS ESPACIOS!    

Probemos:

```javascript
var nombre = "Messi";
var nacionalidad = "Argentino";
console.log(nombre + " es " + nacionalidad) 
// El resultado sería: "Messi es Argentino"
```

Fijate que para este caso, donde escribimos la palabra _es_ agregamos espacios antes y después. Siempre que necesitemos espacios en nuestro texto, deberémos agregarlo dentro de las comillas para indicarle a Javascript que lo queremos incluir.

> Veamos si se entiende: **Declará y asigná** dos variables, una con tu `nombre` y la otra con tu `apellido`, y luego en la variable `nombreCompleto` guardá todo junto. Ej.: “Elon Musk”. PD: No te olvides del espacio!
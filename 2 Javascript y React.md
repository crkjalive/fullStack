# Aprendiendo Javascript y React by midudev

Video 2 del playlist de bootcamp  
Javascript y luego React

# Javascript es ECMASCRIPT

1. lenguaje multiparadigma
2. tipado debil y dinámico
2. iterm2
3. Visual Studio Code

### web-Ejemplo

1. index.html
2. script.js

```
<script src="./script.js" type="module"></script>
```

# Javascript

### Variables

let, var y const  
dependiendo del ambito de su scope se podra reasignar su valor o no  

~~~
let name = 'Miguel'
const lastName = 'midudev'
var dev = 'developer'
~~~

### Tipos de datos primitivos (inmutables)
1. numerico 2
2. string 'texto'
3. booleano true o false 
4. undefined
5. null

No podemos modificar ningun valor primitivo  
podemos crear copias  

### Tipos de datos mutables 
1. {} object
2. [] arrays
3. () funciones

Array
~~~
const list = []
list.push(1)
console.log(list)
~~~

Function
~~~
const sumar = (a , b) => {
    console.log(a)
    console.log(b)
    return a + b
}
~~~

Object
~~~
const persona = {
    name: 'crkj',
    twitter: '@crkj',
    age: 19,
    isDeveloper: true,
    links: [
        'https://crkjalive.tube',
        'https://github.com/crkjalive'
        ],
    city: 'bogota'
}

const sumar = (a , b) => {
    console.log(a)
    console.log(b)
    return a + b
}

const obj = document.querySelector('h1')

obj.innerHTML = `
<h1> Nickname: ${persona.name.toUpperCase()} ${sumar(1111,873)} </h1>
<h4> Twitter: ${persona.twitter} </h4>
<h6> Youtube: ${persona.links[0]} </h6>
<h6> Github: ${persona.links[1]} </h6>
<h1></h1>
`
~~~

# React
Vamos ahora con React  

### Requerimientos de setup 
1. NodeJs
2. nvm ls (instala la version que uno quiera)

## React
Crear proyecto base de react  

~~~
npx create-react-app .
~~~

https://www.youtube.com/watch?v=YLvT1ELnaX4&list=PLV8x_i1fqBw0Kn_fBIZTa3wS_VZAqddX7&index=3


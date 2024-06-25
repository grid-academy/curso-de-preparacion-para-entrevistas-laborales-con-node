# Fundamentos de JavaScript

JavaScript es un lenguaje de programación esencial para el desarrollo web. Es el lenguaje que le da interactividad a las páginas web y se utiliza tanto en el frontend como en el backend (con Node.js).

### Variables y Tipos de Datos

En JavaScript, puedes declarar variables usando `var`, `let` o `const`. Aquí tienes algunos ejemplos:

```js
var nombre = 'Juan';
let edad = 30;
const esProgramador = true;
```

Los principales tipos de datos en JavaScript son: `string`, `number`, `boolean`, `null`, `undefined`, `object` y `symbol`.

### Funciones

Las funciones son bloques de código reutilizables que pueden ejecutarse cuando se llaman. Aquí tienes un ejemplo de una función:

```js
function saludar(nombre) {
  return `Hola, ${nombre}!`;
}

console.log(saludar('Mundo'));
```

### Objetos y Arrays

Los objetos son colecciones de pares clave-valor, mientras que los arrays son listas ordenadas de valores. Aquí tienes ejemplos de ambos:

```js
// Objeto
let persona = {
  nombre: 'Ana',
  edad: 25,
  esEstudiante: true
};

console.log(persona.nombre);

// Array
let numeros = [1, 2, 3, 4, 5];
console.log(numeros[0]);
```

### Bucles y Condicionales

Los bucles y condicionales son estructuras de control que permiten ejecutar código repetidamente o condicionalmente.

```js
// Bucle for
for (let i = 0; i < 5; i++) {
  console.log(i);
}

// Condicional if
let numero = 10;
if (numero > 5) {
  console.log('El número es mayor que 5');
} else {
  console.log('El número es 5 o menor');
}
```

### Recursos Adicionales

- [Documentación de JavaScript de MDN](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [JavaScript GitHub Repository](https://github.com/topics/javascript)

---

## Contenido del Curso

1. **Introducción a Node.js**: Conceptos básicos, instalación y primer script.
2. **Fundamentos de JavaScript**: Repaso de JavaScript, incluyendo variables, funciones y objetos.
3. **Programación Asíncrona**: Callbacks, Promesas y Async/Await.
4. **APIs RESTful**: Creación de APIs utilizando Express.
5. **Bases de Datos con Node.js**: Conexión a bases de datos SQL y NoSQL.
6. **Autenticación y Autorización**: Implementación de JWT y OAuth.
7. **Testing**: Pruebas unitarias y de integración con Mocha y Chai.
8. **Buenas Prácticas y Optimización**: Patrones de diseño, manejo de errores y optimización del rendimiento.
9. **Preparación para Entrevistas**: Preguntas comunes, resolución de problemas y consejos para entrevistas.

---

Asegúrate de revisar cada módulo y practicar los ejemplos provistos para mejorar tus habilidades en Node.js y estar bien preparado para tus entrevistas técnicas. ¡Buena suerte!

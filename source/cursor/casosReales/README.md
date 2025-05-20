# Curso Introductorio de CURSOR (Editor con IA)

---

## 🧪 Bloque 5: Casos prácticos

### Objetivo del bloque

Aplicar de forma práctica lo aprendido en los bloques anteriores mediante ejercicios reales y desafiantes usando CURSOR como copiloto.

---

### Actividades propuestas

En este bloque se presentarán 5 ejercicios que demuestran cómo CURSOR puede asistirte en tareas comunes de desarrollo:

1. Refactorizar una función de JavaScript.
2. Generar un componente React desde descripción.
3. Crear un CRUD simple con sugerencias del AI.
4. Documentar una función automáticamente.
5. Detectar y corregir un bug.

---

### Caso 1: Refactorizar una función

#### Código base:

```js
function fullName(p, a) {
  return p + ' ' + a;
}
```

#### Prompt sugerido:

> "Haz esta función más clara y con validación de tipos."

#### Resultado esperado:

```ts
function getFullName(firstName: string, lastName: string): string {
  return `${firstName} ${lastName}`;
}
```

#### Instrucciones:

1. Copia el código en CURSOR.
2. Usa `Ctrl + K` y solicita una refactorización con tipos.
3. Analiza la respuesta y compárala con el resultado sugerido.

---

### Caso 2: Generar un componente React

#### Prompt:

> "Crea un componente React que reciba un nombre y muestre un saludo personalizado."

#### Resultado sugerido:

```tsx
import React from 'react';

type GreetingProps = {
  name: string;
};

export function Greeting({ name }: GreetingProps) {
  return <h1>Hola, {name}! Bienvenido a CURSOR 🚀</h1>;
}
```

#### Instrucciones:

1. Escribe solo el prompt como comentario.
2. Deja que CURSOR genere el componente.
3. Revisa si puedes pedir una mejora visual o tipado más estricto.

---

### Caso 3: Crear un CRUD básico

#### Descripción:

> "Genera las funciones básicas para crear, leer, actualizar y eliminar usuarios desde un array."

#### Resultado:

```ts
let users: string[] = [];

function addUser(user: string) {
  users.push(user);
}

function getUsers() {
  return users;
}

function updateUser(index: number, newUser: string) {
  users[index] = newUser;
}

function deleteUser(index: number) {
  users.splice(index, 1);
}
```

#### Instrucciones:

1. Escribe la descripción como comentario.
2. CURSOR generará la lógica básica.

---

### Caso 4: Documentar una función automáticamente

#### Código base:

```ts
function multiply(a: number, b: number) {
  return a * b;
}
```

#### Prompt:

> "Documenta esta función con JSDoc."

#### Resultado esperado:

```ts
/**
 * Multiplica dos números.
 * @param a - Primer número
 * @param b - Segundo número
 * @returns El producto de a y b
 */
function multiply(a: number, b: number) {
  return a * b;
}
```

#### Instrucciones:

1. Selecciona la función y lanza el comando `Ask Cursor`.
2. Analiza la documentación generada.
3. ¿Faltaría algún detalle importante?

---

### Caso 5: Detectar y corregir un bug

#### Código con error:

```ts
const list = [1, 2, 3];
const doubled = list.map((n) => {
  n * 2;
});
console.log(doubled); // [undefined, undefined, undefined]
```

#### Prompt:

> "¿Por qué este código no devuelve los valores duplicados?"

#### Respuesta esperada:

> "Falta el return dentro del `map`."

#### Solución:

```ts
const doubled = list.map((n) => {
  return n * 2;
});
```

#### Instrucciones:

1. Pega el código con error.
2. Pide a CURSOR que lo revise y corrija.
3. Verifica la respuesta y prueba el resultado en la terminal integrada.

---

### 🎯 Desafío libre (opcional)

Crea un nuevo fragmento de código por tu cuenta (una función, clase o componente). Luego:

* Pide a CURSOR que lo explique o mejore.
* Genera documentación y tests automáticos.
* Opcional: solicita la traducción a otro lenguaje como Python o Go.

---

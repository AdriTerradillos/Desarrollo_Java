# Curso Introductorio de CURSOR (Editor con IA)

---

## ✨ Bloque 4: Uso de la IA en CURSOR

### Objetivo

Aprender a aprovechar las funcionalidades de inteligencia artificial integradas en CURSOR para programar de forma más rápida, clara y eficiente.

---

### Capacidades clave de la IA en CURSOR

* 🧠 **Explicación de código**
* ✍️ **Generación de código / Autocompletado contextual**
* 🔁 **Refactorización automática (a solicitud)**
* 🧪 **Generación de tests unitarios**
* 🐞 **Depuración asistida**

---

### 🧠 Explicación de código

Selecciona una función o bloque y presiona `Ctrl + K` / `Cmd + K` para preguntarle a la IA:

```md
"¿Qué hace esta función?"
"¿Qué significa este error?"
```

---

### ✍️ Generación de código

Puedes escribir un comentario o prompt como:

```js
// Crea una función que calcule el área de un círculo dado su radio
```

CURSOR generará automáticamente una función válida en base al contexto.

---

### 🔁 Refactorización automática

Selecciona cualquier fragmento y presiona `Ctrl + .` o haz clic derecho → "Refactorizar" para:

* Simplificar estructuras.
* Renombrar variables.
* Extraer funciones reutilizables.
* Aplicar mejores prácticas de estilo.

---

### 🧪 Generación de tests

Puedes pedirle al AI que genere pruebas unitarias con un prompt como:

```md
"Genera tests para esta función usando Jest."
```

CURSOR escribirá automáticamente los `describe` y `it` correspondientes.

---

### 🐞 Depuración asistida

Selecciona un bloque con errores o mal funcionamiento y pregunta:

```md
"¿Por qué esto falla?"
"¿Cómo puedo arreglar esta promesa?"
```

La IA propondrá soluciones y explicaciones paso a paso.

---

### 💡 Ejemplo práctico 1: explicación + refactor

Código original:

```ts
function greet(n: string) {
  return `Hello, ${n}! Welcome.`;
}
```

Prompt: `¿Puedes hacerlo más formal y reusable?`

Resultado sugerido:

```ts
export function generateGreeting(name: string): string {
  return `Good day, ${name}. It's a pleasure to have you here.`;
}
```

---

### 💡 Ejemplo práctico 2: generación desde descripción

Prompt:

```md
"Escribe una función en TypeScript que ordene un array de objetos por fecha descendente."
```

Resultado sugerido:

```ts
interface Item {
  name: string;
  date: string;
}

function sortByDateDesc(arr: Item[]): Item[] {
  return arr.sort((a, b) => new Date(b.date).getTime() - new Date(a.date).getTime());
}
```

---

### 🧪 Actividad práctica

1. Escribe una función simple (por ejemplo: conversión de temperaturas).
2. Pide a CURSOR:

   * Que explique qué hace.
   * Que la refactorice.
   * Que genere tests.
3. Introduce un error intencional y solicita ayuda para resolverlo con la IA.

---

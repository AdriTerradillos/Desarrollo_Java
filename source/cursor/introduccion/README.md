# Curso Introductorio de CURSOR (Editor con IA)

---

## 🧩 Introducción a CURSOR

### ¿Qué es CURSOR?

CURSOR es un editor de código moderno, basado en Visual Studio Code, que integra inteligencia artificial para asistir al programador. Combina la potencia de un IDE con un copiloto conversacional entrenado para entender, mejorar y explicar código.

### ¿Por qué usar CURSOR?

* ✨ **Autocompletado inteligente** y sugerencias contextuales.
* 🔧 **Refactorización rápida** y generación automática de funciones.
* 📘 **Explicaciones claras** de cualquier fragmento de código.
* 🧪 **Generación de tests unitarios** y documentación automática.
* 🌐 **Compatibilidad multilenguaje:** JavaScript, TypeScript, Python, Rust, Go, entre otros.
* 🤖 **Chat integrado** para resolver dudas directamente dentro del editor.
* 💼 **Totalmente compatible** con proyectos existentes de VS Code.

### ¿Cómo se diferencia de VS Code?

| Característica           | VS Code          | CURSOR                        |
| ------------------------ | ---------------- | ----------------------------- |
| Editor base              | Sí               | Sí                            |
| Chat contextual con IA   | No (sin plugins) | Sí, integrado de forma nativa |
| Sugerencias con contexto | Limitadas        | Avanzadas mediante IA         |
| Instalación de plugins   | Requerida        | Ya incluye lo esencial        |
| Velocidad de arranque    | Rápida           | Igual de rápida               |

---

### 💡 Caso de uso: preguntar a la IA

Supón que encuentras este fragmento de código:

```ts
function calculateTotal(prices: number[], taxRate: number): number {
  return prices.reduce((sum, price) => sum + price * (1 + taxRate), 0);
}
```

Puedes seleccionar esta función y presionar `Ctrl + K` (o `Cmd + K`) para preguntarle a CURSOR:

> “¿Qué hace esta función? ¿Hay una forma más clara de escribirla?”

CURSOR no solo la explicará, sino que podrá sugerirte una versión más legible o con mejores prácticas.

---

### 🧠 Prompts útiles para comenzar

* “¿Qué hace esta función?”
* “¿Puedes refactorizar esto para mayor legibilidad?”
* “Genera un test unitario para este método.”
* “Haz esta función compatible con navegadores antiguos.”

---

### 💬 Pregunta de reflexión final

*¿Cómo cambiaría tu manera de programar si tuvieras un copiloto inteligente a tu lado todo el tiempo?*

---

# CodeEmpathy

# El Agente Web Inclusivo

## 🚨 El Problema
Internet es el servicio público más esencial del mundo, pero sigue fallando para millones de personas.  
Más del **96%** del millón de páginas de inicio principales contienen fallos de accesibilidad **WCAG**.

Para los usuarios con discapacidad visual, navegar por la web suele ser un laberinto frustrante de:

- Textos `alt` faltantes  
- Formularios sin etiquetas  
- Navegación confusa  
- Elementos visuales sin contexto  

Para **ONG**, **servicios públicos** y **pequeñas empresas**, solucionar estos problemas manualmente es:

- Técnicamente difícil  
- Lento  
- Costoso  

---

## ✅ La Solución
Estamos desarrollando el **Agente Web Inclusivo**, un **bot autónomo e inteligente** que no solo detecta problemas de accesibilidad… **los corrige automáticamente**.

A diferencia de los linters tradicionales que solo informan errores, **nuestro agente actúa como un ingeniero proactivo**.

---

## 🧠 Cómo Funciona (La Pila Tecnológica)

### 1. 🔍 Scan & Reason  
Con **Python** y **Playwright**, el agente navega una URL o repositorio de GitHub y analiza el **DOM** en profundidad.

### 2. 👁 Comprensión Visual  
Usamos:

- **Azure Computer Vision**  
- **Azure OpenAI (GPT-4o)**  

El agente entiende el contenido visual: reconoce que `image.png` no es solo un archivo, sino un **botón "Guardar"**.

### 3. 🏗 Generación de Código  
La IA genera HTML accesible:

- Inyecta etiquetas **ARIA** precisas  
- Produce **texto alternativo** descriptivo basado en el contenido visual real  

### 4. 🤖 Acción Automatizada  
Mediante la **API de GitHub**, el agente:

- Crea automáticamente una **Pull Request**
- Incluye todas las correcciones de accesibilidad  
- Permite que el propietario solo revise y fusione  

---

## 🌍 Por Qué Es un Éxito

Estamos transformando la accesibilidad web de una tarea manual a un **estándar automatizado**.

Gracias al razonamiento avanzado de **Azure OpenAI**, reducimos el coste de la accesibilidad web a **casi cero**, haciendo que el mundo digital sea:

- **Inclusivo por defecto**  
- Más rápido de mantener  
- Más fácil de escalar  

No solo marcamos errores.  
**Enviamos código que cambia vidas.**

# docs-Investigacion.FC2310
# Conventional Commits

## 💬 ¿Qué es un *commit*?

En **Git**, un *commit* es como una **foto o guardado del progreso** de tu proyecto.  
Cada vez que haces un cambio (por ejemplo, corriges un error o agregas una nueva función), puedes “guardar” ese estado con un mensaje, algo como:

```
git commit -m "Arreglar el botón de login"
```

Ese mensaje ayuda a entender qué hiciste en ese momento.

---

## 📋 ¿Qué es *Conventional Commits*?

**Conventional Commits** es una **forma estandarizada de escribir los mensajes de commit**.  
En lugar de escribir cualquier cosa, se sigue una **estructura clara y uniforme**.

### 🧩 Estructura básica

```
<tipo>(opcional: alcance): <descripción>
```

**Ejemplos:**
```
feat: agregar página de registro
fix: corregir error al guardar usuario
docs: actualizar el README
style: ajustar sangría y formato del código
refactor: mejorar estructura sin cambiar comportamiento
test: agregar pruebas unitarias
```

---

## 🔍 Tipos comunes

| Tipo | Significado |
|------|--------------|
| **feat** | Nueva funcionalidad o característica |
| **fix** | Corrección de un error (bug) |
| **docs** | Cambios en documentación (README, comentarios, etc.) |
| **style** | Cambios de formato (espacios, comas, etc.), sin afectar el código |
| **refactor** | Reorganizar el código sin cambiar su comportamiento |
| **test** | Agregar o modificar pruebas |
| **chore** | Tareas menores o mantenimiento del proyecto |

---

## 🌟 ¿Por qué es importante usarlo?

1. 🧠 **Más claridad:**  
   Todos los mensajes siguen el mismo formato, así cualquiera puede entender rápidamente los cambios.

2. 🔍 **Historial ordenado:**  
   Facilita buscar cambios específicos, por ejemplo, ver solo los *fix* o los *feat*.

3. 🤖 **Automatización:**  
   Permite usar herramientas que **generan automáticamente notas de versión (CHANGELOG)** o incluso **versionan tu proyecto automáticamente**.

4. 👥 **Mejor trabajo en equipo:**  
   Si varias personas colaboran, todos usan el mismo estilo de mensajes, lo que evita confusión.

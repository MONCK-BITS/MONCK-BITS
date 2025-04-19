
# 🧭 Guía Estandarizada de Flujo de Trabajo para Proyectos

Este documento describe un flujo de trabajo estructurado desde la preparación inicial hasta la sincronización en GitHub, ideal para trabajar desde Visual Studio Code (VSC), integrando también Trello y Notion para planificación y documentación.

---

## ✅ PARTE 1: Preparación previa antes de subir a GitHub

### 📦 Estructura organizada del proyecto
- Carpeta raíz clara (`Nombre_Proyecto`)
- Subcarpetas: `/src`, `/docs`, `/app`, `/tests`, `/assets`, etc.
- Nombres sin espacios ni caracteres especiales

### 📄 Archivos base obligatorios
- `README.md` ➝ Descripción, uso, dependencias, etc.
- `.gitignore` ➝ Excluir rutas o archivos como `*.env`, `/app/Carga`, etc.
- `LICENSE` si se libera el código
- `requirements.txt` o `package.json` según el lenguaje

### ⚙️ Validaciones iniciales
- ¿Corre localmente?
- ¿Se abren los archivos correctamente?
- ¿El script principal ejecuta sin errores?
- ¿Los nombres están normalizados?

---

## ✅ PARTE 2: Crear y conectar con GitHub desde VSC

### 🚀 Inicializa el repositorio
```bash
git init
git add .
git commit -m "Primera versión del proyecto"
```

### 🌐 Crear repositorio en GitHub
- Desde https://github.com
- Sin README ni `.gitignore` en GitHub (ya lo tienes localmente)

### 🔗 Conectar y subir
```bash
git remote add origin https://github.com/MONCK-BITS/repositorio.git
git branch -M main
git push -u origin main
```

---

## ✅ PARTE 3: Flujo de trabajo estándar en VSC

### Cambios frecuentes desde interfaz
1. Verifica cambios en "CONTROL DE CÓDIGO FUENTE"
2. Escribe mensaje de commit
3. Confirma (✓)
4. Sincroniza cambios (🔄)

### O desde terminal
```bash
git status
git add .
git commit -m "Cambios realizados"
git push
```

---

## ✅ PARTE 4: Documentación, planificación y seguimiento

### GitHub
- Usa Projects o Issues para tareas
- Wiki para documentación pública

### Trello
- Check List Trello
- Enlaza commits con URL

### Notion
- Base de conocimiento del proyecto
- Bitácora de decisiones
- Instrucciones técnicas

---

## 🔁 Checklist para nuevos proyectos (pendiente de generación)
✔️ Preparación completada  
✔️ Estructura ordenada  
✔️ GitHub listo y conectado  
✔️ Documentación base creada  

> Próximo paso: Generar checklist como plantilla para Trello y Notion

# 🌿 **Estructura de Ramas Git - VEYRA**

## 📋 **Ramas Recomendadas**

### 🏠 **Rama Principal (Compartida)**
- **Nombre:** `main`
- **Propósito:** Código estable y funcional
- **Acceso:** Todos los miembros del equipo
- **Uso:** Merge de features completadas y probadas

### 👤 **Ramas de Desarrollador**
- **Formato:** `dev/[nombre-del-desarrollador]`
- **Ejemplos:**
  - `dev/sebastian` - Rama de Sebastián
  - `dev/developer2` - Rama del segundo desarrollador
  - `dev/developer3` - Rama del tercer desarrollador

### 🚀 **Ramas de Feature**
- **Formato:** `feature/[nombre-de-la-feature]`
- **Ejemplos:**
  - `feature/navigation-improvements`
  - `feature/accessibility-enhancements`
  - `feature/responsive-design`

## 🔄 **Flujo de Trabajo Recomendado**

### 1. **Clonar el Repositorio**
```bash
git clone [URL-del-repositorio]
cd veyra-project
```

### 2. **Crear Rama de Desarrollador**
```bash
git checkout -b dev/[tu-nombre]
git push -u origin dev/[tu-nombre]
```

### 3. **Desarrollo de Features**
```bash
# Crear rama de feature desde tu rama de desarrollador
git checkout -b feature/[nombre-feature]

# Hacer cambios y commits
git add .
git commit -m "feat: [descripción de la feature]"

# Push de la feature
git push -u origin feature/[nombre-feature]
```

### 4. **Merge a Rama de Desarrollador**
```bash
# Volver a tu rama de desarrollador
git checkout dev/[tu-nombre]

# Merge de la feature
git merge feature/[nombre-feature]

# Push de cambios
git push origin dev/[tu-nombre]
```

### 5. **Merge a Main (Después de Review)**
```bash
# Crear Pull Request desde dev/[tu-nombre] a main
# Después de aprobación, merge a main
git checkout main
git pull origin main
git merge dev/[tu-nombre]
git push origin main
```

## 📝 **Convenciones de Commits**

### **Formato:**
```
tipo: descripción breve

tipo puede ser:
- feat: nueva feature
- fix: corrección de bug
- docs: documentación
- style: cambios de estilo
- refactor: refactorización de código
- test: tests
- chore: tareas de mantenimiento
```

### **Ejemplos:**
```bash
git commit -m "feat: add responsive navigation for mobile"
git commit -m "fix: resolve accessibility issues in forms"
git commit -m "docs: update README with team information"
```

## 🚨 **Reglas Importantes**

### ✅ **Permitido:**
- Trabajar en tu rama de desarrollador
- Crear ramas de feature para cambios específicos
- Hacer commits frecuentes con mensajes descriptivos
- Crear Pull Requests para merge a main

### ❌ **No Permitido:**
- Trabajar directamente en main
- Hacer merge sin Pull Request
- Commits sin mensajes descriptivos
- Push de código no probado a main

## 🔍 **Comandos Útiles**

### **Ver Ramas:**
```bash
git branch -a          # Ver todas las ramas
git branch -r          # Ver ramas remotas
git branch -v          # Ver ramas con último commit
```

### **Cambiar de Rama:**
```bash
git checkout [nombre-rama]
git checkout -b [nueva-rama]  # Crear y cambiar a nueva rama
```

### **Sincronizar con Remoto:**
```bash
git fetch origin        # Obtener cambios del remoto
git pull origin main    # Actualizar main local
git push origin [rama]  # Push de cambios
```

### **Ver Estado:**
```bash
git status              # Estado del working directory
git log --oneline       # Historial de commits
git diff                # Cambios no staged
```

## 📊 **Estructura Visual**

```
main (rama compartida)
├── dev/sebastian
│   ├── feature/navigation
│   ├── feature/accessibility
│   └── feature/responsive
├── dev/developer2
│   ├── feature/user-authentication
│   └── feature/dashboard
└── dev/developer3
    ├── feature/product-catalog
    └── feature/shopping-cart
```

## 🎯 **Objetivos del Sistema de Ramas**

1. **Colaboración Segura:** Evitar conflictos entre desarrolladores
2. **Trazabilidad:** Seguimiento claro de cambios y features
3. **Calidad:** Code review antes de merge a main
4. **Flexibilidad:** Desarrollo paralelo sin interferencias
5. **Estabilidad:** Main siempre contiene código funcional

## 📞 **Soporte**

Para dudas sobre el sistema de ramas o Git:
- Revisar esta documentación
- Consultar con el equipo
- Usar recursos de Git oficiales

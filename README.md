# Ejercicios aprendiendo Git - GitHub Classroom

Aquí les dejo una colección completa de ejercicios progresivos para aprender Git y GitHub, diseñados para GitHub Classroom con autocalificación automática usando Jest.

## 📖 Recursos Adicionales

- [Documentación oficial de Git](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com/)
- [Interactive Git Tutorial](https://learngitbranching.js.org/)


## 📚 Descripción del Proyecto

Este repositorio contiene una serie de ejercicios estructurados para que los estudiantes aprendan Git desde lo básico hasta conceptos más avanzados. Cada ejercicio incluye:

- Instrucciones detalladas paso a paso.
- Tests automatizados para verificar el progreso.
- Integración con GitHub Classroom para autocalificación.
- Ejemplos prácticos y casos de uso reales.

## 🎯 Objetivos de Aprendizaje

Al completar estos ejercicios, los estudiantes serán capaces de:

1. **Fundamentos de Git**
   - Inicializar repositorios
   - Configurar Git
   - Realizar commits básicos

2. **Gestión de Archivos**
   - Añadir y modificar archivos
   - Usar el área de staging
   - Entender el flujo de trabajo de Git

3. **Trabajo con Ramas**
   - Crear y gestionar branches
   - Realizar merges
   - Resolver conflictos

4. **Integración con GitHub**
   - Conectar repositorios locales con remotos
   - Realizar push y pull
   - Sincronizar cambios

## 📋 Lista de Ejercicios

| Ejercicio | Descripción | Conceptos Clave |
|-----------|-------------|-----------------|
| **1** | [Inicializar Git](ejercicios/ejercicio-1-git-init.md) | `git init`, `git config`, configuración inicial |
| **2** | [Primer Commit](ejercicios/ejercicio-2-primer-commit.md) | `git add`, `git commit`, `git status` |
| **3** | [Modificar y Commits](ejercicios/ejercicio-3-modificar-commits.md) | `git diff`, commits múltiples, staging selectivo |
| **4** | [Trabajar con Ramas](ejercicios/ejercicio-4-ramas.md) | `git branch`, `git checkout`, `git merge` |
| **5** | [GitHub y Push](ejercicios/ejercicio-5-github-push.md) | `git remote`, `git push`, GitHub integration |
| **6** | [Pull y Clone](ejercicios/ejercicio-6-pull-clone.md) | `git pull`, `git clone`, sincronización |
| **7** | [Conflictos](ejercicios/ejercicio-7-conflictos.md) | Resolución de conflictos, merge conflicts |

## 🚀 Cómo Empezar

### Para Estudiantes

1. **Acepta la asignación** a través del enlace de GitHub Classroom
2. **Clona tu repositorio** generado automáticamente
3. **Instala las dependencias**:
   ```bash
   npm install
   ```
4. **Comienza con el Ejercicio 1** y sigue las instrucciones
5. **Verifica tu progreso** ejecutando los tests:
   ```bash
   npm test ejercicio/1
   ```

## ⚡ Comandos de Testing

```bash
# Ejecutar todos los tests
npm test

# Ejecutar tests de Git básico (ejercicios 1-3)
npm run test:git

# Ejecutar tests de GitHub (ejercicios 4-7)
npm run test:github

# Ejecutar un ejercicio específico
npm test ejercicio/1

# Ejecutar tests con detalles
npm run test:verbose

# Ejecutar tests en modo watch
npm run test:watch

# Generar reporte de cobertura
npm run test:coverage
```

## 📁 Estructura del Proyecto

```
├── ejercicios/           # Instrucciones de los ejercicios
├── tests/
│   └── ejercicio/        # Tests automatizados para cada ejercicio
├── coverage/             # Reportes de cobertura (generado)
├── package.json          # Configuración del proyecto
├── jest.config.js        # Configuración de Jest
└── README.md            # Este archivo
```
---

**Total**: 1.0 punto

## ✅ Criterios de Evaluación

Cada ejercicio es evaluado automáticamente en base a:

- **Existencia de archivos requeridos**
- **Contenido correcto de los archivos**
- **Historial de commits apropiado**
- **Estado del repositorio Git**
- **Configuración correcta**
- **Sincronización con GitHub**

---

**¡Feliz aprendizaje con Git! 🎉**

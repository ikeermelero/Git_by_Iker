# 🔧 Guía básica de Git

Guía rápida con los comandos esenciales para empezar a trabajar con Git.

---

## 📦 Configuración inicial

### Configurar nombre de usuario
```bash
git config --global user.name "Tu Nombre"
```

### Configurar email
```bash
git config --global user.email "tuemail@email.com"
```

### Ver configuración actual
```bash
git config --list
```

---

## 📁 Crear y conectar repositorios

### Inicializar un repositorio en un proyecto
```bash
git init
```

### Clonar un repositorio existente
```bash
git clone URL_DEL_REPOSITORIO
```

---

## 📝 Flujo básico de trabajo

### Ver el estado del repositorio
```bash
git status
```

### Añadir archivo al staging
```bash
git add nombre-archivo
```

### Añadir todos los archivos
```bash
git add .
```

### Crear un commit
```bash
git commit -m "Mensaje descriptivo del commit"
```

---

## 🌿 Trabajo con ramas

### Ver ramas existentes
```bash
git branch
```

### Crear nueva rama
```bash
git branch nombre-rama
```

### Cambiar de rama
```bash
git checkout nombre-rama
```

### Crear y cambiar en un solo paso
```bash
git checkout -b nombre-rama
```

---

## 🔄 Sincronización con remoto

### Conectar repositorio local a remoto
```bash
git remote add origin URL_DEL_REPOSITORIO
```

### Subir cambios al repositorio remoto
```bash
git push origin nombre-rama
```

### Descargar cambios del remoto
```bash
git pull origin nombre-rama
```

---

## 🚀 Flujo típico resumido

```bash
git add .
git commit -m "Descripción clara del cambio"
git push origin main
```

---

## 💡 Buenas prácticas

- Haz commits pequeños y descriptivos.
- Usa ramas para nuevas funcionalidades.
- Mantén tu rama `main` estable.
- Haz `pull` antes de empezar a trabajar.

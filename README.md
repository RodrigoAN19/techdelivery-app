# TechDelivery App 🚚

Aplicación web que permite a los usuarios ver el estado de sus pedidos en tiempo real.

## Tecnologías utilizadas
- Node.js + Express
- Jenkins (CI/CD)
- Docker
- GitHub

## Flujo CI/CD
VS Code → GitHub → Jenkins

## Cómo ejecutar localmente

1. Instalar dependencias:
```bash
   npm install
```

2. Iniciar la aplicación:
```bash
   node app.js
```

3. Abrir en el navegador: `http://localhost:3000`

## Pipeline Jenkins
Cada vez que se hace push al repositorio, Jenkins ejecuta automáticamente:
1. Clonar el repositorio
2. Instalar dependencias
3. Ejecutar pruebas
4. Publicar la aplicación
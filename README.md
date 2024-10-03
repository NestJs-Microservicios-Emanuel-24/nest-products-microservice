# 🛍️ Product Microservice by Emanuel Chusgo

## 🚀 Configuración para Desarrollo

### Prerrequisitos

- Node.js (versión recomendada: 14.x o superior)
- npm (normalmente viene con Node.js)
- Git

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/product-microservice.git
   cd product-microservice
   ```

2. **Instalar las dependencias**
   ```bash
   npm install
   ```

3. **Configurar las variables de entorno**
   - Crea un archivo `.env` en la raíz del proyecto
   - Añade las siguientes variables (ajusta los valores según sea necesario):
     ```
     DATABASE_URL="postgresql://usuario:contraseña@localhost:5432/nombre_db"
     PORT=3000
     ```

4. **Ejecutar la migración de Prisma**
   ```bash
   npx prisma migrate dev
   ```

5. **Iniciar el servidor de desarrollo**
   ```bash
   npm run start:dev
   ```

## 📚 Documentación Adicional

Para más información sobre cómo usar este microservicio, consulta la [documentación completa](link-a-tu-documentacion).

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor, lee las [guías de contribución](link-a-tus-guias) antes de enviar un pull request.

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
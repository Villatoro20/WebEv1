**#Caracteristicas Principales**

- **Consulta de pedidos:** Los clientes pueden ingresar su número de cliente y número de factura para ver el estado de sus pedidos.
- **Gestión de pedidos:** Los empleados pueden ingresar, modificar y actualizar pedidos en función de su rol.
- **Ciclo de vida de los pedidos:** Los pedidos pasan por varias etapas: Ordenado, En proceso, En ruta, y Entregado.
- **Subida de fotos:** El departamento de rutas puede subir fotos como evidencia de la entrega.
- **Gestión de usuarios y roles:** Un administrador puede crear nuevos usuarios y asignarles roles específicos (Ventas, Compras, Almacén, Ruta).

**##Estructura del proyecto**
halcon-materiales-app/
├── public/                # Archivos estáticos (imágenes, CSS, JS)
├── src/                   # Código fuente principal de la aplicación
│   ├── components/        # Componentes reutilizables de la UI
│   ├── pages/             # Páginas de la aplicación (Dashboard, Pedidos, etc.)
│   └── services/          # Servicios para lógica de negocio y conexión con la base de datos
├── diagrams/              # Diagramas de arquitectura (BPMN, ERD, etc.)
├── docs/                  # Documentación técnica adicional
├── README.md              # Documentación general del proyecto
├── .gitignore             # Lista de archivos/folders que no se subirán al repo
└── package.json           # Dependencias del proyecto y scripts de npm
**###Tecnologias Utilizadas**
- Front end
  1. React.js (o la tecnología de frontend elegida)
  2. HTML5, CSS3, JavaScript/TypeScript
- BackEnd
  1. Node.js con Express.js (o el framework backend elegido)
  2. Autenticación JWT para roles de usuario
- Base de datos
  1. MySQL para la gestión de datos de usuarios, pedidos y fotos
- Otros
  1. Git para control de versiones
  2. GitHub Actions (opcional) para CI/CD
  3. Docker (opcional) para contenerización
**####Scripts disponibles**
1. npm run dev: Inicia el servidor de desarrollo.
2. npm run build: Compila el proyecto para producción.
3. npm run start: Inicia la aplicación en modo producción.
**#####Funcionalidades futuras**
- Envío de facturas automáticas por correo electrónico.
- Sistema de notificaciones para los clientes cuando el estado de sus pedidos cambia.
- Reportes y estadísticas para el administrador.
- Mejoras en la seguridad (autenticación 2FA, por ejemplo).
**######Contribuciones**
- Haz un fork del repositorio.
- Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
- Realiza tus cambios y haz commit (git commit -m "Añadida nueva funcionalidad").
- Sube tus cambios a la rama (git push origin feature/nueva-funcionalidad).
- Crea un pull request en GitHub.

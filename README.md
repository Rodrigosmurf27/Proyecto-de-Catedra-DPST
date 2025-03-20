Venmol - Sistema de Inventario
Descripción del Proyecto
Venmol es una aplicación móvil desarrollada en React Native para la gestión interna del inventario de la microempresa Venmol. Está diseñada exclusivamente para empleados y jefes, permitiendo el control de stock, registro de ventas y visualización de movimientos de inventario en tiempo real.
Características
•	📦 Registro y control de inventario: Gestión de productos con nombre, cantidad, categoría y precio.
•	🛒 Registro de ventas: Actualización automática del stock tras cada venta.
•	📊 Historial de movimientos: Registro detallado de productos vendidos con fecha y usuario.
•	🔔 Alertas de stock bajo: Notificación cuando un producto está por agotarse.
•	🔑 Autenticación de usuarios: Roles diferenciados para empleados y jefes.
Tecnologías Utilizadas
•	Frontend: React Native
•	Backend: Node.js con Express
•	Base de Datos: Firebase Firestore
•	Control de Versiones: GitHub
•	Gestión del Proyecto: Trello / Notion
•	Contenedorización: Docker y Kubernetes
Instalación y Configuración
Requisitos previos
•	Node.js instalado (>= 14.x)
•	Expo CLI (npm install -g expo-cli)
•	Firebase configurado con claves de API
•	Docker y Kubernetes instalados para el despliegue
Pasos de instalación
1.	Clona el repositorio:
2.	Instala las dependencias:
3.	Configura las credenciales de Firebase en un archivo .env.
4.	Inicia la aplicación en modo desarrollo:
5.	Para construir la aplicación para Android e iOS:
Uso de la Aplicación
•	Empleados: Pueden registrar ventas y actualizar el stock.
•	Jefes: Pueden visualizar reportes y monitorear movimientos del inventario.
Despliegue con Docker y Kubernetes
1.	Construir la imagen Docker:
2.	Ejecutar el contenedor:
3.	Desplegar en Kubernetes:
Contribuciones
¡Las contribuciones son bienvenidas! Para contribuir:
1.	Realiza un fork del repositorio.
2.	Crea una rama con tu mejora (git checkout -b feature/nueva-funcionalidad).
3.	Sube los cambios (git commit -m 'Agrega nueva funcionalidad').
4.	Envía un Pull Request.
Integrantes
Bonilla Perez William Adonay - BP220765
Velasco Herrera Rodrigo Alberto - VH192433
Rivera Linares Julio David - RL241378
Sandoval Guillen Evelyn Marisol - SG210007
Sanchez Campos Rolando Ezequiel - SC231259

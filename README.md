Venmol - Sistema de Inventario

Descripción del Proyecto

Venmol es una aplicación móvil desarrollada en React Native para la gestión interna del inventario de la microempresa Venmol. Está diseñada exclusivamente para empleados y jefes, permitiendo el control de stock, registro de ventas y visualización de movimientos de inventario en tiempo real.

Características

📦 Registro y control de inventario: Gestión de productos con nombre, cantidad, categoría y precio.

🛒 Registro de ventas: Actualización automática del stock tras cada venta.

📊 Historial de movimientos: Registro detallado de productos vendidos con fecha y usuario.

🔔 Alertas de stock bajo: Notificación cuando un producto está por agotarse.

🔑 Autenticación de usuarios: Roles diferenciados para empleados y jefes.

Tecnologías Utilizadas

Frontend: React Native

Backend: Node.js con Express

Base de Datos: Firebase Firestore

Control de Versiones: GitHub

Gestión del Proyecto: Trello / Notion

Contenedorización: Docker y Kubernetes

Instalación y Configuración

Requisitos previos

Antes de comenzar, asegúrate de tener instalados los siguientes requisitos:

Node.js (>= 14.x)

Expo CLI (npm install -g expo-cli)

Firebase configurado con claves de API

Docker y Kubernetes instalados para el despliegue

Pasos de instalación

Clona el repositorio:

Ingresa al directorio del proyecto:

Instala las dependencias:

Configura las credenciales de Firebase en un archivo .env.

Inicia la aplicación en modo desarrollo:

Para construir la aplicación para Android e iOS:

Uso de la Aplicación

Empleados: Pueden registrar ventas y actualizar el stock.

Jefes: Pueden visualizar reportes y monitorear movimientos del inventario.

Despliegue con Docker y Kubernetes

Construcción y ejecución con Docker

Construir la imagen Docker:

Ejecutar el contenedor:

Despliegue en Kubernetes

Aplicar la configuración de Kubernetes:

Verificar los pods en ejecución:

Contribuciones

¡Las contribuciones son bienvenidas! Para contribuir, sigue estos pasos:

Realiza un fork del repositorio.

Crea una rama con tu mejora:

Realiza los cambios y sube los commits:

Envía un Pull Request.

Integrantes

Bonilla Perez William Adonay - BP220765

Velasco Herrera Rodrigo Alberto - VH192433

Rivera Linares Julio David - RL241378

Sandoval Guillen Evelyn Marisol - SG210007

Sanchez Campos Rolando Ezequiel - SC231259

# 🏥 Sistema de Gestión Veterinaria v2

Un sistema integral de gestión para clínicas veterinarias construido con PHP, que incluye un sistema seguro de inicio de sesión y operaciones CRUD completas para la gestión de registros veterinarios.

## 🌟 Características

- **🔐 Sistema de Autenticación Seguro**
  - Interfaz de inicio de sesión intuitiva
  - Función "Recordar sesión"
  - Gestión de sesiones

- **📊 Panel de Control**
  - Vista general de actividades de la clínica
  - Acceso rápido a funciones principales
  - Diseño adaptable a todos los dispositivos

- **💉 Gestión de Pacientes**
  - Agregar nuevos registros de pacientes
  - Actualizar información existente
  - Eliminar registros obsoletos
  - Ver historial detallado de pacientes

## 🛠️ Stack Tecnológico

- **Backend**
  - PHP
  - Base de datos MySQL
  - Arquitectura MVC

- **Frontend**
  - HTML5
  - CSS3
  - JavaScript
  - Diseño Responsivo

- **Estructura del Proyecto**
  ```
  ├── controllers/
  │   └── viewcontroller.php
  ├── css/
  │   ├── styles.css
  │   ├── stylesdashboard.css
  │   ├── styleseliminardatos.css
  │   ├── stylesingresardatos.css
  │   └── styleslogout.css
  ├── models/
  ├── views/
  │   ├── dashboard.php
  │   ├── eliminardatos.php
  │   ├── ingresardatos.php
  │   └── index.php
  └── test/
      └── testConfig.php
  ```

## 🚀 Instalación

1. **Clonar el Repositorio**
   ```bash
   git clone https://github.com/The-Nasa/MC_CONSTRUCION_SW.git
   ```

2. **Configuración de la Base de Datos**
   - Crear una base de datos MySQL
   - Importar el esquema SQL proporcionado
   - Configurar la conexión a la base de datos en `config.php`

3. **Configuración del Servidor**
   - Configurar tu servidor PHP (Apache/Nginx)
   - Asegurar que PHP versión 7.4+ esté instalado
   - Habilitar las extensiones PHP requeridas

4. **Iniciar la Aplicación**
   - Navegar a la URL del proyecto en tu navegador
   - Las credenciales predeterminadas están en la documentación

## 💻 Guía de Uso

1. **Sistema de Inicio de Sesión**
   - Acceder al sistema a través de la página de inicio de sesión
   - Ingresar credenciales
   - Opcional: Usar la función "Recordar sesión"

2. **Navegación del Panel de Control**
   - Acceder a diferentes módulos a través de la barra lateral
   - Acciones rápidas disponibles en el panel principal
   - Actualizaciones en tiempo real de datos de pacientes

3. **Registros de Pacientes**
   - Agregar nuevos pacientes con información detallada
   - Actualizar registros existentes según sea necesario
   - Ver historial completo de pacientes
   - Eliminar registros obsoletos de forma segura

## 🔍 Pruebas

- Pruebas unitarias disponibles en el directorio `/test`
- Ejecutar pruebas usando el framework de testing de PHP
- Listo para integración continua

## 🤝 Contribución

1. Hacer un fork del repositorio
2. Crear tu rama de características (`git checkout -b feature/NuevaCaracteristica`)
3. Hacer commit de tus cambios (`git commit -m 'Agregar NuevaCaracteristica'`)
4. Hacer push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abrir un Pull Request

## 📝 Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo LICENSE para más detalles.

## 📧 Contacto

Elías Tapullima - [meselemias.tapullima@unas.edu.pe](mailto:meselemias.tapullima@unas.edu.pe)

Enlace del Proyecto: [https://github.com/The-Nasa/MC_CONSTRUCION_SW](https://github.com/The-Nasa/MC_CONSTRUCION_SW)

---

Hecho con ❤️ por Elías Tapullima

# 🏥 Sistema de Gestión Veterinaria v2

Sistema integral de gestión para clínicas veterinarias, evolucionado desde una interfaz básica de login hasta un sistema completo con operaciones CRUD y gestión de registros veterinarios.

## 📋 Descripción General

Este proyecto ha evolucionado desde un simple formulario de inicio de sesión hasta convertirse en un sistema completo de gestión veterinaria. Proporciona una interfaz intuitiva y responsiva que se adapta a diferentes dispositivos, garantizando una experiencia de usuario óptima tanto en móviles como en escritorio.

## 🎨 Capturas de Pantalla

### Pantalla de Inicio de Sesión
![image](https://github.com/user-attachments/assets/a26bb454-bbf8-444e-aeb2-28cf58789bf1)

## 🌟 Características

- **🔐 Sistema de Autenticación Seguro**
  - Interfaz de inicio de sesión intuitiva
  - Función "Recordar sesión"
  - Gestión avanzada de sesiones
  - Diseño limpio y responsivo

- **📊 Panel de Control**
  - Vista general de actividades de la clínica
  - Acceso rápido a funciones principales
  - Diseño adaptable a todos los dispositivos
  - Actualizaciones en tiempo real

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
  - Principios SOLID

- **Frontend**
  - HTML5
  - CSS3
  - JavaScript
  - Diseño Responsivo
  - Clean Code

## 📂 Estructura del Proyecto
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
   - Usar las credenciales predeterminadas de la documentación

## 💻 Guía de Uso

1. **Sistema de Inicio de Sesión**
   - Acceder al sistema a través de la página de login
   - Ingresar credenciales
   - Opcional: Usar la función "Recordar sesión"

2. **Navegación del Panel de Control**
   - Acceder a diferentes módulos por la barra lateral
   - Acciones rápidas en el panel principal
   - Actualizaciones en tiempo real

3. **Gestión de Pacientes**
   - Registro completo de información
   - Actualización de historiales
   - Eliminación segura de registros
   - Consulta de historiales médicos

## 🔍 Pruebas

- Pruebas unitarias en el directorio `/test`
- Framework de testing de PHP
- Preparado para integración continua

## 🌐 Principios de Diseño

El proyecto sigue estrictamente:
- Principios SOLID
- Clean Code
- Arquitectura MVC
- Diseño Responsivo
- Mejores prácticas de seguridad

## 🤝 Contribución

1. Hacer fork del repositorio
2. Crear rama de características (`git checkout -b feature/NuevaCaracteristica`)
3. Commit de cambios (`git commit -m 'Agregar NuevaCaracteristica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abrir Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo LICENSE para detalles.

## 📧 Contacto

Elías Tapullima - [meselemias.tapullima@unas.edu.pe](mailto:meselemias.tapullima@unas.edu.pe)

Enlace del Proyecto: [https://github.com/The-Nasa/MC_CONSTRUCION_SW](https://github.com/The-Nasa/MC_CONSTRUCION_SW)

---

Hecho con ❤️ por Elías Tapullima

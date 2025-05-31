
# Banco Smith - Cajero Virtual (Colombia)

**Banco Smith** es una aplicación web de simulación de cajero automático desarrollada con **Spring Boot** y diseñada con una estética inspirada en el Pacífico colombiano. Permite a los usuarios y administradores realizar operaciones bancarias comunes como creación de cuentas, retiros, consignaciones, transferencias, consultas y más.

## 🛠️ Tecnologías

- Java 17
- Spring Boot (Spring MVC + Spring Data JPA)
- Thymeleaf
- MySQL (con script SQL incluido)
- HTML5 + CSS3 personalizado
- Bootstrap 5 + FontAwesome

## 🚀 Funcionalidades

- Registro y gestión de clientes
- Creación de cuentas bancarias por tipo (ahorros o corriente)
- Inicio de sesión con número de cuenta y PIN
- Acciones para el cliente:
  - Retiros
  - Consignaciones
  - Transferencias
  - Cambio de clave
  - Consulta de movimientos
- Acciones para el administrador:
  - Crear clientes
  - Crear cuentas
  - Desbloquear clientes
- Control de acceso y seguridad por rol
- Estética profesional inspirada en entidades bancarias colombianas

## 📁 Estructura del Proyecto

```
BancoSmith/
├── src/
│   ├── main/
│   │   ├── java/com/fortbank/BancoSmith/
│   │   │   ├── controller/         # Controladores web (Admin, Cajero)
│   │   │   ├── dto/                # Objetos de transferencia de datos
│   │   │   ├── entity/             # Entidades JPA (Cliente, Cuenta, Movimiento, etc.)
│   │   │   ├── repository/         # Repositorios Spring Data JPA
│   │   │   └── services/           # Lógica de negocio
│   │   └── resources/
│   │       ├── static/styles/      # Archivos CSS personalizados
│   │       └── templates/          # Vistas Thymeleaf (HTML)
│   └── test/                       # Pruebas unitarias y de integración
├── banco_smith.sql                 # Script SQL para crear base de datos en MySQL/phpMyAdmin
├── pom.xml                         # Archivo de configuración de Maven
└── README.md                       # Este archivo
```

## 📌 Requisitos previos

- Java 17 o superior
- Maven 3.6+
- MySQL Server o XAMPP con phpMyAdmin

## 🧪 Instalación y ejecución

1. Clona el repositorio:
```bash
git clone https://github.com/tuusuario/banco-smith.git
cd banco-smith
```

2. Importa `banco_smith.sql` en phpMyAdmin para crear la base de datos.

3. Configura `application.properties` con tus credenciales de MySQL.

4. Ejecuta el proyecto:
```bash
./mvnw spring-boot:run
# O si tienes Maven instalado globalmente
mvn spring-boot:run
```

5. Accede en tu navegador:
- [http://localhost:8081/admin](http://localhost:8081/admin) (Administrador)
- [http://localhost:8081/cajero/login](http://localhost:8081/cajero/login) (Cajero)

## 🖼️ Capturas de Pantalla

- ![Menú de administración](./capturas/Menu-administracion.png)
- ![Login](./capturas/Login.png)
- ![Menú del cajero](./capturas/Menu-Cajero.png)

## 👨‍💻 Créditos

Desarrollado por Kevin Vélez con la guía del docente Daniel para la materia de Construcción de Software.

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

---

¿Tienes dudas o sugerencias? Abre un issue o contacta al autor. ¡Gracias por visitar el proyecto!


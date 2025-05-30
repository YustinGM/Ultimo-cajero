# 🏦 CajeroBancoSMITH - Proyecto Spring Boot + MySQL

Este proyecto es un simulador de cajero automático bancario desarrollado con **Spring Boot**, **MySQL**, **Thymeleaf** y **HTML/CSS**. Permite la creación de usuarios, cuentas, desbloqueo de cuentas, y simula transacciones básicas bancarias.

## 🎯 Objetivos

- Aplicar conocimientos de Java y Spring Boot.
- Implementar una conexión a base de datos con MySQL.
- Crear una interfaz web funcional con HTML, CSS y Thymeleaf.
- Simular operaciones de un cajero automático con lógica de negocio real.

## 🚀 Funcionalidades principales

- ✅ Crear cliente (admin)
- ✅ Crear cuenta bancaria (admin)
- ✅ Desbloquear cuenta (admin)
- ✅ Realizar operaciones como retiro, consignación, consulta de saldo (usuario)
- ✅ Login seguro con validación
- ✅ Conexión a base de datos MySQL desde Spring Boot

## 🔧 Tecnologías usadas

- Java 17
- Spring Boot 3
- Spring Data JPA
- MySQL
- HTML5 + CSS3
- Thymeleaf
- XAMPP / phpMyAdmin

## 🗂️ Estructura del proyecto

```bash
src/
├── main/
│   ├── java/
│   │   └── com/banco/smith/
│   │       ├── controllers/
│   │       ├── models/
│   │       ├── repositories/
│   │       ├── services/
│   │       └── MiCajeroSMITHApplication.java
│   └── resources/
│       ├── static/
│       │   ├── css/
│       │   └── images/
│       ├── templates/
│       │   └── *.html
│       └── application.properties

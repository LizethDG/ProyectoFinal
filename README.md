# Spring Boot Proyecto de Autenticación

Este proyecto es un sistema de autenticación básico utilizando **Spring Boot**, **Spring Security** y **MySQL**. El sistema permite a los usuarios registrarse, iniciar sesión y acceder a recursos protegidos según su rol (usuario o administrador).

## Características

- **Autenticación de usuarios** utilizando nombre de usuario (correo electrónico) y contraseña.
- **Roles y permisos**:
  - Los usuarios pueden acceder a sus perfiles y secciones privadas.
  - Los administradores tienen acceso a rutas y recursos adicionales.
- **Protección de rutas** usando **Spring Security**.
- **Hashing de contraseñas** con **BCrypt** para mejorar la seguridad.
- **Inicio de sesión y registro** con formularios personalizados.

## Tecnologías Utilizadas

- **Spring Boot 2.x**
- **Spring Security**
- **MySQL** (base de datos)
- **Thymeleaf** (para vistas)
- **BCryptPasswordEncoder** (para encriptar contraseñas)
- **JWT** (si se implementa autenticación basada en tokens)
- **Spring Data JPA** (para acceso a la base de datos)

## Requisitos Previos

Antes de ejecutar este proyecto, asegúrate de tener instalados los siguientes programas:

- [JDK 11 o superior](https://adoptopenjdk.net/)
- [Maven](https://maven.apache.org/install.html) o [Gradle](https://gradle.org/install/)
- [MySQL](https://www.mysql.com/)

## Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/LizethDG/ProyectoFinal.git

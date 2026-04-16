# 🛒 E-Commerce Accesorios D&M

## 📌 Descripción del Proyecto

**Accesorios D&M** es un emprendimiento que actualmente comercializa productos a través de Instagram y WhatsApp, gestionando los pedidos de forma manual.

Este proyecto tiene como objetivo desarrollar un **Sistema Distribuido tipo E-Commerce**, bajo una arquitectura de **microservicios**, que permita digitalizar y centralizar la gestión de:

- Catálogo de productos
- Pedidos
- Inventario
- Administración del negocio

El sistema será desarrollado bajo metodología **Scrum**, iniciando con la construcción de un **MVP (Producto Mínimo Viable)**.

---

## 👥 Integrantes

1. Dayana Motta Camayo
2. Juan Sebastian Agudelo Quintero
3. Dany Yulieth Campos Bustos
4. Sergio Andres Losada Bahamón

---

## 🚀 Arquitectura del Proyecto

El sistema está diseñado bajo una arquitectura de **microservicios**, separando responsabilidades en distintos repositorios:

- 🔹 [Portal Web (Frontend)](https://github.com/dayana2100/accesorios-dm-frontend.git)
- 🔹 [App Mobile](https://github.com/dayana2100/accesorios-dm-mobile.git)
- 🔹 [Backend API gateway](https://github.com/dayana2100/accesorios-dm-api-gateway.git)
- 🔹 [Modulo de Inventario](https://github.com/dayana2100/accesorios-dm-inventory-service.git)
- 🔹 [Modulo de Pago](https://github.com/dayana2100/accesorios-dm-payment-service.git)
- 🔹 [Modulo de Seguridad](https://github.com/dayana2100/accesorios-dm-security-service.git)
- 🔹 [Base de Datos](https://github.com/dayana2100/accesorios-dm-database.git)

---

## 📌 Convención de Commits

Todos los repositorios siguen el estándar **Conventional Commits**:

| Tipo     | Uso                     | Ejemplo                           |
| -------- | ----------------------- | --------------------------------- |
| feat     | Nueva funcionalidad     | feat: agregar login de usuario    |
| fix      | Corrección de errores   | fix: corregir validación de email |
| docs     | Documentación           | docs: actualizar README           |
| chore    | Tareas de mantenimiento | chore: configurar CI/CD           |
| refactor | Refactorización         | refactor: extraer servicio auth   |

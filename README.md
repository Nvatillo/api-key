# 🔑 API Key Authentication Demo (Spring Boot)

Este proyecto es un ejemplo básico de cómo proteger una API REST usando **API Keys** en **Spring Boot**.

## 💡 ¿Qué es una API Key?

Una API Key es una cadena única que identifica a un cliente o aplicación que intenta acceder a una API. Es un mecanismo simple de autenticación.

## 🚀 Cómo funciona este ejemplo

- Cada solicitud debe incluir el header `X-API-KEY` con el valor `123456`.
- Si la clave no es válida, el servidor devuelve `401 Unauthorized`.

## 📬 Endpoint

- `GET /hello` → protegido con API Key.

### 🔐 Header necesario


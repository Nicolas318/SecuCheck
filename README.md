# 🔒 SecuCheck – Security Dashboard Personal

**SecuCheck** es una aplicación **auto-hosted** que centraliza herramientas de seguridad digital en un único dashboard sencillo y práctico.  
Está pensada para uso **personal o familiar**, con énfasis en simplicidad y privacidad.

## ✨ Funcionalidades

- 🗝️ **Gestor de contraseñas local**  
  Guarda tus credenciales en una base de datos cifrada en tu propio servidor o PC.  

- 📧 **Chequeo de filtraciones**  
  Comprueba si tus correos o contraseñas han aparecido en brechas de datos públicas (*Have I Been Pwned*).  

- 📡 **Escaneo de red local**  
  Detecta dispositivos conectados a tu red doméstica para identificar posibles intrusos.  

- 📊 **Dashboard con métricas**  
  Visualización de contraseñas seguras, alertas de filtraciones y dispositivos en red con gráficas.  

- 🔐 **Autenticación con 2FA** (en roadmap).  

---

## 🛠️ Tecnologías

- **Backend**: [FastAPI](https://fastapi.tiangolo.com/) (Python)  
- **Frontend**: [React](https://react.dev/) + [TailwindCSS](https://tailwindcss.com/)  
- **Base de datos**: SQLite con [SQLCipher](https://www.zetetic.net/sqlcipher/) para cifrado  
- **Contenedores**: Docker + Docker Compose  

---

## 🚀 Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/SecuCheck.git
   cd SecuCheck
   ```

2. Levanta el entorno con Docker Compose:
   ```bash
   docker-compose up --build
   ```

3. Accede a la app en:  
   👉 [http://localhost:3000](http://localhost:3000)

---

## 📌 Roadmap

- [ ] Login con 2FA (TOTP)  
- [ ] Caja de contraseñas cifrada  
- [ ] Exportación/importación segura  
- [ ] Integración completa con Have I Been Pwned  
- [ ] Escaneo de red con detección de intrusos  
- [ ] Dashboard con gráficas dinámicas  

---

## 🤝 Contribución

Las PRs y sugerencias son bienvenidas.  
Si quieres colaborar, abre un *issue* o envía una *pull request*.  

---

## 📜 Licencia

Este proyecto se distribuye bajo la licencia **MIT**.  
Consulta el archivo [LICENSE](./LICENSE) para más detalles.  

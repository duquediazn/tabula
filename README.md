# Tábula

## Español

**Tábula** es una aplicación de gestión de inventario con paneles visuales y control en tiempo real, inspirada en los orígenes históricos de la contabilidad y la logística.

Su nombre hace referencia a las *tabulae* romanas, las primeras herramientas de registro manual usadas por escribas para administrar recursos del Estado, los templos y el comercio.

---

## Tecnologías utilizadas

### Backend
-  [FastAPI](https://fastapi.tiangolo.com/)
-  PostgreSQL
-  SQLModel
-  Autenticación JWT (con access y refresh tokens)
-  WebSockets para notificaciones en tiempo real

### Frontend
-  React (con Vite)
-  Tailwind CSS
-  Gráficas con Recharts
-  Gestión de sesión con JWT + Cookies HttpOnly

---

## Repositorios del proyecto

- [Backend: tabula-backend](https://github.com/duquediazn/tabula-backend) 
- [Frontend: tabula-frontend](https://github.com/duquediazn/tabula-frontend) 

---

## Funcionalidades principales

- Registro y autenticación de usuarios
- Panel de control con gráficas interactivas
- CRUD completo de productos, almacenes y movimientos de stock
- Categorización y filtrado avanzado
- Soporte para productos por lote y fecha de caducidad
- Sistema de roles y protección de rutas
- Websockets para actualizaciones en tiempo real

---

## Instalación local (opcional)

Si quieres clonar y probar el proyecto en tu máquina:

```bash
# Backend
git clone https://github.com/duquediazn/tabula-backend.git

# Frontend
git clone https://github.com/duquediazn/tabula-frontend.git
```

## Licencia
Este proyecto está licenciado bajo los términos de la GNU General Public License v3.0.

Consulta el archivo LICENSE para más detalles.


---


## English

**Tábula** is an inventory management application with visual dashboards and real-time control, inspired by the historical origins of accounting and logistics.

The name refers to the *tabulae* of ancient Rome — wax tablets used by scribes as some of the earliest tools for manually recording and managing state, temple, and commercial resources.

---

## Technologies Used

### Backend
-  [FastAPI](https://fastapi.tiangolo.com/)
-  PostgreSQL
-  SQLModel
-  JWT Authentication (access and refresh tokens)
-  WebSockets for real-time notifications

### Frontend
-  React (with Vite)
-  Tailwind CSS
-  Charts with Recharts
-  Session management using JWT + HttpOnly Cookies

---

## Project Repositories

- [Backend: tabula-backend](https://github.com/duquediazn/tabula-backend) 
- [Frontend: tabula-frontend](https://github.com/duquediazn/tabula-frontend)

---

## Main Features

- User registration and authentication
- Dashboard with interactive graphs
- Full CRUD for products, warehouses, and stock movements
- Categorization and advanced filtering
- Batch and expiration date support for products
- Role-based access and route protection
- WebSockets for real-time updates

---

## Local Installation (optional)

To clone and test the project locally:

```bash
# Backend
git clone https://github.com/duquediazn/tabula-backend.git

# Frontend
git clone https://github.com/duquediazn/tabula-frontend.git
```

## License
This project is licensed under the terms of the GNU General Public License v3.0.

See the LICENSE file for more details.

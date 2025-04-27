# Tábula

## Español

**Tábula** es una aplicación de gestión de inventario con paneles visuales y control en tiempo real, inspirada en los orígenes históricos de la contabilidad y la logística.

Su nombre hace referencia a las *tabulae* romanas, las primeras herramientas de registro manual usadas por escribas para administrar recursos del Estado, los templos y el comercio.

---

## Tecnologías utilizadas

### Backend
- [FastAPI](https://fastapi.tiangolo.com/) (Python 3.11+)
- [PostgreSQL](https://www.postgresql.org/)
- [SQLModel](https://sqlmodel.tiangolo.com/) + [SQLAlchemy](https://www.sqlalchemy.org/) (ORM)
- Autenticación JWT (access y refresh tokens)
- [WebSocket](https://developer.mozilla.org/es/docs/Web/API/WebSockets_API) para notificaciones en tiempo real

### Frontend
- [React 19](https://react.dev/) (con [Vite](https://vitejs.dev/))
- [Tailwind CSS](https://tailwindcss.com/)
- [React Router v7](https://reactrouter.com/en/main)
- Gráficas con [Recharts](https://recharts.org/) (gráficas de stock)
- [Context API](https://react.dev/learn/passing-data-deeply-with-context) para gestión de autenticación
- Gestión de sesión con JWT + Cookies HttpOnly


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
- Websocket para actualizaciones en tiempo real

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
- [FastAPI](https://fastapi.tiangolo.com/) (Python 3.11+)
- [PostgreSQL](https://www.postgresql.org/)
- [SQLModel](https://sqlmodel.tiangolo.com/) + [SQLAlchemy](https://www.sqlalchemy.org/) (ORM)
- JWT Authentication (access and refresh tokens)
- [WebSocket](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API) for real-time notifications

### Frontend
- [React 19](https://react.dev/) (with [Vite](https://vitejs.dev/))
- [Tailwind CSS](https://tailwindcss.com/)
- [React Router v7](https://reactrouter.com/en/main)
- Charts with [Recharts](https://recharts.org/) (stock graphs)
- [Context API](https://react.dev/learn/passing-data-deeply-with-context) for authentication management
- Session management with JWT + HttpOnly Cookies


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

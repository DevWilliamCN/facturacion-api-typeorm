
# 🧾 Facturación API con TypeORM

Sistema backend completo para la gestión de facturación, construido con Node.js, Express y TypeORM sobre una base de datos MySQL.

![GitHub repo size](https://img.shields.io/github/repo-size/DevWilliamCN/facturacion-api-typeorm?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/DevWilliamCN/facturacion-api-typeorm?style=flat-square)
![Made with TypeScript](https://img.shields.io/badge/Made%20with-TypeScript-blue?style=flat-square)
![License](https://img.shields.io/github/license/DevWilliamCN/facturacion-api-typeorm?style=flat-square)

---

## 🚀 Tecnologías utilizadas

- **Node.js** + **Express**
- **TypeScript**
- **TypeORM**
- **MySQL**
- **class-validator**
- **Helmet**, **CORS**
- **JWT + Bcrypt** (preparado para seguridad de autenticación)

---

## 📦 Instalación y ejecución

```bash
# Clona el repositorio
git clone https://github.com/DevWilliamCN/facturacion-api-typeorm.git
cd facturacion-api-typeorm

# Instala dependencias
npm install

# Configura la base de datos en src/data-source.ts

# Inicia en modo desarrollo
npm run dev
```

> Asegúrate de tener MySQL corriendo y una base de datos llamada `web02`.

---

## 🛠️ Estructura del proyecto

```
📦 src/
├── entity/            # Entidades TypeORM (Producto, Cliente, etc.)
├── routes/            # Rutas organizadas por entidad
├── data-source.ts     # Conexión a MySQL con TypeORM
└── index.ts           # Entrada principal del servidor
```

---

## 🧪 Endpoints REST disponibles (ejemplo)

```
GET    /productos
POST   /productos
PUT    /productos/:id
DELETE /productos/:id
```

*(Ver `src/routes/` para todos los endpoints disponibles)*

---

## ✅ Funcionalidades principales

- Gestión de productos, clientes, proveedores y facturas
- Relaciones entre entidades (cabecera/detalle de factura)
- Validación de datos con `class-validator`
- Seguridad con `helmet` y `cors`
- Arquitectura organizada y escalable

---

## 🔐 Seguridad y buenas prácticas

- Separación de rutas, entidades y controladores
- Código limpio y modular
- `.gitignore` configurado para evitar fugas
- Preparado para autenticación con JWT (en implementación)

---

## 👨‍💻 Autor

**William Cubero Navarro**  
Desarrollador Backend & Fullstack | [GitHub @DevWilliamCN](https://github.com/DevWilliamCN)

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.

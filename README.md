
# 🛍️ eCommerce API

**API RESTful para la gestión de un sistema de comercio electrónico.**  
Incluye autenticación, administración de productos, carritos, órdenes y pagos.

---

## 🚀 Funcionalidades

- 🔐 Registro, login y autenticación JWT
- 👤 Gestión de usuarios (cliente y administrador)
- 🛒 Productos, categorías, stock y variantes
- 📦 Carrito de compras y creación de órdenes
- 💳 Integración opcional con pasarela de pagos (ej. Stripe, MercadoPago)
- 📈 Panel de administración con estadísticas
- 🔒 Seguridad: CORS, rate limiting, sanitización de inputs

---

## 🛠️ Tecnologías

- **Backend:** Node.js + Express  
- **Base de datos:** MongoDB  
- **ORM/ODM:** Mongoose  
- **Autenticación:** JWT + bcrypt  
- **Documentación API:** Swagger  
- **Correo electrónico:** SendGrid  
- **Storage:** Cloudinary / Local  
- **Otros:** Firebase (si usás auth externa), Strapi (si hay CMS vinculado)

---

## 🧰 Instalación

```bash
git clone https://github.com/tuusuario/ecommerce-api.git
cd ecommerce-api
npm install
npm run dev
```

Configurar variables de entorno en un archivo `.env`:

```env
PORT=3000
MONGO_URI=mongodb://localhost:27017/ecommerce
JWT_SECRET=tu_clave_secreta
SENDGRID_API_KEY=...
```

---

## 📄 Documentación de la API

Accedé a la documentación en `/api-docs` (Swagger).

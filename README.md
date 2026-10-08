# 🍰 Aplicación Móvil - Catálogo y Pedidos de Pastelería

Bienvenido al repositorio oficial del sistema de pedidos y gestión de envíos para pastelería. Esta aplicación móvil permite a los clientes explorar el catálogo de productos, gestionar sus sesiones de forma segura y realizar pedidos calculando automáticamente las restricciones de transporte según peso, tamaño y distancia.

---

## 🚀 Características Principales

* **🔑 Autenticación Persistente:** Inicio de sesión y registro de usuarios con almacenamiento local seguro (`AsyncStorage`).
* **🎂 Catálogo Interactivo:** Selección dinámica de pasteles con ajuste de cantidades y cálculo en tiempo real.
* **🚚 Validación de Transporte:** Control de restricciones de logística (Bicicleta, Moto, Carro, Furgoneta) según la capacidad de carga (kg) y distancia de entrega (km).
* **📱 Interfaz Enfocada en UX:** Navegación clara, alertas informativas y flujo visual optimizado para el usuario final.

---

## 🛠️ Tecnologías Utilizadas

* **Frontend Móvil:** React Native / Expo
* **Almacenamiento Local:** AsyncStorage
* **Lenguaje:** JavaScript (ES6+)
* **Documentación:** MkDocs / Markdown

---

## 📂 Estructura del Proyecto

```text
├── DocumentonWeb/
│   ├── assets/
│   │   ├── flujo_navegacion.png
│   │   ├── login_anotado.png
│   │   └── registro_anotado.png
│   └── manual_usuario_ux.md
├── src/
│   ├── components/
│   ├── screens/
│   └── utils/
├── mkdocs.yml
├── README.md
└── package.json
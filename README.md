# Proyecto Web - Gestión de Tareas

Este es un sistema de gestión de tareas que permite crear, visualizar, actualizar y eliminar tareas. Está desarrollado con tecnologías web modernas:

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js (Express)
- Base de datos: MySQL

---

## Requisitos mínimos

Antes de instalar el proyecto, asegúrate de tener lo siguiente:

- **Node.js** v18 o superior
- **MySQL** instalado y funcionando (local o remoto)
- **Git** instalado
- Editor recomendado: Visual Studio Code

---

## Configuración e instalación

Sigue estos pasos para clonar y ejecutar el proyecto en tu máquina:

### 1. Clona el repositorio

```bash
git clone https://github.com/tu-usuario/proyecto-gestion-tareas.git
cd proyecto-gestion-tareas
```

### 2. Instala las dependencias del backend

```bash
npm install
```

### 3. Configura las variables de entorno

Crea un archivo `.env` en la raíz del proyecto con la siguiente estructura:

```env
DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASSWORD=tu_contraseña
DB_NAME=gestion_tareas
PORT=3000
```

> Asegúrate de que tu base de datos MySQL tenga un esquema llamado `gestion_tareas` y que los datos de acceso sean correctos.

### 4. Importa la base de datos

- Abre tu cliente de MySQL (phpMyAdmin, DBeaver, CLI, etc.)
- Importa el archivo `database/schema.sql` incluido en el repositorio

```bash
mysql -u root -p gestion_tareas < database/schema.sql
```

### 5. Ejecuta el servidor

```bash
npm start
```

> El servidor correrá en `http://localhost:3000`

### 6. Abre el proyecto en el navegador

```url
http://localhost:3000
```

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Descripción |
|------------|-------------|
| HTML/CSS   | Interfaz de usuario responsiva |
| JavaScript | Lógica del frontend |
| Node.js + Express | Servidor backend y API |
| MySQL | Base de datos relacional |
| dotenv | Gestión de variables de entorno |
| nodemon | Recarga automática del servidor en desarrollo |

---

## Licencia

Este proyecto está bajo la licencia **MIT**. Puedes usarlo, modificarlo y compartirlo libremente con atribución.

---

## Contacto

Si tienes preguntas o sugerencias, puedes escribirme a:  
tuemail@correo.com  
GitHub: [@tu-usuario](https://github.com/tu-usuario)

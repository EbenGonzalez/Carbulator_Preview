# :mortar_board: REPOSITORIO A LA ESPERA DE NOTA PARA PODER PUBLICARLO

# 🧮 Carbulator: Contador de hidratos de carbono

**Carbulator** es una aplicación web desarrollada como parte del Ciclo Superior de Desarrollo de Aplicaciones Web. Su objetivo es ayudar a personas con diabetes o sus cuidadores, a calcular la cantidad de hidratos de carbono consumidos en los alimentos de forma rápida y sencilla.

## 🚀 Tecnologías utilizadas

### 🧩 Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![JSX](https://img.shields.io/badge/JSX-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)

### 🛠️ Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white)

### 🗄️ Base de datos
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![phpMyAdmin](https://img.shields.io/badge/phpMyAdmin-F89C0E?style=for-the-badge&logo=php&logoColor=white)
![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=for-the-badge&logo=apache&logoColor=white)

### 🧰 Herramientas y control de versiones
![VSCode](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)


## 🎯 Funcionalidades principales

- ✅ Registro e inicio de sesión de usuarios
- ✅ Añadir, editar y eliminar alimentos
- ✅ Clasificación por categorías
- ✅ Visualización de hidratos de carbono por cada 100g
- ✅ Cálculo multiple de alimentos
- ✅ Interfaz adaptada a dispositivos móviles
- 🔜 Futuras mejoras: conversión app

## 🛠️ Instalación y uso

Para una correcta instalación de **Carbulator** en un entorno local con **Windows**, es necesario tener previamente instaladas las siguientes herramientas:

- 🔹 [Node.js](https://nodejs.org/): entorno de ejecución para JavaScript en el backend.
- 🔹 [XAMPP](https://www.apachefriends.org/): para arrancar los servicios Apache y MySQL, y acceder a phpMyAdmin.
- 🔹 [Visual Studio Code](https://code.visualstudio.com/): editor de código recomendado (el que usamos durante el desarrollo).
- 🔹 [Google Chrome](https://www.google.com/intl/es/chrome/): navegador moderno para acceder a la interfaz de la aplicación.

---

### 📁 Estructura del proyecto

El proyecto se divide en dos carpetas principales:

- `Carbulator_Backend/` → Lógica del servidor y conexión a la base de datos.
- `Carbulator/` → Frontend desarrollado con React.

Ambos deben ejecutarse **por separado** para que la aplicación funcione correctamente.

---

### 🧪 Pasos para la instalación

1. **Clona** ambos repositorios en carpetas separadas:

    `Carbulator_Backend`
     ```bash
     https://github.com/EbenGonzalez/Carbulator_Backend.git
     ```
    `Carbulator`
     ```bash
     https://github.com/EbenGonzalez/Carbulator.git
     ```
2. **Inicia XAMPP** y arranca los servicios de:
   - Apache
   - MySQL
     
3. En el navegador, **entra** a [http://localhost/phpmyadmin/](http://localhost/phpmyadmin/).
   
4. **Crea una base de datos** llamada `carbulator_db` y **importa** el archivo `carbulator_db.sql`.
   
5. **Configura el archivo `.env`** en `Carbulator_Backend/` para adaptarlo a tu entorno local:
   ```env
   DB_NAME=carbulator_db
   DB_USER=tu_usuario_mysql
   DB_PASSWORD=tu_contraseña_mysql
   
6. **Abre dos terminales** (una por cada carpeta) desde Visual Studio Code:

    En `Carbulator_Backend/`:
    
      ```bash
      npm install
      npm install -g nodemon
      nodemon start
      ```
    
    En `Carbulator/`:
    
      ```bash
      npm install
      npm run dev
      ```

7. **Accede** a la aplicación desde tu navegador:
http://localhost:5173


## 🖼️ Capturas de pantalla

![Categorias](/screenshots/carbulator1.jpg)
![Favoritos](/screenshots/carbulator2.jpg)
![Filtrado](/screenshots/carbulator3.jpg)

## 👨‍💻 Autor

**Ebén González de la Cruz**

📧 ebencito88@gmail.com

🌐 https://github.com/EbenGonzalez

💼 https://www.linkedin.com/in/ebendev/

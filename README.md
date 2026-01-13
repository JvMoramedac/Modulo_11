# 🎡 Proyecto Ruleta - JavaFX 🚀

¡Bienvenido al **Proyecto Ruleta**! Una aplicación de escritorio desarrollada en **Java** utilizando el framework **JavaFX**, gestionada con **Maven** y preparada para su distribución profesional en entornos Windows. 

---

## 🛠️ Tecnologías y Herramientas Utilizadas

* **Lenguaje:** Java 17+ ☕
* **Framework:** JavaFX 🖼️
* **Gestión de Proyecto:** Maven 📦
* **Conversión EXE:** Launch4j 🚀
* **Instalador:** Inno Setup 🛠️

---

## 📦 Proceso de Desarrollo y Distribución

El ciclo de vida de este proyecto siguió los siguientes pasos profesionales:

### 1. Generación del JAR 🏺
Se utilizó el plugin `javafx-maven-plugin` para empaquetar la aplicación.
* **Comandos:** `mvn clean` seguido de `mvn package`.
* **Resultado:** Un archivo `.jar` ejecutable en la carpeta `target/`.

### 2. Conversión a Ejecutable (.exe) 💻
Para mejorar la experiencia del usuario, transformamos el JAR mediante **Launch4j**:
* **Modo GUI:** Configurado para abrir la interfaz gráfica directamente sin consola negra.
* **Icono Personalizado:** Se integró un archivo `.ico` para una apariencia profesional.
* **Portabilidad:** Se configuró el **JRE Bundled** apuntando a una carpeta local `jre/` para que el programa funcione sin instalar Java previamente.

### 3. Creación del Instalador 📥
Finalmente, usamos **Inno Setup** para crear un asistente de instalación real:
* ✅ Instalación en `Program Files`.
* ✅ Creación de accesos directos en el Escritorio.
* ✅ Sistema de desinstalación completa desde el Panel de Control.

---

## 🚀 Cómo ejecutar el proyecto

Si eres desarrollador y quieres ver el código:
1. Clona el repositorio: `git clone https://github.com/JvMoramedac/Modulo_11.git`
2. Abre el proyecto en tu IDE favorito (IntelliJ/NetBeans).
3. Ejecuta `mvn javafx:run`.

Para usuarios finales:
1. Ve a la carpeta `Output/`.
2. Ejecuta el archivo `Ruleta_Setup.exe` y sigue los pasos del asistente. 🎡

---

## 📁 Estructura del Repositorio

* `/src`: Código fuente del proyecto.
* `/jre`: Entorno de ejecución de Java embebido (No incluido en el repositorio por peso).
* `/Output`: Instalador final generado.
* `pom.xml`: Configuración de dependencias y plugins de Maven.

---

## 👤 Autor
* **Francisco Javier Mora Lucena** - [JvMoramedac](https://github.com/JvMoramedac)

---
Proyecto realizado para el **Instituto Oficial de Formación Profesional MEDAC** 🎓

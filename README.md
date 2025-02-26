# 🏰 MegaRol - Juego de Rol en Consola 🎭

**MegaRol** es un juego de rol basado en texto donde puedes crear personajes, explorar mazmorras, combatir contra monstruos y gestionar tu inventario.  
¡Aventúrate en un mundo lleno de peligros y tesoros!  

---

## 📜 Características  

✔️ **Creación de personajes** con razas personalizadas: Humano, Elfo, Enano, Hobbit, Orco y Troll.  
⚔️ **Sistema de combate** basado en atributos y equipo.  
🗺️ **Exploración de mazmorras** con eventos aleatorios como monstruos, acertijos y objetos.  
🤖 **Modo Autoplay** para exploración automática.  
🎒 **Gestión de inventario** con armas, armaduras y accesorios.  
📈 **Subida de nivel y progresión** con experiencia y mejora de atributos.  

---

## 🚀 Instalación y Ejecución  

### 📥 Requisitos  

- Java 8+ instalado.  
- Tener `Gson` para el manejo de archivos JSON.  

### 🔧 Compilación  

javac -cp ".;gson.jar" MegaRol.java

### ▶️ Ejecución  

java -cp ".;gson.jar" MegaRol


## 🎮 Cómo Jugar  

### 📌 Menú Principal  
Al ejecutar el juego, verás el siguiente menú:

🌌 MEGAROL 🌌  
1️⃣ Crear un personaje  
2️⃣ Ver personajes  
3️⃣ Iniciar un combate  
4️⃣ Explorar la mazmorra  
5️⃣ Explorar la mazmorra en Autoplay  
6️⃣ Administrar inventario  
7️⃣ Curar a todos los personajes 💖  
8️⃣ Salir  


### 📝 Opciones  

🔹 **Opción 1 - Crear un personaje**  
Puedes crear un personaje eligiendo un nombre y su raza.  

🔹 **Opción 2 - Ver personajes**  
Muestra la lista de personajes creados.  

🔹 **Opción 3 - Iniciar un combate**  
Permite seleccionar dos personajes para luchar entre sí.  

🔹 **Opción 4 - Explorar la mazmorra**  
Lleva a un personaje a una aventura con eventos aleatorios.  

🔹 **Opción 5 - Explorar la mazmorra en Autoplay**  
El personaje explora automáticamente la mazmorra hasta que el jugador lo detiene o muere.  

🔹 **Opción 6 - Administrar inventario**  
Permite agregar o eliminar objetos del inventario de un personaje.  

🔹 **Opción 7 - Curar a todos los personajes**  
Restaura la vida de todos los personajes.  

🔹 **Opción 8 - Salir**  
Finaliza el juego.  

## 📂 Estructura del Proyecto  

- 📂 src/
- │── MegaRol.java            # Punto de entrada del juego
- │── GestorPersonajes.java   # Gestión de personajes y combates
- │── Personaje.java          # Clase del personaje con atributos y métodos
- │── Item.java               # Clase de ítems para el inventario
- │── 📜 personajes.json      # Almacena los datos de los personajes
- │── 📜 items.json           # Contiene la lista de ítems disponibles


## 🏆 Créditos  

**Desarrollador:** sh0gg__  
**Inspiración:** Juegos de rol de mesa y RPGs clásicos.  

📢 ¡Cualquier sugerencia o mejora es bienvenida!






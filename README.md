# 🎮 Pokemon Vue - Juego Estilo Pokemon Clásico

<img width="1548" height="772" alt="Pokemon Vue Game Screenshot" src="https://github.com/user-attachments/assets/24fccdc3-25cb-4112-bd0e-0c68b14d5b85" />

## 📋 Descripción

Pokemon Vue es un juego web inspirado en los clásicos juegos de Pokemon, desarrollado con Vue.js para el frontend y Node.js/Express para el backend. El juego incluye mecánicas de movimiento, encuentros aleatorios con Pokemon salvajes, captura de Pokemon y un sistema de Pokedex.

## ✨ Características

- 🎯 **Jugabilidad clásica**: Movimiento del jugador en un mapa pixelado
- 🌿 **Encuentros aleatorios**: Pokemon salvajes aparecen en la hierba alta
- 🎣 **Sistema de captura**: Captura Pokemon con mecánicas de probabilidad
- 📚 **Pokedex integrada**: Visualiza los Pokemon capturados
- 💾 **Sistema de guardado**: Persistencia del progreso del juego
- 🎨 **Arte pixel perfecto**: Sprites y assets estilo retro
- 🎵 **Interfaz responsive**: Diseño adaptado para diferentes pantallas

## 🛠️ Tecnologías Utilizadas

### Frontend
- **Vue.js 3** - Framework principal
- **Vite** - Bundler y servidor de desarrollo
- **CSS3** - Estilos y animaciones
- **JavaScript ES6+** - Lógica del juego

### Backend
- **Node.js** - Entorno de ejecución
- **Express.js** - Framework web
- **CORS** - Manejo de políticas de origen cruzado
- **File System** - Persistencia de datos

## 🚀 Instalación y Configuración

### Prerrequisitos
- Node.js (v16 o superior)
- npm o yarn

### Pasos de instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/pokemonVUE.git
   cd pokemonVUE
   ```

2. **Instalar dependencias del backend**
   ```bash
   cd backend
   npm install
   ```

3. **Instalar dependencias del frontend**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Ejecutar el backend**
   ```bash
   cd ../backend
   npm run dev
   ```
   El servidor se ejecutará en `http://localhost:8081`

5. **Ejecutar el frontend**
   ```bash
   cd ../frontend
   npm run dev
   ```
   El juego estará disponible en `http://localhost:8082`

## 🎮 Cómo Jugar

### Controles
- **Flechas direccionales**: Mover al jugador
- **Tecla A**: Interactuar/Confirmar
- **Tecla B**: Cancelar/Volver
- **Tecla Menu**: Abrir menú principal

### Mecánicas de Juego
1. **Movimiento**: Usa las flechas para mover tu personaje por el mapa
2. **Encuentros**: Camina por la hierba alta para encontrar Pokemon salvajes
3. **Captura**: Durante un encuentro, intenta capturar el Pokemon
4. **Pokedex**: Revisa tu colección de Pokemon capturados en el menú

## 📁 Estructura del Proyecto

```
pokemonVUE/
├── frontend/                 # Aplicación Vue.js
│   ├── src/
│   │   ├── components/       # Componentes del juego
│   │   ├── base_components/  # Componentes base
│   │   ├── assets/          # Sprites y recursos
│   │   └── App.vue          # Componente principal
│   └── package.json
├── backend/                  # Servidor Express
│   ├── app.js               # Servidor principal
│   ├── save_file.txt        # Archivo de guardado
│   └── package.json
└── README.md
```

## 🎯 Funcionalidades Técnicas

### Sistema de Guardado
- Persistencia automática del progreso
- Guardado de posición del jugador
- Registro de Pokemon capturados

### API Backend
- `GET /initial_info` - Obtener información inicial del juego
- `POST /save` - Guardar progreso del juego
- Sistema de encuentros aleatorios con Pokemon

### Componentes Principales
- **MapMiddleware**: Renderizado del mapa
- **PlayerMiddleware**: Lógica del jugador
- **WildEncounterMiddleware**: Encuentros con Pokemon
- **PokedexMiddleware**: Gestión de la Pokedex

## 🔧 Desarrollo

### Scripts Disponibles

**Frontend:**
- `npm run dev` - Servidor de desarrollo
- `npm run build` - Compilar para producción
- `npm run preview` - Vista previa de la compilación

**Backend:**
- `npm run dev` - Servidor con auto-reload usando nodemon

### Contribuir

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia ISC. Ver el archivo `LICENSE` para más detalles.

## 🤝 Autor

**Marc** - [Tu perfil de GitHub](https://github.com/tu-usuario)

## 📞 Contacto

Si tienes alguna pregunta o sugerencia, no dudes en:
- Abrir un issue en GitHub
- Contactarme a través de [tu email]

## 🙏 Agradecimientos

- Inspirado en los clásicos juegos de Pokemon de Game Freak
- Sprites y assets creados con estilo pixel art retro
- Comunidad de Vue.js por la excelente documentación

---

⭐ **¡Dale una estrella al repo si te gustó el proyecto!** ⭐

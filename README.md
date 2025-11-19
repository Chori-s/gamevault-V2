# GameVault

GameVault es una aplicación de prueba de Flutter que he creado para gestionar videojuegos, con sus pantallas, los favoritos y como es obvio las categorías. Este proyecto es parte de un taller de diseño y prototipado de interfaces de usuario que me han dado en clase.

## Estructura del proyecto

- `lib/main.dart` → Aqui tengo toda la configuracion del tema y la pantalla principal
- `lib/screens/home_screen.dart` → Pantalla principal, he usado TabBar
- `lib/widgets/` → Aqui tengo widgets reutilizables
  - `app_drawer.dart` → Drawer lateral.
  - `games_grid.dart` → Aqui se hace la cuadricula donde van los juegos
  - `categories_list.dart` → Aqui tengo la lista con las categorias

## Cómo ejecutar el proyecto IMPORTANTE

1. Clona el repositorio:
git clone https://github.com/Chori-s/gamevault.git
cd gamevault

2. Instalate las dependencias que te pidan:
flutter pub get

3. Ejecuta la app:
flutter run

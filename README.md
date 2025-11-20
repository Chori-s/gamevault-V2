# GameVault 2

GameVault2 es la segunda version de una app de Flutter que ya cree para gestionar videojuegos. En este repositorio la encontraras mejorada en cuanto a su version 1. Aqui me centre en crear metodos para la interaccion y la navegacion, asi puedes añadir juegos nuevos mediante un formulario muy sencillo, confirmar la accion con un dialogo modal que uso y recibir la notificaciones usando Snackbar.

## Estructura del proyecto

- `lib/main.dart` → Aqui tengo toda la configuracion del tema y la pantalla principal
- `lib/screens/home_screen.dart` → Pantalla principal, he usado TabBar
- `lib/screens/add_game_screen.dart` → Pantalla para añadir un juego usando un formulario
- `lib/widgets/` → Aqui tengo widgets reutilizables
  - `app_drawer.dart` → Drawer lateral.
  - `games_grid.dart` → Aqui se hace la cuadricula donde van los juegos
  - `categories_list.dart` → Aqui tengo la lista con las categorias

## Funcionalidades implementadas

1. Formulario para añadir juegos:
  Título (TextField)
  Plataforma (RadioListTile)
  Géneros (CheckboxListTile)
  Calificación (Slider)
  Completado (SwitchListTile)

2. He usado un Modal de confirmación antes de guardar (AlertDialog)

3. Implementado la navegacion entre pantallas usando Navigator.push y Navigator.pop

4. Notifico al usuario con Snackbar después de añadir un juego

## Cómo ejecutar el proyecto IMPORTANTE

1. Clona el repositorio:
git clone https://github.com/Chori-s/gamevault.git
cd gamevault

2. Instalate las dependencias que te pidan:
flutter pub get

3. Ejecuta la app:
flutter run

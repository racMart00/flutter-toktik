# toktik

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

-->Pasos para hacer primer commit<--
git init

git add .

git commit -m "first commit"

git remote add origin https://github.com/NOMBRE_USUARIO/NOMBRE_PROYECTO.git

git push -u origin master

-->Flujo de la Arquitectura Limpia<--
1. UI: Tiene la comunicacion con la capa de presentacion
2. Presentacion: Tiene providers o gestionadores de estado q terminan llamando los casos de uso
3. Casos de Uso: Se comunica con los repositorios //NO SE HACE EN ESTE PROYECTO
4. Repositorios y Datasources: Los repositorios llaman los datasources
5. Informacion: Y luego la informacion regresa al UI.
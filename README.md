# MyFinc — Android Studio

Copia de desarrollo de MyFinc para trabajar con Flutter desde Android Studio.

- Repositorio oficial (versiones, etiquetas, releases y APK): https://github.com/K3NYEL/myfinc
- Este repositorio se utiliza para desarrollar y probar cambios.
- No publiques versiones oficiales ni APK desde este repositorio.

## Empezar

```bash
flutter pub get
flutter analyze
flutter test
flutter run
```
## Aplicación de escritorio para Windows

Para compilar se requiere Windows de 64 bits, Flutter, Visual Studio 2022 con la carga **Desarrollo para el escritorio con C++**, el SDK de Windows y las bibliotecas ATL.

Desde la raíz del proyecto:

```powershell
flutter pub get
flutter run -d windows
```

Para generar la versión de distribución:

```powershell
flutter build windows --release
```

Distribuye la carpeta de salida completa, incluidos el ejecutable y sus DLL. La base local se guarda en el directorio de datos de MyFinc del usuario.

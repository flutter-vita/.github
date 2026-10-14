# Flutter for the PlayStation Vita

flutter-vita builds Flutter apps for the PS Vita. It compiles the Flutter
engine and framework for the console, and each app draws through the
console's GPU. Your `main.dart` does not change.

| Repository | Purpose |
|---|---|
| [flutter-vita](https://github.com/flutter-vita/flutter-vita) | The `flutter-vita` command. It builds, installs, runs and debugs your app. It also contains the Bridge (the app on the console that installs your app over Wi-Fi), the GLES2 layer, the Vita plugins, the gallery and the docs. **Start here.** |
| [flutter](https://github.com/flutter-vita/flutter) | Our fork of Flutter, branch `vita-3.47.7`, with the changes that the engine needs to run on the console. Its releases contain the prebuilt engine, so you do not build the engine. |
| [flutter-vita-embedder](https://github.com/flutter-vita/flutter-vita-embedder) | The `main()` of each app. It starts the engine, reads touch and buttons, and puts each frame on the screen. Each app build compiles it from source. |
| [flutter-vita-packages](https://github.com/flutter-vita/flutter-vita-packages) | Our pub packages. `flutter_vita` sets up an app for the console with one call in `main()`. |
| [flutter-vita-bench](https://github.com/flutter-vita/flutter-vita-bench) | The benchmark: a Flutter app with 36 scenes. It shows which scenes become slower after a change to the engine, the GLES2 layer or the embedder. |

The other repositories are forks:
[the libraries that the engine uses](https://github.com/flutter-vita/flutter-vita/blob/master/docs/engine.md)
and [the apps that we test with](https://github.com/flutter-vita/flutter-vita/blob/master/samples/README.md).

*PlayStation and PS Vita are trademarks of Sony Interactive Entertainment.
This project is not affiliated with or endorsed by Sony.*

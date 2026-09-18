# Flutter for the PlayStation Vita

Flutter apps on the PS Vita. The Flutter engine and framework, compiled for
`arm-vita-eabi`, draw through the console's GPU. Your `main.dart` does not
change.

| Repository | What it is |
|---|---|
| [flutter-vita](https://github.com/flutter-vita/flutter-vita) | The tool: `flutter-vita build`, `install`, `run`, `logs`. The receiver that installs apps over Wi-Fi, the GLES2 layer over `sceGxm`, twelve Vita plugin implementations, the docs. Start here. |
| [flutter](https://github.com/flutter-vita/flutter) | The Flutter fork, branch `vita-3.44.8`: the engine patches and the prebuilt engine on its releases page. |
| [flutter-vita-embedder](https://github.com/flutter-vita/flutter-vita-embedder) | The `main()` of every app: engine start-up, GPU present, touch, pad, keyboard, the dev server, the debug strip. |
| [flutter-vita-packages](https://github.com/flutter-vita/flutter-vita-packages) | Pub packages: `flutter_vita` (one call sets the app up for the console), `vita_debug_strip`, `vita_file_browser`. |

## Start

1. [Install the toolchain](https://github.com/flutter-vita/flutter-vita/blob/master/docs/install-macos.md) (macOS) or [on Linux](https://github.com/flutter-vita/flutter-vita/blob/master/docs/install-linux.md).
2. [Set up the console](https://github.com/flutter-vita/flutter-vita/blob/master/docs/configure-console.md): homebrew, the shader compiler, the receiver.
3. [Get started](https://github.com/flutter-vita/flutter-vita/blob/master/docs/get-started.md): the gallery, then your own app.

## Releases

One tag across the repositories: `<flutter version>_<ours>`, for example
`3.44.8_0.1.0`. Flutter 3.44.8 is pinned; the engine is prebuilt for it.

*PlayStation and PS Vita are trademarks of Sony Interactive Entertainment.
This project is not affiliated with or endorsed by Sony.*

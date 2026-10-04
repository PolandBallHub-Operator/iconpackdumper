# H-backtask — Third-party notices

H-backtaskには、以下の第三者ソフトウェア／アイコンに関するライセンスが適用されます。各ライセンスの全文は、このプロジェクトの`LICENSES/`に収録しています。

> ここに記載する第三者ライセンスは、それぞれの第三者コンポーネントにのみ適用されます。H-backtask独自のソースコードのライセンスは、この告知では定めていません。

## Flutter SDK / Flutter Material 3

- **ライセンス:** BSD 3-Clause License
- **著作権表示:** Copyright 2014 The Flutter Authors. All rights reserved.
- **ソース:** [Flutter](https://github.com/flutter/flutter)
- **ライセンス全文:** [`LICENSES/FLUTTER-BSD-3-CLAUSE.txt`](LICENSES/FLUTTER-BSD-3-CLAUSE.txt)

このプロジェクトはFlutterのフレームワーク、Material 3コンポーネント、およびFlutter同梱のMaterialアイコンフォントを使用します。

## Google Material Icons / Material Symbols

- **ライセンス:** Apache License 2.0
- **帰属表示:** Material Design icons by Google (Material Symbols)
- **公式ソース:** [google/material-design-icons](https://github.com/google/material-design-icons)
- **ライセンス全文:** [`LICENSES/MATERIAL-DESIGN-ICONS-APACHE-2.0.txt`](LICENSES/MATERIAL-DESIGN-ICONS-APACHE-2.0.txt)

現状のDartコードではFlutterの`Icons.*`を使用しています。独立したMaterial Symbolsフォントや`material_symbols_icons`パッケージは直接追加していません。この表記は、Materialアイコンの出所とApache 2.0ライセンスを明示するものです。

## Cupertino Icons package

- **パッケージ:** `cupertino_icons`（pubspec.yamlに宣言）
- **ライセンス:** MIT License
- **著作権表示:** Copyright (c) 2016 Vladimir Kharlampidi
- **公式パッケージ:** [pub.dev/packages/cupertino_icons](https://pub.dev/packages/cupertino_icons)
- **ライセンス全文:** [`LICENSES/CUPERTINO-ICONS-MIT.txt`](LICENSES/CUPERTINO-ICONS-MIT.txt)

このパッケージはテンプレート由来の依存関係として宣言されていますが、現状の画面コードではCupertinoアイコンを直接使用していません。

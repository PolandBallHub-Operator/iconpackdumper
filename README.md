Android向けオープンソース（FOSS）アプリ「Icon Pack Inspector / Viewer」の `README.md` です。英語（EN）と日本語（JP）の両方を1つのファイルとして使える構成にしています。

```markdown
# Icon Pack Inspector / Exporter (FOSS)

[English](#english) | [日本語](#japanese)

---

<a name="english"></a>
## English

An open-source (FOSS) Android utility app designed to detect installed icon packs, list every icon provided by a selected icon pack, and export individual icons via a long-press action.

### Features
* **Icon Pack Detection**: Automatically scans and lists installed icon pack applications on your device.
* **Full Icon Listing**: Displays all icons contained within the selected icon pack.
* **Long-Press Export**: Long-press any icon to save or export it to your device storage.
* **Material 3 (Monet)**: Fully supports Material You dynamic coloring (Monet) using classic Material 3 XML components.
* **No Jetpack Compose**: Built using traditional Android View System (XML layouts) without Jetpack Compose for a lightweight footprint.
* **100% Free & Open Source**: No ads, no tracking, pure FOSS.

### Requirements
* (Dynamic colors available on Android 12+)
* Material Components for Android library (`com.google.android.material:material`)

### Dependencies
```groovy
dependencies {
    // Material Design 3 (XML)
    implementation 'com.google.android.material:material:1.11.0'
    
    // Core AndroidX
    implementation 'androidx.appcompat:appcompat:1.6.1'
    implementation 'androidx.constraintlayout:constraintlayout:2.1.4'
    implementation 'androidx.recyclerview:recyclerview:1.3.2'
}

```

---

## 日本語

インストールされているアイコンパックを取得し、含まれているすべてのアイコンを一覧表示して、長押しで個別保存（抽出）できるオープンソース（FOSS）のAndroidツールアプリです。

### 主な機能

* **アイコンパックの自動検出**: 端末にインストールされているアイコンパックアプリを一覧取得します。
* **全アイコンのリスト表示**: 選択したアイコンパックに含まれるすべてのアイコンをグリッド表示します。
* **長押しで保存**: アイコンを長押しすることで、画像ファイルとしてストレージに保存・抽出できます。
* **Material 3 (Monet) 対応**: Material Youの動的カラー（Monet）に対応し、端末の壁紙に応じたテーマが適用されます。
* **No Jetpack Compose**: Jetpack Composeを使用せず、従来のMaterial 3 XMLレイアウトで構築された軽量設計です。
* **完全なFOSS（オープンソース）**: 広告なし、トラッキングなしのオープンソースソフトウェアです。

### 動作環境

* （動的カラーはAndroid 12以降で適用）

### ビルド・技術仕様

* UI: Traditional XML View System (`com.google.android.material`)
* Theme: `Theme.Material3.DayNight` (Dynamic Colors対応)

---

## License

```text
MIT LICENSE

```

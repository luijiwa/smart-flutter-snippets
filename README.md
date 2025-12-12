# Smart Flutter Snippets

A comprehensive collection of 50+ Flutter and Dart code snippets for Zed Editor.

## ✨ Features

- **50+ Code Snippets** - Ready-to-use templates for Flutter and Dart
- **Stateless & Stateful Widgets** - Quick widget generation
- **Material & Cupertino** - Both design systems supported
- **Builders** - ListView, GridView, StreamBuilder, FutureBuilder, etc.
- **Layout Widgets** - Row, Column, Stack, Wrap, and more
- **Custom Painters & Clippers** - Advanced UI components
- **Lifecycle Methods** - initState, dispose, didUpdateWidget, etc.
- **Test Templates** - testWidgets, test, and group templates

## 📋 Requirements

This extension works perfectly with the official **[Dart extension](https://github.com/zed-extensions/dart)** which provides:
- Language Server (LSP) support
- Syntax highlighting
- Code completion
- Debugging
- Runnable indicators for main() and tests

**Install both extensions for the best experience!**

## Snippets

### Widget Snippets

| Prefix | Name | Description |
|--------|------|-------------|
| `stl`, `statelessWidget` | Stateless Widget | Create a StatelessWidget class |
| `stlChild`, `statelessWidgetWithChild` | Stateless Widget with Child | Create a StatelessWidget with child parameter |
| `stf`, `statefulWidget` | Stateful Widget | Create a StatefulWidget class with lifecycle methods |
| `stfChild`, `statefulWidgetWithChild` | Stateful Widget with Child | Create a StatefulWidget with child and controller |
| `inh`, `inheritedWidget` | Inherited Widget | Create an InheritedWidget class |
| `mateapp` | Material App | Create a MaterialApp with runApp |
| `cupeapp` | Cupertino App | Create a CupertinoApp with runApp |
| `scaffold` | Scaffold | Create a Scaffold with AppBar and body |

### Lifecycle & Methods

| Prefix | Name | Description |
|--------|------|-------------|
| `build` | Build Method | Override build method |
| `initS` | initState | Initialize state for StatefulWidget |
| `dispose` | dispose | Dispose resources when widget is removed |
| `reassemble` | reassemble | Called during hot reload |
| `didChangeD` | didChangeDependencies | Called when dependencies change |
| `didUpdateW` | didUpdateWidget | Called when widget configuration changes |
| `debugFillProperties` | debugFillProperties | Add debug properties |

### Custom Widgets

| Prefix | Name | Description |
|--------|------|-------------|
| `painter`, `customPainter` | Custom Painter | Create a CustomPainter class |
| `clipper`, `customClipper` | Custom Clipper | Create a CustomClipper class |

### Builder Widgets

| Prefix | Name | Description |
|--------|------|-------------|
| `builder` | Builder | Create a Builder widget |
| `wrapWithBuilder` | Wrap with Builder | Wrap selected widget with Builder |
| `stfBuilder`, `statefulBuilder` | Stateful Builder | Create a StatefulBuilder |
| `strBuilder`, `streamBuilder` | Stream Builder | Create a StreamBuilder |
| `futBuilder`, `futureBuilder` | Future Builder | Create a FutureBuilder |
| `animBuilder`, `animatedBuilder` | Animated Builder | Create an AnimatedBuilder |
| `lisBuilder`, `listenableBuilder` | Listenable Builder | Create a ListenableBuilder |
| `valLisBuilder`, `valueListenableBuilder` | Value Listenable Builder | Create a ValueListenableBuilder |
| `layBuilder`, `layoutBuilder` | Layout Builder | Create a LayoutBuilder |
| `orientBuilder`, `orientationBuilder` | Orientation Builder | Create an OrientationBuilder |
| `tweenAnimBuilder`, `tweenAnimationBuilder` | Tween Animation Builder | Create a TweenAnimationBuilder |

### List & Grid Widgets

| Prefix | Name | Description |
|--------|------|-------------|
| `listViewBuilder` | ListView.builder | Create a ListView.builder |
| `listViewSeparated` | ListView.separated | Create a ListView.separated |
| `gridViewBuilder` | GridView.builder | Create a GridView.builder |
| `gridViewCount` | GridView.count | Create a GridView.count |
| `gridViewE` | GridView.extent | Create a GridView.extent |
| `customScrollV` | Custom Scroll View | Create a CustomScrollView |
| `singleChildSV` | Single Child ScrollView | Create a SingleChildScrollView |

### Layout Widgets

| Prefix | Name | Description |
|--------|------|-------------|
| `row` | Row | Create a Row widget |
| `col`, `column` | Column | Create a Column widget |
| `stack` | Stack | Create a Stack widget |
| `wrap` | Wrap | Create a Wrap widget |
| `fittedbox` | FittedBox | Create a FittedBox widget |

### Other Widgets

| Prefix | Name | Description |
|--------|------|-------------|
| `switcher`, `animatedSwitcher` | Animated Switcher | Create an AnimatedSwitcher |
| `repBound`, `repaintBoundary` | Repaint Boundary | Create a RepaintBoundary |

### Helper Snippets

| Prefix | Name | Description |
|--------|------|-------------|
| `of`, `maybeOf` | of Method | Create static of method for InheritedWidget |
| `stateOf` | stateOf Method | Create static stateOf method for State |
| `widgetOf` | widgetOf Method | Create static widgetOf method for Widget |

### Test Snippets

| Prefix | Name | Description |
|--------|------|-------------|
| `testWidget`, `widgetTest` | Widget Test | Create a testWidgets function |

## Installation

### From Zed Extensions (Recommended)

1. Open Zed Editor
2. Press `Cmd/Ctrl + Shift + X` to open Extensions
3. Search for "Smart Flutter Snippets"
4. Click Install

### Manual Installation (Development)

```bash
# Clone the repository
git clone https://github.com/luijiwa/smart-flutter-snippets

# Install as dev extension in Zed
# Open Zed, click "Install Dev Extension" and select the cloned directory
```

## Usage

### Using Code Snippets

1. Start typing a snippet prefix (e.g., `stl` for Stateless Widget)
2. Press `Tab` to expand the snippet
3. Use `Tab` to navigate between placeholders
4. Fill in your custom values

### Example

Type `stl` and press Tab:

```dart
import 'package:flutter/widgets.dart';

/// {@template my_widget}
/// MyWidget widget.
/// {@endtemplate}
class MyWidget extends StatelessWidget {
  /// {@macro my_widget}
  const MyWidget({
    super.key,
  });
  
  @override
  Widget build(BuildContext context) =>
    const Placeholder();
}
```

## Requirements

- [Flutter SDK](https://flutter.dev/docs/get-started/install) installed
- Flutter in your PATH

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


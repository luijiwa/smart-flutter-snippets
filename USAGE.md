# Smart Flutter Snippets - Example Usage

## Runnable Indicators Demo

This file demonstrates how runnable indicators work in this extension.

### Example 1: Main Function with Runnable Indicator

```dart
// You should see a ▶ button next to this main() function
void main() {
  runApp(MyApp());
}
```

**Click the ▶ button to run:** `flutter run`

### Example 2: Widget Test with Runnable Indicator

```dart
import 'package:flutter_test/flutter_test.dart';

// You should see a ▶ button next to this test
testWidgets('Counter increments smoke test', (WidgetTester tester) async {
  // Test code here
});
```

**Click the ▶ button to run this specific test**

### Example 3: Test Group

```dart
import 'package:flutter_test/flutter_test.dart';

// You should see a ▶ button next to this group
group('Calculator tests', () {
  test('addition test', () {
    expect(2 + 2, 4);
  });
  
  test('subtraction test', () {
    expect(5 - 3, 2);
  });
});
```

**Click the ▶ button to run all tests in this group**

## Hot Reload & Hot Restart

Once your app is running:

1. **Hot Reload** - Make changes to your code and press `r` in the terminal
2. **Hot Restart** - Press `R` to fully restart the app

## Using Tasks

You can also use the Command Palette:

1. Press `Cmd/Ctrl + Shift + P`
2. Type `task: spawn`
3. Select:
   - **Flutter: Run** - Start your app
   - **Flutter: Hot Reload** - Reload changes
   - **Flutter: Hot Restart** - Restart app
   - **Flutter: Test** - Run tests

## Keybindings Example

Add to your `keymap.json`:

```json
{
  "context": "Workspace",
  "bindings": {
    "ctrl-shift-r": ["task::Spawn", { "task_name": "Flutter: Run" }],
    "ctrl-r": ["task::Rerun"],
    "ctrl-shift-t": ["task::Spawn", { "task_name": "Flutter: Test" }]
  }
}
```

## Next Steps

1. Open a Dart file with a `main()` function
2. Look for the ▶ button indicator
3. Click it to run your Flutter app
4. Enjoy fast development with hot reload!

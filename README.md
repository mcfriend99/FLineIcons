# FLineIcons

The complete LineAwesome Icon pack available as Flutter Icons.

## Getting Started

This plugin was created due to the massive pitfalls of exisiting Line Awesome flutter icon libraries for not keeping up to date with the complete icons list as well as missing almost all the very cool icons.

[Line Awesome fonts by Icons8](https://icons8.com/line-awesome)

You can visit the icons source project for a full list of all the available icons. I'll do my best to make sure this project is always up-to-date and in sync with the [Icons8](https://icons8.com) project.

## Installation

Simply include the `flineicons` in your `pubsec.yaml`

```
dependencies:
  flutter:
    sdk: flutter
  flineicons: ^0.0.3
```

Then run the `flutter packages get` command (some IDE's such as IntelliJ will prompt you to do this or do it for you automatically).


## Usage

1. Import the library

	```
	import 'package:flineicons/flineicons.dart'
	```

2. Use is anywhere you can use an `IconData` such as in the `Icon` widget. E.g.

	```
	Icon(FLineIcons.facebook)
	```
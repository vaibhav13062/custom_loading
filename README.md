
# custom_loading

custom_loading is a Flutter package that provides an easy way to display customizable loading screens in your Flutter applications. It allows you to create visually appealing loading screens that match your app's design and provide a seamless user experience during data fetching or processing operations.

## Features

- Display a customizable loading screen with various options for customization.
- Easily integrate the loading screen into your existing Flutter applications.
- Customize the appearance of the loading screen to match your app's design.
- Smoothly transition between the loading screen and your app's content.

## Installation

To use `custom_loading` in your Flutter project, add it as a dependency in your `pubspec.yaml` file:

dependencies:
  custom_loading: ^1.0.0

## Getting started

Import the custom_loading package in your Dart file:

```dart
import 'package:custom_loading/custom_loading.dart';
```

## Usage


Use CustomLoadingScaffold widget instead of Scaffold at top most widget of your screen also provide a loader widget and isLoading.

```dart
CustomLoadingScaffold(
isLoading: true, // BOOLEAN
blurIntensity: 2.0, //BACKGROUND BLUR INTENSITY
loaderWidget: Container(), // ADD CUSTOM LOADING WIDGET HERE
body:Container(), // ADD BODY HERE NORMALLY 
);
```

Also you can use all the parameters of Scaffold.

## Example

Check out the `example` directory in the GitHub repository for a complete example showcasing the usage of the custom_loading package.

## Contributing
Contributions to custom_loading are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request on the GitHub repository.

## Additional information

Made by :- Vaibhav Chandolia
Email:- chandolia.vaibhav@gmail.com
Website:- vaibhavchandolia.info

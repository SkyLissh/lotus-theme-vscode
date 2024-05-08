# Change Log

All notable changes to the "lotus" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [1.1.4] - 2024-05-08

### Changed

- Remove support for custom components is vue, due to lack of correct semantic tokens the
  new extension version, to enable syntax highlighting for Vue, use the version 1.8.27 of
  vue extension

## [1.1.3] - 2024-05-07

### Changed

- Fixed broken syntax highlighting in all clases to cyan, now every kind of class has it's own color
- Added better dupport of sytax highlighting for GDScript

## [1.1.2] - 2024-05-01

### Changed

- Added support for gdscript language (it still needs some work)
- Fixed Component syntax highlighting for Vue Extension version 2.0.X
- Added color to type definitions in typescript

## [1.1.1] - 2023-10-14

### Changed

- Added color to constants, this specifically to solve an issue with built-in constants
  in Python, like `True` and `False`, etc.
- Added bracket colorization by default, for light and dark mode

## [1.1.0] - 2023-09-13

### Changed

- Improved syntax highlighting for C# in dark and white mode
- Improvements of colors for better readability in white mode

## [1.0.4] - 2022-07-06

### Changed

- Syntax highlighting for `self` and `cls` with Python Language Server (Jedi)

## [1.0.3] - 2022-02-03

### Changed

- Hover text link now are pinky
- Add background highlight to menu item hover

## [1.0.2] - 2021-08-26

### Changed

- Colors of the components parameters (Like React and Blazor)

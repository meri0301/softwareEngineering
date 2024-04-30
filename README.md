# Observer Design Pattern in JavaScript

## Description
This repository contains an implementation of the Observer design pattern in JavaScript. The Observer pattern is a behavioral design pattern where an object (subject) maintains a list of its dependents (observers) and notifies them of any state changes, usually by calling one of their methods.

## Implementation
The implementation consists of two main classes:
- `Subject`: Represents the subject being observed. It maintains a list of observers and provides methods to subscribe, unsubscribe, and notify them.
- `Observer`: Represents an observer that is interested in receiving updates from a subject. It provides an `update` method that subjects can call to notify observers of state changes.

## Usage
To use the Observer pattern, create instances of the `Subject` and `Observer` classes. Subscribe observers to the subject, and then notify them when the subject's state changes.

Unit Test
A unit test is provided to verify the functionality of the Observer pattern implementation. It tests whether observers are correctly notified when the subject's state changes.

Repository Structure
observer.js: Contains the implementation of the Observer pattern.
test.js: Contains the unit test for the Observer pattern implementation.
README.md: This file, providing an overview of the project.
Branches
This repository has two branches:

dev: Development branch where new features are implemented and tested.
main: Main branch containing stable and production-ready code.
Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

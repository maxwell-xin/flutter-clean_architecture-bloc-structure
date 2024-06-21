## Flutter Clean Architecture & Bloc State Management

### This repository showcases a Flutter project structured with Clean Architecture principles and utilizing the Bloc State Management pattern. It serves as a comprehensive example for developers aiming to build scalable, maintainable, and testable Flutter applications.

````
flutter-clean-architecture-bloc/
├── lib/
│   ├── core/
│   │   ├── di/
│   │   │   └── service_locator.dart
│   │   ├── network/
│   │   │   └── http_request_strategies/
│   │   └── utils/
│   ├── feature/
│   │   ├── app/
│   │   │   ├── data/
│   │   │   │   ├── data_sources/
│   │   │   │   ├── models/
│   │   │   │   └── repositories/
│   │   │   ├── domain/
│   │   │   │   ├── repositories/
│   │   │   │   └── usecases/
│   │   │   ├── presentation/
│   │   │   │   ├── bloc/
│   │   │   │   ├── pages/
│   │   │   │   └── widgets/
│   ├── services/
│   └── main.dart
├── pubspec.yaml
└── README.md
````

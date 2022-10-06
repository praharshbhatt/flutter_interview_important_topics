# flutter_interview_important_topics
Flutter and Dart Interview important topics and material

============================================

Oops concepts

============================================

SQL queries

============================================

REST API
    1. get
    2. PUT
    3. Post
    4. Idempotence: https://youtu.be/rhTkRK53XdQ

============================================

Syntax:
    1. Syntax for stateless and stateful
    2. Syntax for navigator
    3. syntax for isolate

============================================

How Flutter renders Widgets:
    1. https://www.youtube.com/watch?v=996ZgFRENMs

============================================

Flutter architecture:
    1. framework
    2. Engine
    3. Embedder
    4. https://flutter.dev/docs/resources/architectural-overview

============================================

State management:
    1. setState (To manage ephemeral states)
    2. Bloc (business Logic and component):
        1. A family of stream/observable-based patterns.
        2. Event, State, Bloc, View. View: Block provider, blocbuilder
    3. Provider
    4. Redux
    5. Fish Redux
        1. Fish Redux is an assembled flutter application framework based on Redux state management. It is suitable for building medium and large applications.
    6. GetIt
        1. A service locator-based state management approach that doesn’t need a BuildContext.
    7. MobX
    8. InheritedWidget & InheritedModel
    9. Riverpod
    10. https://docs.flutter.dev/development/data-and-backend/state-mgmt/options

============================================

Flutter Navigator 2.0 and Deep Links:

    1. https://medium.com/flutter/learning-flutters-new-navigation-and-routing-system-7c9068155ade
    2. Declarative approach rather than imperative
    3.  RouterDelegate, RouteInformationParser, BackButtonDispatcher
    4.  Page: An abstract class that describes the configuration of a route
        Router: A class that manages the opening and closing pages of an application
        RouteInformationParser: An abstract class used by the Router‘s widget to parse route information into a configuration
        RouteInformationProvider: An abstract class that provides route information for the Router‘s widget
        RouterDelegate: An abstract class used by the Router‘s widget to build and configure a navigating widget
        BackButtonDispatcher: Reports to a Router when the user taps the back button on platforms that support back buttons (such as Android)
        TransitionDelegate: The delegate that decides how pages transition in or out of the screen when it’s added or removed.
    3. https://www.youtube.com/watch?v=wH16ROWAtAk
    4. https://www.raywenderlich.com/19457817-flutter-navigator-2-0-and-deep-links

============================================

Platform and method channels:
    1. https://flutter.dev/docs/development/platform-integration/platform-channels

============================================

Difference between Flutter and react Native: https://www.javatpoint.com/flutter-vs-react-native#:~:text=Flutter%20compiles%20the%20application%20by,app%20a%20better%20native%20performance.&text=React%20Native%20uses%20third%2Dparty,as%20compared%20to%20React%20Native.

============================================

JIT and AOT:
    1. JIT:
        1. Compiles just during hot reload, on the fly.
        2. Includes all the code
        3. takes less time
    2. AOT:
        1. Compiles all at compile time
        2. Used when we need to build a production application
        3. Takes more time, and creates a smaller build including only the code and libraries that are actually used by the app.
    3. https://medium.com/@onuohasilver9/how-does-jit-and-aot-work-in-dart-cab2f31d9cb5


============================================

Change status bar color: https://stackoverflow.com/questions/52489458/how-to-change-status-bar-color-in-flutter

============================================

Difference between const and final
    1. https://www.youtube.com/watch?v=B1fIqdqwWw8

============================================

Transitive dependencies
    1. Understanding pubspec.lock: https://medium.com/flutter-community/whats-the-pubspec-lock-file-in-a-flutter-project-64a22e1b03f4

============================================

hash collision

tree shaking and garbage collection
generics (run time / compile time)
    1. https://youtu.be/S5NY1fqisSY

============================================

Flutter tests
    1. Integration test: https://flutter.dev/docs/cookbook/testing/integration/introduction
    2. Unit test: https://flutter.dev/docs/cookbook/testing/unit/introduction
    3. Flutter test tutorial and mocking dependencies: https://sagarsuri56.medium.com/integration-and-unit-testing-in-flutter-f08e4bd961d5

============================================
Flutter CI / CD
    1. Flutter github actions: https://www.youtube.com/watch?v=rpQKpXjH5vs
    2. Codemagic: https://www.youtube.com/watch?v=GsQ5MHHVNqQ
    3. Environments (Flavors) in Flutter with Codemagic CI/CD: https://www.youtube.com/watch?v=zdJkvDANiuY

============================================

Flutter flavors
    1. https://flutter.dev/docs/deployment/flavors

============================================

Repaint boundaries: https://youtu.be/cVAGLDuc2xE

============================================

MaterialPageRoute(
        builder: (context) => Page2()
      )
Flutter streams
    1. Types of streams:
        - Single subscription: Single subscription streams are meant to deliver events in order. This type of stream is used when order of events received matters like reading a file. Such type of Streams can be listened only once. Attempting to listening them again will throw an exception.
        - Broadcast (Multiple subscribers): Broadcast streams are intended to deliver events to their subscribers. Any subscriber can start listening to events as soon as they subscribe to it. A Broadcast stream can be listened multiple times.
    2. Note: A Single Subscription stream can be converted into broadcast streams by using asBroadcastStream() method.

============================================

Creating Packages and plugins: https://docs.flutter.dev/development/packages-and-plugins/developing-packages

============================================

How Flutter handles high-Performance web applications (web architecture)- https://youtu.be/kCnYRhkfWHY

============================================
Debuggable properties
https://youtu.be/DnC7eT-vh1k

============================================

what are something(s) in flutter or dart that majority of Dev's don't use/know/heard about? https://www.reddit.com/r/FlutterDev/comments/wsa4pa/what_are_somethings_in_flutter_or_dart_that/?utm_medium=android_app&utm_source=share

============================================

Intrinsic widgets: https://youtu.be/Si5XJ_IocEs

============================================

Primaryscrollview: https://youtu.be/33_0ABjFJUU

============================================

Equality, Equatable, and Hashcodes: https://www.youtube.com/watch?v=DCKaFaU4jdk

============================================

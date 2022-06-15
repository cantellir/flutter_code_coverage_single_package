# flutter_code_coverage_single_package

A simple Flutter project demonstrating how code coverage works in Flutter with a single package APP.

Run flutter test with coverage info (root app folder):

```flutter test --coverage```

Coverage will be available in ```/coverage/lcov.info```.

Convert info into html report (```lcov``` needs to be installed):

```genhtml coverage/lcov.info -o coverage/html```

```-o``` = output folder

Coverage report will be available in ```/coverage/html/index.html```.

Remember to add ```/coverage``` folder to the ```.gitignore``` file.
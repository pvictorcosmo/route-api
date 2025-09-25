# Route Finder API 🗺️

*Project Status: In Development*

A Dart API that finds the shortest route between two geographic points using real map data. This project is currently under active development.

## About

This API takes two geographic coordinates (latitude/longitude) and returns the optimal route between them. It's designed for routing applications, logistics, and trip planning.

## How It Works

- **Data Source**: Uses the Overpass API to fetch real street and path data from OpenStreetMap
- **Routing Algorithm**: Implements the A* search algorithm to find the shortest path efficiently
- **Database**: Uses a database for caching and performance optimization

## Current Status

This project is still being built. The core functionality is implemented but expect changes, improvements, and occasional breaking changes as development continues.

Basic setup:
```bash
dart pub get
dart run bin/api.dart
```

More detailed documentation and stable release coming soon.

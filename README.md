# Shopping List App

A simple Flutter shopping list app that helps users add, view, and remove grocery items.

## Features

- Add new grocery items with name, quantity, and category
- View the shopping list
- Remove items by swiping
- Sync data with Firebase in real time
- Modern and responsive user interface

## Screens Used in the Project

- `main.dart` → app entry point
- `grocery_list.dart` → main shopping list screen
- `new_item.dart` → form for adding a new grocery item
- `grocery_item.dart` → grocery item data model
- `categories.dart` → category data used in the app

## How It Works

The app starts with the main shopping list screen.  
When the user adds a new grocery item, the data is sent to Firebase and displayed in the list on the screen.  
Users can also remove items by swiping them from the list.

## Technologies

- Flutter
- Dart
- HTTP
- Firebase Realtime Database

## Getting Started

To run this project locally:

```bash
git clone https://github.com/iremcimen/Shopping-List-App.git
cd Shopping-List-App
flutter pub get
flutter run

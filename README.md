# Flutter News App
This Flutter application is designed to provide users with a seamless experience for browsing and managing news articles. Leveraging clean architecture principles, it incorporates features such as displaying news lists, retrieving news details, utilizing local databases for favorites, and managing favorites through removal operations. The app employs Retrofit for API calls and BLoC for state management.

## Features
1. Display News List
   The app fetches news articles from an API and displays them in a list format, allowing users to browse through the latest news.
2. Get News Details
   Users can access detailed information about each news article by selecting them from the list. The app retrieves and presents comprehensive details such as the title, content, publication date, and author.
3. Local Database for Favorites
   Users have the ability to mark news articles as favorites, which are then stored locally within the app. This feature ensures that users can access their preferred articles even when offline.
4. Remove Favorites from Local Database
   Should users decide to remove articles from their list of favorites, the app provides functionality to easily delete them from the local database.
##   Architecture
###   Clean Architecture
   The app follows clean architecture principles to ensure separation of concerns and maintainability. This architecture divides the application into distinct layers: Presentation, Domain, and Data.

###   Retrofit for API Calls
   Retrofit is used to handle API requests and responses efficiently. It simplifies the process of making network calls and parsing JSON data, providing a robust foundation for interacting with remote servers.

###   BLoC (Business Logic Component) for State Management
   BLoC architecture is implemented for managing application state and handling user interactions. BLoC decouples business logic from UI components, promoting a reactive programming paradigm and enhancing code reusability.

###   Setup Instructions
   To run the Flutter News App locally on your machine, follow these steps:

Clone the repository to your local environment.
Navigate to the project directory using a terminal or command prompt.
Ensure that Flutter and Dart SDK are installed on your system.
Run flutter pub get to install dependencies.
Connect a physical device or start an emulator.
Run flutter run to launch the application.

## Contributors
Aishwarya Dherange - Developer and maintainer
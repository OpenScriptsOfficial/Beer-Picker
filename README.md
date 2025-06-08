# Beer-Picker
# Beer Picker App

This is a simple Android application that helps users find different beer brands based on a selected color.

## Description

The application provides a dropdown list (Spinner) for the user to select a beer color (e.g., Light, Dark, Red, Wheat). After selecting a color and clicking the "Find Beer" button, the app displays a list of recommended beer brands corresponding to that color.

## Features

*   **Beer Color Selection**: Users can choose their preferred beer color from a dropdown list.
*   **Brand Search**: Upon clicking the button, the app searches for and displays a list of beer brands.
*   **Results Display**: The found brands are displayed in a text view below the button.


## Technologies Used

*   **Programming Language**: Kotlin
*   **User Interface**: XML Layouts
*   **Core Android Components**:
    *   `Activity`
    *   `Spinner`
    *   `Button`
    *   `TextView`
    *   `LinearLayout`

## Project Structure (Key Files)

*   `app/src/main/java/com/example/myapplication/MainActivity.kt`: The main activity of the application, containing UI logic and event handling.
*   `app/src/main/res/layout/activity_main.xml`: The XML layout file for the main screen.
*   `app/src/main/res/values/strings.xml`: String resources used in the application.
*   `app/src/main/res/values/arrays.xml` (if you are using it for `android:entries` in the Spinner): String array resources.
*   `app/src/main/res/font/`: (If used) Folder for custom fonts (e.g., `roboto.ttf`).

## How to Build and Run

1.  **Clone the repository**:
2.  **Open the project in Android Studio**.
3.  **Build the project**: Click `Build > Make Project` or use the hammer icon in the toolbar.
4.  **Run the application**: Select an emulator or a connected device and click `Run > Run 'app'` or the green play icon.

## Potential Future Enhancements

*   Load beer data from a remote API or a local database.
*   Add images for each beer brand.
*   Implement filtering by other parameters (e.g., alcohol content, country of origin).
*   Allow users to add beers to a "favorites" list.
*   Develop a more complex and visually appealing user interface design.

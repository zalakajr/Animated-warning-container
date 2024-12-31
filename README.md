# Warning Animated Container

This Flutter project demonstrates an animated container that expands when clicked, revealing a warning message with options to cancel or continue. The container starts small and expands to show a detailed message, with a smooth animation.

## Features

- **Expandable Container**: The container expands to show a warning message when tapped.
- **Warning Message**: A warning message is displayed to notify the user about potential consequences (e.g., data loss).
- **Interactive Buttons**: Includes "Cancel" and "Continue" buttons that let the user either dismiss the warning or proceed.
- **Smooth Animation**: The container expands and collapses with a smooth animation effect.

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/zalakajr/Animated-warning-container.git
# Navigate into the project directory:
cd Animated-warning-container

# Install the required dependencies:
flutter pub get

# Run the app:
flutter run

## Description
The app contains a container that changes size when tapped. Initially, the container is small, displaying a "Continue" button. When tapped, it expands to show a warning message and options to "Cancel" or "Continue." The user can collapse the container by tapping the close icon or the cancel button.

# Key Parts of the Code
AnimatedContainer: Used to create a smooth transition when the container expands and collapses.
GestureDetector: Detects taps to trigger the expansion or collapse of the container.
Row and Column Layout: Used to organize the icons, text, and buttons within the expanded container.

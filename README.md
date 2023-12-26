# Unscramble App

The **Unscramble** app is a single-player word game designed for Android devices. It presents players with a scrambled word and challenges them to create a valid word using all the letters from the displayed scrambled word.

## Features

### Game Logic
- Randomly generates a scrambled word by rearranging the letters.
- Requires players to form a meaningful word using all the letters from the scrambled word.
- Validates whether the created word matches the letters available in the scrambled word.

### Android Architecture Components Used
- Demonstrates the utilization of ViewModel and StateFlow.
- **ViewModel**: Manages game logic and data.
- **StateFlow**: Handles the flow of data and ensures real-time UI updates.

### Functionality
- `ScrambledWordViewModel` manages:
  - Generating the scrambled word.
  - Checking the user's input for correctness.

### UI Updates
- Utilizes StateFlow to reflect changes in the scrambled word immediately in the UI.
- Provides an interactive interface for users to input their answers.

### Game Flow
- After submitting an answer, the app validates the accuracy of the user's response.
- If the answer is correct, the app can display a success message or progress to the next level.
- In case of an incorrect answer, the user might receive a prompt to retry.

The Unscramble app not only offers entertainment but also helps users enhance their vocabulary. By leveraging ViewModel and StateFlow, the app ensures organized data management and streamlined UI updates, contributing to a more stable and user-friendly gaming experience.



![screens](https://github.com/erdemserhat/Unscramble/assets/116950260/cc7be61f-4142-4917-8c37-19900e64fe4a)

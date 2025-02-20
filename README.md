# Lottery Numbers Generator 🎲✨

## Description
This is a simple Android app that generates random numbers for lottery games. It allows users to generate lists of **6 or 7 unique numbers** between 1 and 49, simulating the drawing process of typical lottery games. 

The app also includes a feature to clear previously generated numbers, allowing users to start fresh with new draws. 🔄

---

## Features
- **Generate 6 numbers** 🎯: Users can generate a set of 6 random numbers.
- **Generate 7 numbers** 💫: Users can generate a set of 7 random numbers.
- **Clear numbers** ❌: Users can clear the displayed numbers to start over.
- Numbers are shuffled and sorted automatically before being displayed. 🔄➡️📈

---

## Prerequisites
Before running this app, make sure you have the following tools installed:
- [Android Studio](https://developer.android.com/studio) (recommended version: latest stable release)
- JDK (Java Development Kit) compatible with Android Studio

---

## How to Run
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/lotto-numbers-generator.git
   ```
2. Open the project in Android Studio. ⚙️
3. Connect an Android physical device or use an emulator. 📱
4. Compile and run the app by clicking the "Run" button in Android Studio. ▶️

---

## Project Structure
The project follows the standard Android architecture:

- **MainActivity.java** ✨: Contains the main logic of the app, including the number generator and button event handlers.
- **activity_main.xml** 🖼️: Defines the user interface layout, including buttons and the text view where the generated numbers will be displayed.

### Main Code Logic
The method `generateNumbers(int count)` is responsible for generating random numbers. It performs the following steps:
1. Creates a list of numbers from 1 to 49. 🔢
2. Shuffles the list using `Collections.shuffle()`. 🔄
3. Selects the first `count` numbers from the shuffled list. ✅
4. Sorts the selected numbers. ➡️📈
5. Displays the numbers in the `TextView`. 🖼️

---

## Screenshots
Add screenshots of the app in action to showcase its functionality. Example:

![Initial Screen](path/to/screenshot1.png)
*Initial screen of the app.*

![Generated Numbers](path/to/screenshot2.png)
*Numbers generated after clicking the "Generate 7 Numbers" button.*

---

## Contribution
Contributions are welcome! If you'd like to improve this project, follow these steps:
1. Fork this repository. 🍴
2. Create a new branch for your feature (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Adds new feature'`).
4. Push to your branch (`git push origin feature/new-feature`).
5. Open a Pull Request. 📝

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details. 📜


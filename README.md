# SGPI & Percentage Calculator

A Flutter application that helps users calculate their Semester Grade Point Index (SGPI) and the corresponding percentage based on their subject grades and credit points.

## Features

- **Grade Input**: Users can input their grades for up to 11 subjects.
- **Credit Points Input**: Each subject can be assigned credit points (3, 2, or 1).
- **Validation**: The app validates user inputs for grades and credit points and alerts the user in case of missing or incorrect inputs.
- **SGPI & Percentage Calculation**: The app calculates the SGPI based on the entered grades and credit points, and also converts SGPI to percentage.

## How to Use

1. Enter your grades for each subject in the designated text fields.
2. Select the corresponding credit points for each subject from the dropdown.
3. Click the **Calculate** button.
4. The app will display your SGPI and percentage in a pop-up dialog.

### Grade to Point Mapping
- **O** = 10
- **A** = 9
- **B** = 8
- **C** = 7
- **D** = 6
- **E** = 5
- **P** = 4
- **F** = 0

### Credit Points
- 3, 2, or 1 based on subject importance.

## Validation Messages

- If any grade is missing: "Please enter grade for all subjects."
- If an invalid grade is entered: "Invalid grade entered for subject X."
- If an invalid credit point is entered: "Invalid credit point entered for subject X."
- If a failing grade (F) is entered: "Student has failed in subject X."

## SGPI & Percentage Formula

- **SGPI** = Total Grade Points / Total Credit Score
- **Percentage** = 
  - If SGPI < 7: `7.1 * SGPI + 12`
  - If SGPI >= 7: `7.4 * SGPI + 12`

## Installation

1. Clone the repository or download the project.
2. Run the app using `flutter run` in the terminal or use an IDE like Android Studio or Visual Studio Code with Flutter setup.
3. Ensure you have Flutter installed on your system. Visit [Flutter installation](https://flutter.dev/docs/get-started/install) for more details.

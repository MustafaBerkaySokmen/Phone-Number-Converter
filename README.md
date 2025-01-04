# Phone Number Converter

## Overview
The **Phone Number Converter** is a Python-based program that converts alphanumeric phone numbers (e.g., `555-GET-FOOD`) into their numeric equivalent using a standard phone keypad mapping.

## Features
- Converts alphanumeric phone numbers into numeric format.
- Handles different input formats, including hyphenated and non-hyphenated numbers.
- Preserves numeric digits and only translates alphabetic characters.
- Provides a testing interface with various sample inputs.

## Installation
To run this project, ensure you have **Python 3.x** installed on your system.

### Steps:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/phone-number-converter.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd phone-number-converter
   ```
3. **Run the script:**
   ```bash
   python PhoneConverter.py
   ```

## Usage
1. The program contains one primary function:
   - `phone_converter(phone_alpha)`: Converts an alphanumeric phone number into a numeric format.
2. Users can modify the test cases in the `main()` function to test different inputs.
3. Running the script prints the converted numeric phone numbers.

## Example Output
```
555-GET-FOOD → 555-438-3663
310-EaT-MeaT → 310-328-6328
12E-456-789T → 123-456-7898
444-EAT-CHICKEN → 444-328-2442536
444EATMEAT → 4443286328
090-EAT-MEAT → 090-328-6328
```

## License
This project is licensed under the **MIT License**.

## Contributions
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-new-feature`).
3. Commit and push your changes.
4. Open a pull request.

## Contact
For any questions or support, please open an issue on GitHub.


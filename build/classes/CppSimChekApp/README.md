# CppSimChekApp

CppSimChekApp is a Java Swing application designed to calculate and display similarity metrics between C++ code snippets. The application features a user-friendly interface that guides users through the process of calculating similarity scores.

## Project Structure

```
CppSimChekApp
├── src
│   ├── CppSimChek.java        # Main application frame
│   ├── LoadingPage.java       # Loading screen displayed during calculations
│   ├── Result.java            # Result screen displaying similarity results
│   └── utils
│       └── FrameUtils.java    # Utility methods for frame management
├── .gitignore                 # Specifies files to ignore in version control
└── README.md                  # Documentation for the project
```

## Setup Instructions

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd CppSimChekApp
   ```

2. **Compile the Java files**:
   Ensure you have Java Development Kit (JDK) installed. Compile the source files using:
   ```
   javac src/*.java
   ```

3. **Run the application**:
   Execute the main application frame:
   ```
   java src.CppSimChek
   ```

## Usage Guidelines

- Upon launching the application, users can input C++ code snippets for similarity analysis.
- Click the "Calculate" button to initiate the similarity calculation.
- A loading screen will appear for 3 seconds before displaying the results.
- The results will show the similarity score between the provided code snippets.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
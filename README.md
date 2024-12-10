# Quantum-Safe Scanner

## Overview

The Quantum-Safe Scanner is a command-line tool designed to analyze Java projects for cryptographic vulnerabilities, particularly those susceptible to quantum computing attacks. This tool helps developers identify and mitigate potential security risks in their codebases.

## Prerequisites

- **Java 17 or later**: Ensure Java is installed on your system. You can verify this by running:
  ```bash
  java -version
  ```

## Usage

### Basic Command

To run the Quantum-Safe Scanner, use the following command:

```bash
java -jar executable-1.0-SNAPSHOT.jar --input=<inputPath>
```

- **`<inputPath>`**: Replace this with the path to the Java file or directory you want to scan.

### Options

- **`-i, --input=<inputPath>`**: (Required) Specifies the input path to scan.
- **`-f, --formats=<formats>`**: (Optional) Specifies the report formats, such as JSON or HTML. Example: `--formats=JSON,HTML`.
- **`-h, --help`**: Displays the help message and exits.
- **`-V, --version`**: Prints version information and exits.

### Example Commands

- **Scan a Single File**:
  ```bash
  java -jar executable-1.0-SNAPSHOT.jar --input=src/main/java/com/example/MyClass.java
  ```

- **Scan an Entire Directory**:
  ```bash
  java -jar executable-1.0-SNAPSHOT.jar --input=src/
  ```

- **Generate Reports in JSON and HTML**:
  ```bash
  java -jar executable-1.0-SNAPSHOT.jar --input=src/ --formats=JSON,HTML
  ```

## Troubleshooting

- **Terminal Issues on Windows**: If you encounter terminal-related errors, try using a different terminal emulator like Windows Terminal or Git Bash. Ensure your terminal supports the necessary operations.

- **Error: `To start java on Windows, use javaw!`**: This error may occur due to terminal compatibility issues. Consider running the application in a different environment or checking for updates to any terminal libraries used.

## Support

For any issues or questions, please contact [support@example.com](mailto:support@example.com) or visit our [GitHub Issues page](https://github.com/your-org/quantum-safe-scanner/issues).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.md) file for details.

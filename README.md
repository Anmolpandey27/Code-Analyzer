# Security Scanner Extension
This VS Code extension helps detect security vulnerabilities in JavaScript code 
while coding. It checks for SQL Injection, XSS, and package vulnerabilities.

## Features
- Real-time vulnerability detection
- Quick Fixes for security issues
- Checks for npm package vulnerabilities
- Seamless IDE integration

## Usage
1. Install the extension.
2. Open a JavaScript file.
3. Vulnerabilities will be highlighted automatically.
4. Use `Ctrl + Shift + P` → `Run Security Scan` to manually scan.

## Commands
- `Run Security Scan`: Scans the active file for security issues.
- `Check Dependencies`: Runs `npm audit` to check dependencies.

## License
MIT License

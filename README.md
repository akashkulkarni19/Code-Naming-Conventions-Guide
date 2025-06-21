# Code Naming Conventions Guide

A comprehensive cheat sheet for naming conventions used across popular programming languages and software development environments. This guide ensures consistency, readability, and maintainability in codebases by following widely accepted industry standards.

---

## 📘 Contents

- General Naming Rules
- Language-Specific Conventions:
  - JavaScript / TypeScript
  - Python
  - Java
  - C#
  - C / C++
  - Go
- Usage Tips & Best Practices

---

## 📋 General Naming Conventions

| Element                 | Recommended Casing       | Example                        |
|-------------------------|--------------------------|--------------------------------|
| Variable                | camelCase / snake_case   | `userName`, `user_name`        |
| Function / Method       | camelCase / snake_case   | `getUserInfo()`, `fetch_data()`|
| Class / Type            | PascalCase               | `UserService`, `OrderModel`    |
| Constant                | SCREAMING_SNAKE_CASE     | `MAX_RETRIES`, `DEFAULT_TIMEOUT` |
| File Name               | kebab-case / snake_case  | `user-form.js`, `user_data.json` |
| CSS Class Name          | kebab-case               | `.user-card`, `.form-label`    |
| Environment Variable    | SCREAMING_SNAKE_CASE     | `API_KEY`, `NODE_ENV`          |
| Database Table/Column   | snake_case               | `created_at`, `user_profiles`  |

---

## 💻 Language-Specific Guidelines

### JavaScript / TypeScript
- Variables/Functions → `camelCase`
- Classes/Interfaces → `PascalCase`
- Constants → `SCREAMING_SNAKE_CASE`
- Files → `kebab-case`

### Python
- Variables/Functions → `snake_case`
- Classes → `PascalCase`
- Constants → `SCREAMING_SNAKE_CASE`
- Files → `snake_case.py`

### Java
- Variables/Methods → `camelCase`
- Classes/Enums → `PascalCase`
- Constants → `SCREAMING_SNAKE_CASE`

### C#
- Variables/Properties → `camelCase` or `PascalCase`
- Methods/Classes → `PascalCase`
- Constants → `SCREAMING_SNAKE_CASE`

### C / C++
- Variables/Functions → `snake_case`
- Constants → `SCREAMING_SNAKE_CASE`
- Structs/Enums → `PascalCase`

### Go
- Unexported → `camelCase`
- Exported → `PascalCase`
- Packages → `lowercase`

---

## ✅ Best Practices

- Stick to one style throughout a project or codebase.
- Follow the language’s community conventions for better collaboration.
- Use linters (e.g., ESLint, Pylint) to enforce naming styles automatically.
- Include this guide in your team documentation or onboarding materials.

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 🙌 Contributions

Contributions are welcome! If you'd like to add naming rules for other languages or clarify existing ones, feel free to open a pull request.

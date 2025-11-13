# CRUSH.md

## Build/Lint/Test Commands
*   **Build**: N/A (Static HTML)
*   **Lint**: N/A (Consider tools like HTMLHint, CSSLint, ESLint for larger projects)
*   **Test**: N/A (Consider Cypress, Playwright for end-to-end tests in larger projects)
    *   To run a single test: N/A

## Code Style Guidelines

### General
*   **File Naming**: Use `kebab-case` for HTML, CSS, and JavaScript files (e.g., `login-page.html`, `main-styles.css`, `utils.js`).
*   **Indentation**: Use 2 spaces for indentation.
*   **Comments**: Add comments to explain complex or non-obvious parts of the code.

### HTML
*   **Structure**: Maintain a clear and semantic HTML structure.
*   **Attributes**: Use double quotes for all HTML attribute values.
*   **Self-closing tags**: Use self-closing tags for elements like `<img />`, `<link />`.

### CSS
*   **Classes/IDs**: Use `kebab-case` for class and ID names (e.g., `user-profile`, `main-header`).
*   **Ordering**: Order CSS properties alphabetically within a rule.

### JavaScript (if applicable)
*   **Variables**: Use `camelCase` for variable and function names (e.g., `userName`, `getUserData`).
*   **Constants**: Use `SCREAMING_SNAKE_CASE` for global constants.
*   **Error Handling**: Basic `try...catch` blocks for asynchronous operations.

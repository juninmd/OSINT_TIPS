```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines detail the principles and requirements for development within the AGENTS.md repository. Adherence to these principles is crucial for maintaining code quality, scalability, and maintainability.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent module should have a single, well-defined purpose.
*   **Component Reuse:**  Identify and reuse components across different agents whenever possible.
*   **Abstraction:** Define abstract interfaces for agents to minimize code duplication.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimal Code:** Strive for the shortest possible code that achieves a given functionality.
*   **Readability:** Code should be easily understandable by other developers (including the AI).
*   **Clear Intent:** Each line of code should have a single, clear purpose.

## 3. SOLID Principles

*   **Single Responsibility:**  Each class/module should have one specific responsibility.
*   **Open/Closed Principle:**  The system should be extensible without modifying the code itself.  (This is handled through modular design).
*   **Liskov Substitution Principle:**  Subclasses should be able to replace their base classes without breaking the functionality.
*   **Interface Segregation Principle:**  Clients should not be forced to depend on methods they do not use.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Code:**  Only implement features that are absolutely necessary for the current task.
*   **Focus on Core Functionality:** Prioritize the essential elements required for agent operation.

## 5. Code Structure & File Management

*   **File Limit:** Each file must not exceed 180 lines of code.
*   **Modular Structure:** Organize modules logically and hierarchically.
*   **Naming Conventions:**  Use consistent and meaningful naming conventions.
*   **Comments:**  Provide clear and concise comments to explain complex logic, assumptions, or design decisions.
*   **Documentation:** Include JSDoc-style comments within each file where appropriate, detailing input/output expectations, assumptions, and key considerations.
*   **Clear Separation of Concerns:**  Each file should be focused on a single part of the agent's functionality.

## 6. Testing & Quality Assurance

*   **Unit Tests:** All modules must have comprehensive unit tests covering all critical functions.  Aim for 80% test coverage.
*   **Integration Tests:**  Integrate agents to verify the interaction between different modules.
*   **Test Data:** Use realistic and diverse test data.
*   **Automated Testing:**  Automate as much of the testing process as possible.
*   **Test Driven Development:** Implement tests before coding, ensuring they cover critical functionality.

## 7. Development Workflow

*   **Version Control:** Use Git for version control.
*   **Code Reviews:**  All code changes must be reviewed by at least one other developer before merging.
*   **Pull Requests:**  All changes must be submitted via pull requests.
*   **Static Analysis:** Utilize static analysis tools to detect potential issues.
*   **Refactoring:**  Regularly refactor code to improve its design and maintainability.

## 8.  AGENTS.md File Structure (Example)

```
AGENTS.md
```

*   **modules/
    *   [module-1]/
        *   [agent-1.py] - Core agent logic
        *   [agent-2.py] - Another agent with different logic
        *   ...
*   **data/
    *   [data-1].json - Configuration data
    *   ...
*   **tests/
    *   [test-1].test.js - Unit tests
    *   [test-2].test.js - Integration tests
    *   ...
*   README.md - Document repository information and project overview.
```

These guidelines are intended to provide a framework for development.  Developers are encouraged to discuss and refine these principles as needed.  AI implementation will prioritize adherence to these guidelines.
```
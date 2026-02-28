```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines are designed to ensure high-quality, maintainable, and robust AI coding agent development within the AGENTS repository.  Adherence to these principles is mandatory for all development activities.

**1. DRY (Don't Repeat Yourself)**

*   **Module Design:**  Each module should have a clear, single responsibility.  Avoid creating redundant code within a single module.
*   **Function Definitions:**  All functions and classes should have clearly defined inputs, outputs, and purpose.
*   **Template Code:** Utilize templates where appropriate to reduce boilerplate.
*   **Parameterization:** Design algorithms and data structures with parameters to promote reusability.

**2. KISS (Keep It Simple, Stupid)**

*   **Code Clarity:**  Prioritize readability.  Use meaningful variable and function names.
*   **Minimize Complexity:** Avoid overly convoluted logic.
*   **Short Functions:** Keep functions as small and focused as possible.
*   **Explicit Logic:**  Ensure your code clearly expresses the intended behavior.

**3. SOLID Principles**

*   **Single Responsibility Principle (SRP):**  Each class/module should have one primary responsibility.
*   **Open/Closed Principle (OCP):**  The system should be extensible without modifying the existing code.  New functionality should be added through new classes/modules, not through modification of existing code.
*   **Liskov Substitution Principle (LSP):**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle (ISP):** Each client interface should receive only the information necessary for it to fulfill its contract.
*   **Dependency Inversion Principle (DIP):** Interfaces should match implementations, and implementations should match abstractions.

**4. YAGNI (You Aren't Gonna Need It)**

*   **Avoid Over-Implementation:**  Do not implement functionality that is not currently required.  Refactor if necessary, but avoid adding code that isn't needed at this time.
*   **Placeholder Implementation:**  If a functionality isn’t needed yet, it should be clearly marked as such.

**5. Development Process & Rules**

*   **Commit Messages:**  Each commit must include a concise description of the changes made.  Follow a consistent format (e.g., "feat: Add logging for API calls").
*   **Code Reviews:** All code submitted for review MUST be reviewed by at least one other team member.
*   **Testing:** All code must undergo comprehensive unit and integration testing.  Tests must cover all significant functionality.
*   **Error Handling:** Implement robust error handling with informative error messages.
*   **Documentation:**  Write clear and concise documentation for all modules and functions, including comments explaining complex logic.
*   **Version Control:**  Use Git effectively, adhering to established branching strategies.
*   **Dependencies:** Explicitly declare all dependencies in the `requirements.txt` file.  Ensure dependency versions are tracked and managed.
*   **Code Style:**  Follow a consistent code style guide (e.g., Google Style, PEP 8).  Use linters to enforce the style.
*   **Testing Framework:** Use a chosen testing framework consistently (e.g., `pytest` or `unittest`).
*   **Refactoring:**  Carefully consider refactoring to improve code quality and maintainability.
*   **Documentation Updates:** All documentation must be updated whenever code changes are made.
*   **Timeboxing:**  Allocate a defined amount of time (e.g., 2 hours) for each task, and stick to it.

**6. Code Length Constraint**

*   **Maximum Code:** 180 lines of code per file.

**7. Test Coverage Requirements**

*   **Minimum:** 85% code coverage (based on automated tests).
*   **Testing Strategy:** Utilize a combination of unit and integration tests, ensuring all major functionality is tested.


**8.  File Structure & Conventions**

*   **Modular Design:**  Organize the codebase into logical modules.
*   **Clear Naming:**  Use descriptive and consistent names for classes, functions, and variables.
*   **Consistent Formatting:**  Follow a consistent code formatting style.
*   **Separate Concerns:** Each file should address a single, well-defined purpose.

**9.  AGENTS.md Format:**

*   Include a "description" field in each file documenting its purpose.
*   Include a "test_coverage" field (percentage) in each file.
*   Include a "last_modified" field in each file.
*   Document the major functions and components.


These guidelines are subject to change.  Any updates must be communicated to the team.
```
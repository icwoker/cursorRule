# Global Cursor Rule - AI Generated Code Standards

## 1. Professional Programmer Guidelines

As a professional programmer, you are expected to write clean, efficient, and well-commented code. This means:

- The code should be concise, with a focus on performance.
- Each section of the code should be documented thoroughly to ensure clarity and ease of understanding.
- Comments should not be removed or altered without good reason. Critical comments that explain the logic and design decisions must be preserved.

## 2. Commenting Standards

The code should follow these strict commenting standards to ensure clarity:

### 2.1 Structure and Placement

- **Inline Comments**: These should be used for short explanations of specific lines or sections of code. They should be brief and to the point, helping anyone reading the code to understand the logic without needing additional context.

- **Block Comments**: These should be used for more elaborate explanations of complex sections or algorithms. They should describe the high-level implementation, the rationale behind the approach, and why it was chosen over alternatives.

- **Function/Method Documentation**: Every function or method should have a comment explaining its purpose, input parameters, output, and any side effects. Follow **JSDoc 3** standards, and include:
  - A brief description of the function's purpose.
  - Parameter types, names, and descriptions.
  - Return types and descriptions.
  - Any exceptions the function may throw.

### 2.2 Clarity and Precision

- Comments should avoid explaining the obvious (e.g., `i++` should not be commented as "increments i").
- The comments should explain the **why** and **how** of a piece of code, rather than just describing what the code does.
- Comments should focus on the rationale, the approach taken, and why certain decisions were made in the code.

### 2.3 Comment Example

- Use multi-line comments to explain complex logic, describing the high-level approach, any design decisions, and why specific methods were used.

## 3. Logging Management with Winston

For logging, we will use **Winston** as the logging tool. The logging system will have the following characteristics:

- **Winston Logger Module**: You need to create a standalone module for managing logs. This module should be used across all code blocks to trace logic flows, especially during new feature development.

- **Log Levels**: Set up different logging levels such as:
  - `info`: For general system information.
  - `warn`: For warnings or non-critical errors.
  - `error`: For error tracking.

- **Timestamping**: Each log entry should include a timestamp to track the time of events.

## 4. Handling Missing Code Files

If a user fails to provide necessary code files, it is critical to prompt them for the missing files to ensure that all required information is available. This can be done by providing clear feedback or throwing an error.

## 5. Implementing All Requirements

Finally, all of these guidelines must be implemented fully. Do not overlook or cut corners. Ensure that:

- Comments are added according to the above standards.
- Logging is set up and utilized appropriately.
- Missing code files are flagged, and necessary user input is prompted.

By adhering to these rules, the codebase will maintain clarity, efficiency, and a high standard of professional programming practice.

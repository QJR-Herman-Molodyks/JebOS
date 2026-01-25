# Contributing to Jeb OS

Thank you for your interest in contributing to **Jeb OS**! We welcome contributions from developers, testers, and anyone passionate about making Jeb OS better. Your help will be essential in improving this project, and we're excited to have you on board.

## How You Can Contribute

There are many ways you can contribute to **Jeb OS**! Whether you are a seasoned developer or just starting out, we encourage you to get involved.

### 1. **Forking the Repository**
   - The first step to contributing to **Jeb OS** is to fork the repository to your own GitHub account.
   - Once you've forked the repository, you can make changes to the code and create a pull request with your proposed changes.
   - This allows you to experiment with features or fix bugs without affecting the main project.

   **How to Fork:**
   1. Click the **Fork** button on the top-right of the repository page.
   2. This will create a copy of the repository in your GitHub account.
   3. Clone the forked repository to your local machine using `git clone https://github.com/Mavox-ID/JebOS.git`.

### 2. **Making Changes**
   - **Jeb OS** is a community-driven project, and we highly encourage developers to contribute new features, bug fixes, documentation, or even improvements to the codebase.
   - Before making changes, please review the existing codebase to ensure that your changes will be consistent with the project's architecture.
   - Use meaningful commit messages that describe the purpose of your changes.

   **Recommended Workflow:**
   1. Create a new branch for your feature or bug fix:
      ```bash
      git checkout -b feature-branch
      ```
   2. Make your changes in the code.
   3. Commit your changes with a descriptive message:
      ```bash
      git commit -m "Add new feature for VBE"
      ```
   4. Push your changes to your fork:
      ```bash
      git push origin feature-branch
      ```

### 3. **Running Tests**
   - If your changes affect the functionality of **Jeb OS**, it's important to test them locally.
   - Ensure that all the tests pass, and if necessary, write new tests to verify your changes.

   **Running the Build Locally:**
   1. Install dependencies:
      ```bash
      sudo apt install -y gcc-arm-none-eabi binutils xorriso build-essential mtools
      ```
   2. Clean up previous build files:
      ```bash
      make clean
      ```
   3. Build the project:
      ```bash
      make all
      ```

### 4. **Creating a Pull Request (PR)**
   Once you've made your changes and tested them, it's time to submit your pull request.

   **Steps for Creating a Pull Request:**
   1. Navigate to your fork on GitHub.
   2. Click on the **New Pull Request** button.
   3. Select your branch and compare it with the `main` branch of the original repository.
   4. Write a clear description of what your PR does. Include references to issues if necessary.
   5. Submit the pull request.

### 5. **Code Review and Feedback**
   - Once your pull request is submitted, the maintainers of the project will review your changes.
   - You may receive feedback or requests for further changes. We highly encourage collaboration and discussion to ensure that all changes align with the project's goals and quality standards.
   - We appreciate patience during this process as we work to ensure the quality of the project.

   **Responding to Feedback:**
   - If the reviewer suggests changes, make those changes locally and push them to your fork. The PR will automatically update with the new changes.
   - Be open to constructive criticism and take it as an opportunity to improve the project.

### 6. **Submitting Issues**
   - If you find a bug, have a suggestion, or encounter any problems with **Jeb OS**, please create a new issue.
   - Before submitting a new issue, please search through the existing issues to ensure that it hasn't already been reported.
   - Provide a detailed description of the problem, including any error messages and steps to reproduce the issue.

### 7. **Documentation Contributions**
   - We believe in clear, concise, and up-to-date documentation. If you find errors, typos, or places where the documentation could be improved, we welcome your contributions!
   - Please feel free to submit pull requests to improve the **Jeb OS** documentation.

### 8. **Improving the Build and CI/CD Pipelines**
   - **Jeb OS** is built using a variety of tools, including `make`, `gcc`, `xorriso`, and more. If you have experience with build automation or continuous integration, we welcome contributions to improve the build process.
   - You can help by proposing optimizations, updating dependencies, or integrating new tools into our CI/CD pipeline.

## Contribution Guidelines

To maintain the high standards of **Jeb OS**, we have a few contribution guidelines:

### 1. **Code of Conduct**
   We expect all contributors to adhere to the project's **Code of Conduct**, which encourages a positive, respectful, and professional environment for everyone.

### 2. **Coding Style**
   - Follow the [C Coding Standards](https://www.kernel.org/doc/Documentation/CodingStyle) for C code style.
   - Use `4 spaces` for indentation.
   - Avoid using tabs in the codebase.
   - Each function should be separated by a blank line.
   - Write descriptive comments for functions and complex code blocks.

### 3. **Commit Messages**
   - Use clear, concise commit messages.
   - The commit message should explain *why* the change was made, not just *what* was changed.
   - A good format for commit messages:
     ```
     [type]: Short description of the change

     Detailed explanation of the change (if necessary).
     ```
     Example:
     ```
     fix: correct memory leak in kernel.c

     Fixed a bug that caused memory to leak in the kernel when processing I/O requests.
     ```

### 4. **Issues and Feature Requests**
   - Before working on a feature or bug fix, please check the [existing issues](https://github.com/Mavox-ID/JebOS/issues) to avoid duplication.
   - If you're planning to implement a new feature, it's a good idea to first open an issue to discuss it with the maintainers and get feedback.

### 5. **Maintainers' Decision**
   - While we appreciate all contributions, please note that the maintainers of **Jeb OS** have the final say on whether your changes are merged.
   - Contributions must align with the project's goals and code quality standards.

## Getting Help

If you need any assistance or have questions, feel free to ask in the **Issues** section of the repository or reach out to the maintainers directly.

We are always happy to help and answer any questions you may have. Just remember to be clear and respectful when asking for help.

---

## Conclusion

We actively accept pull requests and are eager to review the changes you make! Your contributions will help us make **Jeb OS** better, and we look forward to seeing what you build. If you're unsure about something or need help along the way, don't hesitate to ask. We're here to help!

Happy coding and welcome to the **Jeb OS** community!

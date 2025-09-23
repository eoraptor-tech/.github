<p align="center"\>  
  <img src="https://avatars.githubusercontent.com/u/233878561?s=400\&u=fa9f02d5be28382c0115519ed5e941edd9706ee3\&v=4" alt="rust-eoraptor banner" width="150"/\>  
</p\>

# **Contributing to rust-eoraptor**

First off, thank you for considering contributing to rust-eoraptor\! We're excited you're here. This project is a collective effort, and we welcome contributions from everyone. By participating, you are helping us build robust, efficient, and innovative software with Rust.

This document provides guidelines for contributing to our projects. Whether you're reporting a bug, proposing a new feature, or submitting code, these guidelines are here to make the process smooth and effective for everyone involved.

## **📜 Code of Conduct**

We are committed to providing a friendly, safe, and welcoming environment for all, regardless of level of experience, gender identity and expression, sexual orientation, disability, personal appearance, body size, race, ethnicity, age, religion, or nationality.

Please read and adhere to our [Code of Conduct](./CODE_OF_CONDUCT.md).

## **🦖 How Can I Contribute?**

There are many ways to contribute to the rust-eoraptor ecosystem. Here are some of the most common ones:

* **Reporting Bugs**: If you find something that isn't working as expected, please open an issue.  
* **Suggesting Enhancements**: Have an idea for a new feature or an improvement to an existing one? We'd love to hear it.  
* **Writing Documentation**: Great documentation is key. Help us improve project READMEs, add code comments, or create tutorials.  
* **Submitting Code**: If you're ready to write some code, you can open a Pull Request to fix a bug or implement a new feature.

## **🚀 Getting Started**

Ready to jump in? Here’s how you can get set up for a typical rust-eoraptor project.

1. **Install Rust**: If you don't have Rust installed, you can get it from [rustup.rs](https://rustup.rs/).  
   ```sh
   curl --proto '=https' --tlsv1.2 -sSf [https://sh.rustup.rs](https://sh.rustup.rs) | sh
   ```
3. **Fork the Repository**: Navigate to the repository you want to contribute to and click the "Fork" button in the top-right corner.  
4. **Clone Your Fork**: Clone your forked repository to your local machine.  

  ```bash
   git clone https://github.com/USERNAME/REPOSITORY_NAME 
   cd REPOSITORY_NAME
  ```

6. **Create a Branch**: Create a descriptive branch name for your changes.  
   ```bash
   git checkout -b feature/my-awesome-feature
   ```
   # or  
   ```bash
   git checkout -b fix/resolve-that-bug
   ```

8. **Build the Project**: Ensure the project builds correctly before you start making changes.  
   ```bash
   cargo build
   ```

9. **Run the Tests**: Make sure all tests are passing.  
   ```bash
   cargo test
   ```

## **submitting a Pull Request (PR)**

When you're ready to submit your contribution, please follow these steps:

1. **Commit Your Changes**: Make your changes and commit them with a clear, descriptive commit message. We follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.  
   * **feat**: A new feature.  
   * **fix**: A bug fix.  
   * **docs**: Documentation only changes.  
   * **style**: Changes that do not affect the meaning of the code (white-space, formatting, etc).  
   * **refactor**: A code change that neither fixes a bug nor adds a feature.  
   * **test**: Adding missing tests or correcting existing tests.  
   * **chore**: Changes to the build process or auxiliary tools.

  ```
  git commit -m "feat: Add a new API endpoint for user profiles"
  ```

2. **Keep Your Branch Updated**: Before pushing, rebase your branch on top of the latest main branch from the original repository to avoid merge conflicts.  
   # Add the original repository as an upstream remote  
   ```bash
   git remote add upstream https://github.com/rust-eoraptor/REPOSITORY_NAME.git
   ```

   # Fetch the latest changes  
   ```bash
   git fetch upstream
   ```

   # Rebase your branch  
   ```bash
   git rebase upstream/main
   ```

4. **Push to Your Fork**: Push your changes to your forked repository.  
   ```bash
   git push origin feature/my-awesome-feature
   ```

5. **Open a Pull Request**: Go to the rust-eoraptor repository on GitHub and open a new Pull Request. Provide a clear title and a detailed description of your changes, linking to any relevant issues (e.g., Closes #123).

## **🛠️ Style Guides & Code Quality**

### **Code Formatting**

We use rustfmt to maintain a consistent code style across all our projects. Please format your code before committing.

```bash
cargo fmt
```

### **Linting**

We use clippy for catching common mistakes and improving our code. Please run clippy and address its warnings.

```bash
cargo clippy -- -D warnings
```

### **AI-Assisted Coding**

We embrace modern tools like GitHub Copilot and other AI assistants (vaicoding) to accelerate development. If you use an AI tool, you are still responsible for the code you submit. Please ensure that:

* You understand the code you are committing.  
* The code adheres to our quality standards and style guides.  
* The code is well-tested and documented.  
* The code does not introduce any licensing issues.

<p align="center">Thank you for helping us make rust-eoraptor better. Happy coding! 🦖</p>

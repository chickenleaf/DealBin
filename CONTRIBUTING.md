# Contributing to the Price Tracker Web Extension

Thank you for considering contributing to our project! We welcome contributions and are excited to see how you can help improve the price tracker web extension.

Please follow these guidelines to ensure a smooth contribution process.

## How to Contribute

### 1. **Fork the Repository**
   - Go to the repository page and click on the **Fork** button at the top right.
   - This creates a personal copy of the repository under your GitHub account.

### 2. **Clone Your Fork**
   - Clone your fork to your local machine:

     ```bash
     git clone https://github.com/YOUR-USERNAME/DealBin.git
     ```

### 3. **Create a New Branch**
   - Always create a new branch for your work. This keeps the main branch clean.

     ```bash
     git checkout -b feature/your-feature-name
     ```

### 4. **Make Changes**
   - Implement your changes or fixes in your local branch. Make sure to test the extension, especially for the functionality related to price tracking on Amazon and Flipkart.
   - Ensure your changes adhere to the project's code style and best practices.
   - If you're fixing a bug, try to reproduce the issue before making changes.

### 5. **Commit Your Changes**
   - Write clear, concise commit messages. Each commit should reflect a logical change.
   - Please make sure you **sign your commits**.

     ```bash
     git add .
     git commit -s -m "Briefly describe your changes"
     ```

### 6. **Push to Your Fork**
   - Push the changes to your forked repository.

     ```bash
     git push origin feature/your-feature-name
     ```

### 7. **Create a Pull Request**
   - Go to the original repository (not your fork) and create a **Pull Request** (PR).
   - Provide a clear description of what your PR does and what issue it addresses (if any).
   - Make sure to select the correct base branch (`main`) and compare it with your feature branch.

## Code Style

- **JavaScript/Node.js:** Follow standard JavaScript conventions. Use ESLint for linting.
- **Puppeteer Scripts:** Make sure your Puppeteer scripts are optimized and error-free.
- **MERN Stack:** Keep the server-side code clean and well-structured. Use async/await for asynchronous operations.

## Issue Tracking

- **Bug Reports:** If you find a bug, please create an issue before submitting a PR. This allows us to discuss the problem and plan the fix.
- **Feature Requests:** Feature requests are welcome! Please open an issue first, so we can discuss the idea and understand its scope.

## Testing

Please make sure to run tests before submitting your pull request. Testing is crucial, especially to verify that the price tracking for Amazon and Flipkart works properly.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).

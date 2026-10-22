# Contributing to My First Website

Thank you for your interest in contributing to **My First Website**! This open-source project is a beginner-friendly website built with HTML, CSS, and JavaScript. Contributions of all experience levels are welcome.

## Ways to contribute

- Report bugs or problems with the website.
- Suggest improvements to accessibility, design, documentation, or functionality.
- Fix issues and improve existing code.
- Improve explanations and examples for beginners.

## Before you start

1. Review the [Code of Conduct](CODE_OF_CONDUCT.md).
2. Check existing issues and pull requests to avoid duplicating work.
3. For a substantial change, open an issue first to discuss the idea.

## Set up the project

1. Fork the repository at https://github.com/beyondruntime/my-first-website.
2. Clone your fork:

   ```bash
   git clone https://github.com/YOUR-USERNAME/my-first-website.git
   cd my-first-website
   ```

3. Create a branch for your change:

   ```bash
   git checkout -b fix/describe-your-change
   ```

4. Open `index.html` in a browser. No build tools or dependencies are required.

## Make your changes

- Keep HTML, CSS, and JavaScript clear and beginner-friendly.
- Follow the existing folder structure and coding style.
- Use descriptive names and explain non-obvious logic with brief comments.
- Preserve the `defer` attribute on the JavaScript script tag in the document head so the script runs after HTML parsing.
- Test the site in a modern browser, including button clicks and basic responsive layout.
- Do not include passwords, access tokens, or other secrets.

## Submit a pull request

1. Commit your changes with a clear message, for example:

   ```bash
   git add .
   git commit -m "fix: ensure button works after page loads"
   ```

2. Push your branch:

   ```bash
   git push origin fix/describe-your-change
   ```

3. Open a pull request against the `master` branch of the original repository.
4. Describe what changed, why it was needed, how you tested it, and which issue it addresses (if any).
5. Respond respectfully to review feedback. Maintainers may request revisions before merging.

## Reporting bugs

When opening a bug report, include the steps to reproduce the problem, what you expected, what happened instead, your browser and operating system, and screenshots or console errors if useful. Avoid sharing personal information.

## Licensing

By contributing, you agree that your contributions will be licensed under the project's [MIT License](LICENSE).

Thank you for helping make this project better!

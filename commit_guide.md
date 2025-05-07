# Abstract

A list of conmmit message reference.
As a guide, the below is the commit convention syntax (base on Angular commit convention):
"**type** *[optional scope]* : messages"

# Type of commit:

1. feat: A new feature for the user.
Example: feat: add user login functionality
Explanation: This type is used when you add a new feature to your project.

2. fix: A bug fix.
Example: fix: resolve login issue on mobile devices
Explanation: Use this type when you fix a bug in your code.

3. docs: Documentation only changes.
Example: docs: update API documentation
Explanation: This type is for changes to documentation only.

4. style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc).
Example: style: format code according to new guidelines
Explanation: Use this type for code style changes that do not affect the logic of the code.

5. refactor: A code change that neither fixes a bug nor adds a feature.
Example: refactor: optimize user authentication logic
Explanation: This type is for code changes that improve the structure or readability of the code without changing its behavior.

6. perf: A code change that improves performance.
Example: perf: enhance database query efficiency
Explanation: Use this type for changes that improve the performance of your code.

7. test: Adding missing tests or correcting existing tests.
Example: test: add unit tests for user service
Explanation: This type is for adding or updating tests.

8. build: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm).
Example: build: update npm dependencies
Explanation: Use this type for changes that affect the build system or dependencies.

9. ci: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs).
Example: ci: configure TravisCI for continuous integration
Explanation: This type is for changes to your CI configuration.

10. chore: Other changes that don't modify src or test files.
Example: chore: update project README
Explanation: Use this type for routine tasks or changes that don't fit into other categories.

11. revert: Reverts a previous commit.
Example: revert: revert "feat: add user login functionality"
Explanation: This type is used when you need to undo a previous commit.

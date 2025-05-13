# Django ToDo list

This project is an advanced to-do list web application with the basic features of most web apps, such as accounts/login, API, and interactive UI.

To complete this task, you will need:

- CSS | [Skeleton](http://getskeleton.com/)
- JS  | [jQuery](https://jquery.com/)

## Summary

In this project, I've created a GitHub Actions workflow that:

    Runs on every push to the main and develop branches, and on pull requests to the main branch.

    Includes a dynamic run name that contains the GitHub username and the commit SHA.

    Runs a python-ci job with steps to:

        - Run tests.

        - Generate and display code coverage using coverage.

        - Check code style and complexity using flake8 (non-blocking).

        - Upload Python code as an artifact.

Additionally, I’ve created a repository with this workflow and ensured that it successfully passes all checks on pull request events.

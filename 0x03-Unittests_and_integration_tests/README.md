**README**

This repository contains unit tests for the `client` module, focusing on the `GithubOrgClient` class. The tests are designed to ensure the functionality and reliability of the methods within the `GithubOrgClient` class.

## Unit Tests Overview

The unit tests are organized into two main test suites:

1. **TestGithubOrgClient:** This test suite includes tests for individual methods of the `GithubOrgClient` class.

   - `test_org`: Tests the retrieval of organization data from GitHub.
   - `test_public_repos_url`: Tests the `_public_repos_url` property of the `GithubOrgClient` class.
   - `test_public_repos`: Tests the retrieval of public repositories belonging to an organization.
   - `test_has_license`: Tests the determination of whether a repository has a specific license.

2. **TestIntegrationGithubOrgClient:** This test suite performs integration tests for the `GithubOrgClient` class. It simulates interactions with the GitHub API to verify the behavior of the `public_repos` method, considering both the basic functionality and filtering by license.

## Test Fixtures

The unit tests utilize fixtures to mock responses from the GitHub API, ensuring consistent and predictable testing environments. These fixtures are located in the `fixtures.py` file.

# github-user-created-abc136

## Overview

This project publishes a simple Bootstrap webpage that allows users to input a GitHub username. Upon submission, the page fetches the GitHub user's information using the GitHub API and displays the account creation date in YYYY-MM-DD UTC format. It optionally accepts a GitHub API token via the `?token=` query parameter for increased rate limits.

## Features

*   Displays a Bootstrap form with the ID `github-user-abc136`.
*   Fetches GitHub user data using the GitHub API.
*   Displays the GitHub account creation date in YYYY-MM-DD UTC format within the element with ID `github-created-at`.
*   Supports optional GitHub API token authentication via the `?token=` query parameter.

## How to Use

1.  Open the deployed page in your web browser (e.g., [https://your-github-username.github.io/github-user-created-abc136/](https://your-github-username.github.io/github-user-created-abc136/)). Replace `your-github-username` with your actual GitHub username.
2.  Enter a GitHub username in the input field.
3.  Submit the form.
4.  The GitHub account creation date will be displayed below the form.
5.  To use a GitHub API token, append `?token=YOUR_GITHUB_TOKEN` to the URL (e.g., [https://your-github-username.github.io/github-user-created-abc136/?token=ghp_xxxxxxxxxxxxxxxxxxxxxxxxxxxxx](https://your-github-username.github.io/github-user-created-abc136/?token=ghp_xxxxxxxxxxxxxxxxxxxxxxxxxxxxx)). Replace `YOUR_GITHUB_TOKEN` with your actual token.

## Technology Stack

*   Bootstrap
*   JavaScript
*   GitHub API

## Project Structure

```
github-user-created-abc136/
├── index.html
└── style.css
```

## Local Development

1.  Clone the repository: `git clone https://github.com/your-github-username/github-user-created-abc136.git` (Replace `your-github-username` with your actual GitHub username).
2.  Navigate to the project directory: `cd github-user-created-abc136`
3.  Open `index.html` in your web browser.

## License

This project is licensed under the MIT License.
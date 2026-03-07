# Authenticate GitHub CLI on a New Machine

Setting up GitHub authentication on a new machine is easy with the GitHub CLI.
No need to manually generate SSH keys — the `gh` CLI handles it automatically.

Run the following command:

```bash
$ gh auth login --web
```

This will:

1. Generate a one-time authentication code in your terminal
2. Open your browser and prompt you to enter that code on GitHub
3. Automatically configure SSH key authentication and push it to your GitHub account

After completing the browser flow, your machine is fully authenticated and ready
to push to GitHub.

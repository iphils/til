# GitHub CLI Authentication on a New Machine

Setting up GitHub authentication on a new machine? You don't need to manually create SSH keys.

Use the GitHub CLI to authenticate via the web:

```bash
gh auth login --web
```

This command will:
1. Generate a one-time code in the terminal
2. Open your browser to GitHub's device activation page
3. Ask you to enter the code to confirm the login
4. Automatically configure authentication (including SSH key setup) linked to your GitHub account

No manual SSH key generation or copying of public keys required.

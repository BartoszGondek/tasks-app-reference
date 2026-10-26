# Meeting 3: changes

You do not have to do this. If you missed the meeting, copy these files into your repo to catch up.

Each file is replaced as a whole. Copy the complete file, not parts of it.

| File | What to do | What it is for |
|---|---|---|
| `.github/workflows/ci.yml` | replace | The finished pipeline: tests and Bandit on every Python version, API docs made with pdoc for both services, and a `deploy` job that publishes the reports and the API docs to GitHub Pages when a pull request is merged. It carries the `pull_request` trigger, the `if:` and the `permissions` block. |
| `.github/workflows/ci_livecode.yml` | delete | An old workflow file that is no longer used. Delete it if you have it. |
| `README.md` | replace | Adds a short section, "What each meeting covers". |

## Also do

- Settings > Pages > Source: GitHub Actions (the repo must be public).

This is not homework either.

# gitpus

Keeps my GitHub contribution graph active with one automated commit per day,
powered by a scheduled GitHub Actions workflow.

The workflow lives in [`.github/workflows/daily-commit.yml`](.github/workflows/daily-commit.yml).
It runs daily, appends a line to `activity.log`, and pushes the commit.

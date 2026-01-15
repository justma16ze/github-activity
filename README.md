# GitHub Activity Generator

Automated daily commits to maintain GitHub activity.

## How it works

- GitHub Actions runs 3 times daily at different hours
- Each run has a ~20% chance to skip (creates natural variation)
- Makes 1-3 commits per successful run
- Results in varying shades of green on the contribution graph

## Setup

1. Create a new repository on GitHub
2. Push this code to the repository
3. Go to repository Settings > Actions > General
4. Under "Workflow permissions", select "Read and write permissions"
5. The workflow will start running automatically on schedule

## Manual trigger

You can also manually trigger the workflow from the Actions tab.

# GitHub Batch Updater

Script to help make basic additions to multiple GitHub repositories.

Currently this just adds a single file and opens a pull request.

## Usage

Edit the variables at the top of the script.

Set the environment variable `GITHUB_TOKEN` to your GitHub personal token.
Run `./main.js addfile`:


    ./main.js addfile README.md --base manicstreetpreacher/github-api-test --dest dir2/README-2.md --branch test-new-ref --title 'This is a test' --body $'This is a test of creating a PR using [octokit rest.js](https://github.com/octokit/rest.js/)\n\n:octocat: :smile: :star:' --force

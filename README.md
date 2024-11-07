# gh-play
My playground for some gh functionalities


I am trying some gh functionalities

- **the dependabot**
- **some deployment for a simple html gh page**
- **a simple python script in the CI**
- **A merge check that draft current PR into next version if needed** but this worked until I made this a organization repo. I discovered that the permissions of the `GITHUB_TOKEN` for PR from external forks are read-only (and that it is the ONLY secret passed to them)
- **Trying an automerge tool** for moving nearly "automagically" bugfixes from older versions to newer ones, to make it work I moved it to trigger on push and not on closed prs

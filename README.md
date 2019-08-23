

# Ironhack Data Analytics Labs

## Getting Started

1. Install [grip](https://github.com/joeyespo/grip) with `brew install grip` (Mac) or `pip install grip` (Windows).

2. Start local Markdown server:

```
$ grip -b README.md 8080 --user <your-github-username> --pass <your-github-password>
```

:bulb: `grip` uses the GitHub Markdown API to render the files in localhost so that you'll see exactly how GitHub would render the Markdown files. Running `grip` with your Github username and password will allow you to make unrestricted requests to GitHub. If you see error when you run the problem that says `GitHub Rate Limit Reached`, it's because you didn't run grip with your GitHub credentials or the provided credentials are incorrect.

Each project/lab has its own directory in which you'll find a `README.md` file and a sub-directory named `your-code`. The descriptions and requirements of the assignment can be found in the README file. When you work on the assignment, create your code files in the `your-code` directory and save regularly while you work.

Add those files to git, commit, and push your branch to GitHub.

```
$ git add <files-to-add>
$ git commit -m "Module 1 MySQL"
$ git push origin john-doe
``

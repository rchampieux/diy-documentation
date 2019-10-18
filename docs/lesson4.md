# Read the Docs Modification & Troubleshooting

![Workbench](images/workbench.jpg)

## Hands-on: Modification

You'll need a copy of your docs tied to your GitHub repo if you don't already have one.

1. Sign into [GitHub](https://github.com/login).
1. Go to your Forked version of [our sample repository](https://github.com/BioData-Club/my-first-rtd).  Forks of an original repo can be found by clicking the number next to **Fork** in the top right of the repo.
1. Click **Clone or Download** and then **Open in Desktop**.
1. Within GitHub Desktop there should be an **Open in Visual Studio Code** button.  Click that button.
1. Within Visual Studio Code, update the `contributors.md` file with your neighbor's name.
    - Bonus: Use `**bold**`, `*italics*`, `- bullets`, and `1. numbered lists`.  Remember the [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## Hands-on: Add a readthedocs.org maintainer

1. Log into [readthdocs.org](https://readthedocs.org/accounts/login/) with your GitHub account.
1. Click your name in the top right corner to go to **My Projects**.
1. Click your Read the Docs **Project**.
1. Click the **Admin** tab.
1. On the left menu click **Maintainers**.
1. Here you can add maintainers to your Read the Docs Project by typing in their Read the Docs **User** account name.

## Demo: Troubleshooting

Documentation site-breaking problems are usually confined to the `mkdocs.yml` YAML file.  To publish new content:

1. Make and save edits.
1. **Stage** your edits.
1. **Commit** your edits.
1. **Push** your commit.
1. Go to your **readthedocs.org** Project inside the **Builds** tab.
1. Click on the newest build.
1. Watch your docs build in real-time.

**Note**: If your edited docs look like they haven't changed even though you know you've changed them and the build has completed, try a different browser or an "Incognito Browser" mode to see newer edits.

## Discussion: What are some site-breaking things you can guess?

Problems I have run into:

- Incorrectly named `mkdocs.yaml` instead of the correct name, `mkdocs.yml`.
- Incorrectly spelled keys in `mkdocs.yml`.
- Special characters in `pages:` names.
- Incorrectly named or incorrectly placed `.md` files in `mkdocs.yml`.

```
        \          SORRY            /
         \                         /
          \    This page does     /
           ]   not exist yet.    [    ,'|
           ]                     [   /  |
           ]___               ___[ ,'   |
           ]  ]\             /[  [ |:   |
           ]  ] \           / [  [ |:   |
           ]  ]  ]         [  [  [ |:   |
           ]  ]  ]__     __[  [  [ |:   |
           ]  ]  ] ]\ _ /[ [  [  [ |:   |
           ]  ]  ] ] (#) [ [  [  [ :===='
           ]  ]  ]_].nHn.[_[  [  [
           ]  ]  ]  HHHHH. [  [  [
           ]  ] /   `HH("N  \ [  [
           ]__]/     HHH  "  \[__[
           ]         NNN         [
           ]         N/"         [
           ]         N H         [
          /          N            \
         /           q,            \
        /                           \
```
# Read the Docs Setup & Publish

Read the Docs simplifies documentation by automating building, versioning, and hosting of your docs for you.

## Getting started

Read the Docs requires a repository (a.k.a. repo) with a minimum of:

- A specifically formatted `mkdocs.yml` YAML file
- A `docs/` folder containing an `index.md` file

### A sample `mkdocs.yml` YAML file (**YAML** = **Y**AML **A**in't **M**arkup **L**anguage)

```yaml
site_name: My first readthedocs
theme: readthedocs
pages:
- Introduction: index.md
- Getting started: getting_started.md
```

## Hands-on

### GitHub Setup

1. Sign into [GitHub](https://github.com/login).
1. Fork [our sample repository](https://github.com/BioData-Club/my-first-rtd), the button is in the top right corner of the repository.

**Note ([from the glossary](https://diy-documentation.readthedocs.io/en/latest/glossary/#fork))**: A fork is a Git concept of copying a repository from someone else's ownership to your ownership, all the while maintaining the history

### Read the Docs Setup

1. Log into [readthdocs.org](https://readthedocs.org/accounts/login/) with your GitHub account.
1. Click the **Import a project** button which will bring you to the Import a Repository menu.
1. In the Import a repository menu select your forked repo with the **+ (plus)** sign.
1. Adjust the **Name** to something short and memorable for the documentation webpage name.
1. Click **Next** on Project Details.
1. Go to the **Admin** tab in the top right and then **Advanced Settings** on the left.
1. Change **Documentation type:** to **Mkdocs (Markdown)**.
1. Click **Save** at the bottom.

### Publish

1. To see publishing progress go to the **Build** tab and find the latest build.
1. When it says **Build completed** you can click the **View Docs** button to view those docs.

## Discussion: Your new site

Take a look at the front page of your newly published readthedocs.org site.  What advice might you suggest that you don't see there?

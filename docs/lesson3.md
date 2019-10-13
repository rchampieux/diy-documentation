# Read the Docs Setup & Publish

Read the Docs simplifies documentation by automating building, versioning, and hosting of your docs for you.

## Getting started

Read the Docs requires a repository (a.k.a. repo) with a minimum of:

- A specifically formatted `mkdocs.yml` YAML file
- A `docs/` folder containing an `index.md` file

### A sample `mkdocs.yml` YAML file

**YAML** = **Y**AML **A**in't **M**arkup **L**anguage

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
1. Click **Clone or Download** and then **Open in Desktop**
1. Within GitHub Desktop, go to **File** > **Clone Repository**
1. Clone *yourusername/my-first-rtd*

### Read the Docs Setup

1. Log into [readthdocs.org](https://readthedocs.org/accounts/login/) with your GitHub account.
1. Click the **Import a project** button which will bring you to the Import a Repository menu.
1. In the Import a repository menu select your repo with the **+ (plus)** sign.
1. Adjust the **Project Slug** to something short and memorable for the documentation webpage name.
1. Click **Next** on Project Details.
1. Go to the **Admin** tab in the top right and then **Advanced Settings** on the left.
1. Change **Documentation type:** to **Mkdocs (Markdown)**.
1. Click **Save** at the bottom.

### Publish

1. To see publishing progress go to the **Build** tab and find the latest build.
1. When it says **Build completed** you can click the **View Docs** button to view those docs.

## Discussion

- What do you notice about the table of contents?
- What does this documentation feel like it is missing?

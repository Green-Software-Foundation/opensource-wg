# Configuring this repository

This is a template repository based on docusaurus.io

## Update these files

### docusaurus.config.js

This configuration file defines many of the top level features of the website such as the menu, title etc...

Replace all references to `TODO` and `PROJECT-TITLE` with the appropriate content for your website.

### README.md

- Replace the `PROJECT-TITLE` with your projects title.
- Replace the `TODO's` with your content, including the main title.
- Ensure it refers to the right working group and URL.
- Ensure it refers to the right license.

### docs/index.mdx

This is the landing page of the website.

- Replace the `PROJECT-TITLE` with your projects title.
- Replace the `TODO's` with your content, including the main title.
- Add the right people to the Team section.
  - Every team member must have a GitHub profile.
  - The `<TeamMember>` component will source an image for each person from their GitHub profile.
- Every project index page must have:
  - A Summary
  - Links including the PR-FAQ
  - A getting started section for people new to the project
  - How the project communicates e.g. the main email address of the project).
  - Information regarding the core team.

### CONTRIBUTING.md

Double check that the content in this file is still applicable for your project and workflow.

### LICENSE

The license file is MIT, double check this is valid for you (MIT is the default license for the GSF except in some rare situations)

### .github/workflows/deploy-main.yml

- This is the GitHub Action that builds the website of this repository and deploys it.
- This yml uses GitHub pages to deploy the project based off the contents of the `main` branch.
- Every time there is a change made to the `main` branch this action is re-run and the website rebuilt.

If you are happy with this approach, nothing needs to be changed here.

### .github/ISSUE_TEMPLATE/meeting-template.md

This is a GitHub issue template for meeting agendas.

In this template you can define some default agenda items or other content which will appear in each meeting agenda, edit as you wish.

### static/CNAME

If you are using GitHub pages to deploy (the default) and you want to use a custom domain like `myproject.greensoftware.foundation` then you need to add **JUST** the text `myproject.greensoftware.foundation` to this file.

### Delete this CONFIGURE.md

Once you are happy with the setup please delete this file.

## Settings

### Deploying a website

The default platform we use for deploying websites is GitHub pages. You will need to add certain settings to your `/settings/pages` section of your repository to enable this.

### Custom Domain Names

Ask the GSF Ops team to create a `CNAME` record for the subdomain you want your project to live under greensoftware.foundation, e.g. for myproject.greensoftware.foundation they will need to create a `CNAME` record pointing `myproject` to `green-software-foundation.github.io`

# Android project proposal starter

## Project expectations

In coming up with a project topic and writing the proposal, please keep in mind the _basic_ requirements for the personal Android project:

* General data persistence using SQLite.

* User settings/preferences persistence using Shared Preferences or SQLite.

* Multiple screens with intuitive navigation.

* Data-driven presentation of content using flexible controls such as lists, grids, pagers, etc.

* Use of device services (e.g. sensors, camera), Android services requiring special permissions (e.g. contacts, messaging, external file storage), or cloud data sources/services (e.g. authentication providers, GIS/mapping services, machine learning platforms).

The above isn't an exhaustive list of Android project requirements, but should project sufficient direction for identifying a topic and writing the proposal.

## Proposal steps

Create a project proposal for a standalone Android project in this repository, as follows:

1. In the GitHub **Settings** screen for this repository, enable GitHub Pages by selecting **master branch `/docs` folder** from the **Source** pull-down in the **GitHub Pages** section.

    After making this change, a URL will appear at the top of the **GitHub Pages** section, after the text "Your is ready to be published at", or "Your site is published at"; this is the URL of the GitHub Pages site created from your repository.

2. Clone this repository to your local system.

3. In your local clone of the repository, edit `docs/_config.yml`, replacing the default values of the `author.name` and `author.href` properties with your name and a suitable URL (e.g. your GitHub profile page). Please preserve the formatting of this file, and the quotes around the values of the 2 modified properties. 

4. In your local clone of the repository, edit `docs/index.md` with the content of your proposal. 

    * Edit the `title` and `description` properties in the _front matter_ (the lines at the top, between the 2 lines that contain just 3 dashes each) to make them specific to your proposal.
    
    * Edit the Markdown content of the document to replace the instructions and sample content with content relevant to your project proposal.

5. In your local clone of the repository, edit `README.md` (i.e. this file), to include a brief summmary of your project for display in the default GitHub view of your repo (note that it will not appear in the GitHub Pages site). 

6. Commit your changes and push them to GitHub.

7. Review the GitHub Pages site created from your repository (via the URL referenced in step 1), as well as the summary displayed with the repository in GitHub, and repeat steps 4&ndash;5, as necessary.


# tomighty.github.io
Tomighty Github Page

This is the repository for the Tomighty website.

## Deploying

Currently the actual website content is hosted on the [tomighty-website repository](https://github.com/tomighty/tomighty-website). In order
to redeploy the website you must check out the website repository, build the site, and deploy it to this repository.

1. Check out the tomight-website project.
1. In the project directory, run `npm install`
1. Run `grunt` to build the website
1. Copy the contents of the `release` directory into this directory
1. Commit to this repository, or create a pull request if you lack commit access

That's it!

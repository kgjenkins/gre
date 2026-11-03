# Gardens of the Roman Empire Project

This repo contains the source files of the *Gardens of the Roman Empire* project.

## Hugo

We are using [Hugo](https://gohugo.io) with a heavily modified [Mainroad](https://themes.gohugo.io/mainroad/) theme.  The rendered website can be viewed locally by running `hugo server` from the main directory.  (Run `hugo server -D` to include drafts.)  This will update the website files in the `/docs` directory.  Note that the any changes to the `/docs` will be ignored when committing changes -- this helps to keep the repo size down.

The public website is built by running a GitHub Action that uses Hugo to publish the site to a separate repo named `roman-gardens.github.io`.  There are also actions to publish updates to various test websites -- this can be used to test changes more thoroughly before updating the public website.


## Basic Development

See the [GRE wiki](https://github.com/roman-gardens/gre/wiki)

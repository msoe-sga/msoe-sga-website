[![Build Status](https://travis-ci.org/msoe-sg/msoe-sg-website.svg?branch=master)](https://travis-ci.org/msoe-sg/msoe-sg-website)
## Welcome to the student government frontend repository. 
#### We're really happy to have you.

Keep reading to learn how to set up this repository.
In general, this repository is managed by the editor and few manual edits should be made; however, on the off chance you're one of the rare people interacting with the frontend directory, the setup instructions below should help you get started!

## Setup
1. Follow the instructions from the wiki article [here](https://github.com/msoe-sg/msoe-sg-website/wiki/Environment-Setup) to setup your development environment.
2. Open up a terminal to the folder where you want to clone the repo and run the command `git clone git@github.com:msoe-sg/msoe-sg-website.git`
3. After run the clone change into the project directory by running the command `cd msoe-sg-website`
4. Next install the dependencies for the site by running the command `bundle install`
6. If the bundle install command succeeds you should be able to run the site locally by running the command `bundle exec jekyll serve`. This should put forth some output, and you can now view the site locally on port 4000.
7. To test this, open a browser and navigate to `localhost:4000`. You should see the site up and running!
8. Contribute
Our git flow process is typical--we have a master branch that gets released to the public, a dev branch for merging ongoing development, and feature branches for individual tasks.
If you have questions on how to contribute, please contact admin@msoe-sse.com or msoe.sg.hosting@gmail.com and we will get back to you at our earliest convenience.

## Continuous Integration
There are checks that will be performed whenever Pull Requests are opened.  To save time on the build server, please run the tests locally to check for errors that will occur in the CI builds.

1. To run [Rubocop](https://github.com/ashmaroli/rubocop-jekyll), run the command `bundle exec rubocop -R`

Happy coding!

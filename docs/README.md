## Welcome to the student government frontend repository. 
#### We're really happy to have you.

Keep reading to learn how to set up this repository.
In general, this repository is managed by the editor and few manual edits should be made; however, on the off chance you're one of the rare people interacting with the frontend directory, the setup instructions below should help you get started!

## Environment
These instructions were written originally for an ubuntu 19.10 LTE release; a dockerfile is planned for the repo but not yet created.

1. Set up Ruby with RVM.
Follow the instructions located (here)[https://rvm.io/rvm/install]

2. Set up git on your machine (if you don't have it yet).
`sudo apt install git` 

3. Set up your ssh keys.
Run `ssh-keygen`, and follow the steps to create a public/private key pair.
In the github web interface, go to your profile > settings > SSH & GPG keys. Click on 'add a new SSH key'.
Now you are going to `cat` the location of your public key, and copy your public key to the textbox in the Github web interface.
For example, if my ssh key was located at /home/users/.ssh/id_rsa.pub, I would type
`cat /home/users/.ssh/id_rsa.pub`, copy the output and copy it into Github.

If you're not sure where your public key went, double-check the output from your earlier `ssh-keygen`.
Give your new key in github a title (like 'hobby-vm-keys' for example, just to tell you which machine is using the key), and save.

4. Okay, now you've successfully set up git, so we are going to clone the repository. Run the following:
`git clone git@github.com:msoe-sg/msoe-sg.github.io.git`
Check the output for errors. Assuming success, follow up with
`cd msoe-sg.github.io`

5. Set up bundler
This step depends on ruby and rvm being installed and working. To double check you can run
`ruby -v`
This project currently uses ruby 2.5.5, but our developers have used versions as late as 2.6.3.
To switch versions of ruby type
`rvm use x.x.x` where x.x.x is the version of ruby to use.

Assuming ruby 2.5.5 or greater, you can now run:
`gem install bundler`
And then:

'bundle install'

Pending the success of the above, you are now ready to build the website.

6. Run the site locally:
`bundle exec jekyll serve`

This should put forth some output, and you can now view the site locally on port 4000.
To test this, open a browser and navigate to `localhost:4000`. You should see the site up and running!

7. Contribute
Our git flow process is typical--we have a master branch that gets released to the public, a dev branch for merging ongoing development, and feature branches for individual tasks.
If you have questions on how to contribute, please contact admin@msoe-sse.com or msoe.sg.hosting@gmail.com and we will get back to you at our earliest convenience.

Happy coding!

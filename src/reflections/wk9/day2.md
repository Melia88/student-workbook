Day

Daily Challenge https://github.com/MichaelaBickish/neatpantry

Read Working In a Professional Environment > Github Actions and How to Use Them and answer the following questions

What is a Github action and how do they work?
>GitHub Actions are event-driven, meaning that you can run a series of commands after a specified event has occurred. For example, every time someone creates a pull request for a repository, you can automatically run a command that executes a software testing script.
The main concept at the heart of GitHub actions is the workflow; this is done by creating a series of YAML files that contain a series of actions that determine your workflow in your repositories. These YAML files are stored in a special folder in the .github/workflows folder inside your repository.

What benefits do Github actions provide?
> Gitub actions help us to be able to have some automatic testing for different parts of the application we're building. This is great because then we dont have to plysically test every aspect constantly but we can make sure its functional.

What types of trigger actions can a workflow use? What do they do?
>You can mannually trigger Github actions using GitHub api, repository dispatch events, and workflow dispatch events. There are also other event types that will trigger your workflow. There's Webhook events (things like commit and push), scheduled events, and external events via repository dispatch and workflow dispatch events
# HubSpot App Boilerplate

This is repository is used for testing the new HubSpot component generation tool via the [HubSpot CLI](https://github.com/HubSpot/hubspot-cli).
Specifically, this repository is used for generating components from non-hubspot owned repositories. It will mimic an random open source implementation some 3rd party could make.

## Getting Started
The `generator.json` is used for customizing the component generation process. The `generator.json` file is located in the root of the project.

Instead of structuring this like an entire project, we only maintain the root directory of the individual component. Only the directories & files within that root level directory will be copied over to the destination directory. All other files will be disregarded.

### Template Tags
The templating tags used in this project are using the [EJS](https://ejs.co/) syntax.
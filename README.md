# Pull-Request-Feedback-Plugin
This is a Chrome Plugin for GitHub to collect data from developers when they are reviewing pull requests in order to determine common features of "good" code changes.

**Note:** *This is a work in progress and is not recommended for use at this stage of development.*

## Getting Started:
![](https://raw.githubusercontent.com/achyudhk/Pull-Request-Feedback-Plugin/master/doc/screenshot.png)
### Prerequisites:
This extension is just a bundle of files that adds functionality to the Google Chrome browser. You will need a recent version of Google Chrome with developer mode enabled to install the unpacked plugin.
#### Permissions required:
These are subject to change in the coming build are more functionality is added.
  * Active Tab: To get the URL of the active webpage
  * Access to "https://github.com/*", "https://api.github.com/*" for the GitHub APIs
### Installing the extension:
For details on how to load an unpacked extension, you can read [this tutorial](https://developer.chrome.com/extensions/getstarted#unpacked) by Google.

## Limitations:
* Due to the use of Github API this is fully functional for public repositories in Github.com and not for corporate repos.
* Limited support can be extended to private and corporate repos wherein only the reviewer ratings and comments are sent to our database,

## Contributing:
When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change. Ensure any install or build dependencies are removed before the end of the layer when doing a build. Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.

## License:
This project is licensed under the MIT License - see the LICENSE.md file for details

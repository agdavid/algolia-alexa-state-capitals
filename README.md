# algolia-alexa-pokedex
Build an Algolia powered Alexa skill to fetch you pokemon.

**Note:** I am attempting to create this project using ["README Driven Development"](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html) as noted by [Dustin Coates](https://twitter.com/dcoates?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) in the post ["Perspectives on Building the Algolia Alexa Adapter"](https://www.talkingtocomputers.com/building-algolia-search-alexa-adapter), and, in turn, recommended to him, by [Vincent Voyer](https://twitter.com/vvoyer).


## But before you start...Developer Setup
If you don't already use Node, get setup the right way:

### Install Node.js "the right way"
There are many ways to get Node.js on your system (brew, setup files...) but the best way to do it is via nvm.

* Remove any system-wide Node.js installation: https://stackoverflow.com/questions/11177954/how-do-i-completely-uninstall-node-js-and-reinstall-from-beginning-mac-os-x
* Install nvm: https://github.com/creationix/nvm#install-script
* Open a new terminal to ensure nvm is installed: `nvm --version`

### Install Yarn "the right way"
* Remove any installation of Yarn: https://stackoverflow.com/questions/42334978/how-do-i-uninstall-yarn
* Install Yarn following this: https://yarnpkg.com/en/docs/install#alternatives-stable

🎉 Cheers to [Vincent Voyer](https://twitter.com/vvoyer) for the above method

In the next section you will utilize the [Algolia JavaScript API Client](https://www.algolia.com/doc/api-client/getting-started/install/javascript/) to push JSON data to a searchable Algolia index

Now, let's get going!

[GO TO Step 1 - Algolia Index](./instructions/algolia-index.md)
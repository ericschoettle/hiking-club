# hiking-club

This is a basic hiking club application, built as practice for using ember with firebase. 

## Functionality

* Home Page: All Users listed
* Click on list to go to dynamically generated details page.
* About page at the top.
* Save data to firebase.
* Pipes for favorite hiking location or style or something. 

* Admin route to add new users.
* Admin route to update and delete users.

* Bootstrap 

* Bonus: user authentication
* Bonus: deployment

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with NPM)
* [Ember CLI](https://ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone <repository-url>` this repository
* `cd hiking-club`
* `npm install`

## API Keys

* You will need to set up a project in firebase and put the keys in a file called "api-keys.ts". Make the file in the home directory of the project and make sure its name is included in the ".gitignore" file. Copy and paste the following code into the api-keys file.


* In the Firebase Console click on "add to website" and use the provided content to fill out the api-keys file seen above


## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Building

* `ember build` (development)
* `ember build --environment production` (production)



## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)

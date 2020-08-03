# Angular Watson Voice

This project is an update from [Angular Watson Voice](https://github.com/stevengregory/angular-watson-voice) by [stevengregory](https://github.com/stevengregory)

An [IBM Watson](https://www.ibm.com/watson/) speech to text application in Angular and Node. Uses the [Watson APIs Node.js SDK](https://www.npmjs.com/package/ibm-watson) library for speech to text services in web browsers.

![Angular Watson Voice](https://i.imgur.com/aMOLZav.gif)

## Requirements

1. Get IBM Watson service credentials

    * Sign up for a free [IBM Cloud account](https://console.bluemix.net/registration/?target=%2Fdeveloper%2Fwatson%2Fservices) or [log in](https://console.bluemix.net/login?state=%2Fdeveloper%2Fwatson%2Fservices).

    * Go to the [Watson Developer Services](https://console.bluemix.net/developer/watson/services) page.

    * Select Speech to Text and create a project.

    * Copy the credentials (API Key) to your service instance.

1. Install the [Angular CLI](https://cli.angular.io/)

    ```bash
    npm install -g @angular/cli
    ```

## Getting Started

1. Clone this repository

    ```bash
    git clone https://github.com/fcojlanda/angular-watson-voice
    cd angular-watson-voice
    ```

1. Install the npm packages

    ```bash
    npm install
    ```

1. Configure API Key value

    Copy the API Key from your Speech-To-Text service from your IBM Service platform. Replace <API_TOKEN> text located into the index.js file in the root server side by the real Api Key value with IBM Speech-To-Text credentials. No worries, the file is in the `.gitignore` so it won't get pushed to the GitHub repository.
    
## Running the app locally

1. Build the Angular app and launch the node server.

    Running this command will start both the client app & token server and open the browser to `http://localhost:4200`.

   ```bash
   npm start
    ```

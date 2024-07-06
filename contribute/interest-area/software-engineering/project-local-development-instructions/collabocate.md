---
description: SOFTWARE ENGINEERING CONTRIBUTING DOC FOR COLLABOCATE
---

# Collabocate

***

## Project description - page link

Find project description in the page attached below.

{% content-ref url="https://app.gitbook.com/s/D4inNwzMBU3WuBySeYcV/collabo-projects/collabocate" %}
[Collabocate](https://app.gitbook.com/s/D4inNwzMBU3WuBySeYcV/collabo-projects/collabocate)
{% endcontent-ref %}

***

## Local development instructions

* Head over to the GitHub repository: [https://github.com/collabo-community/collabocate](https://github.com/collabo-community/collabocate)
* Fork and clone the repository as shown in the [SWE contribution workflow](https://docs.collabocommunity.com/contribute/v/software-engineering/#git-workflow-fork-and-clone-repository).

Find the local development instructions for the different Collabocate projects in the tabs below, depending on the one you want to develop locally.

{% tabs %}
{% tab title="GitHub Sync" %}
{% hint style="info" %}
**Note 1 of 2:** There is migration going on for the API server, therefore there are 2 servers. Reason for retaining the old server for now: we still want to be able to run both the old API server and the new one, for comparison, upgrade and collaboration purposes.

**Note 2 of 2:** See instructions below for whether you wish to run the older API server or the new API server.
{% endhint %}

***

_**Running the server: Old API server**_

{% hint style="info" %}
Once you have the repository on your local computer, ensure you are _**in the root of the project's directory**_. Then install and run following the steps below.
{% endhint %}

* Install Dependencies: `npm install`
* Make a copy of the `.env.example` file, then rename the copy to `.env` - it is this renamed copy that you will store your secrets in. Ensure that the .env file is in the _**root of the project's directory**_.
*   In the `.env` file, supply:

    * The GitHub API url of your desired/chosen project in the `.env` file like this:

    ```
    GITHUB_API_URL=https://api.github.com/repos/your-own-github-account-user-name-will-be-here-instead/the-name-of-the-repo-you-want-to-interact-with
    ```

    * A GitHub personal access token for the GitHub account you are trying to access the repo for like this:

    ```
    GITHUB_PERSONAL_ACCESS_TOKEN=add-your-token-here
    ```

    * the port number of your choice (for the API server to run on) in the `.env` file e.g. `PORT=4200`
* Start the server: `npm start`
* Open your browser and navigate to `http://localhost:server-port-number-here`

***

_**Running the server: New API server**_

{% hint style="info" %}
Once you have the repository on your local computer, follow the steps below.
{% endhint %}

* Change directory into the `server` folder of in the root of the collabocate project/repository cloned
* Make a copy of the `.env.example` file, then rename the copy to `.env` - it is this renamed copy that you will store your secrets in. Ensure that the .env file is in the root of the `server` folder.
* In the `.env` file, supply:
  * the port number of your choice (for the API server to run on) in the `.env` file e.g. `PORT=8080`
* Start the server: `npm start`
* Open your browser and navigate to `http://localhost:server-port-number-here`
{% endtab %}
{% endtabs %}

***

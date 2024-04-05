---
description: SOFTWARE ENGINEERING CONTRIBUTION WORKFLOW
---

# Contribution Workflow for Software Engineers

***

## Community Contributing Guide

Visit the contributing guide page below to get directions about what is important in Collabo Community, and also learn how to make quality contributions to Collabo Community.

{% content-ref url="https://app.gitbook.com/o/-MWSSST6_GF5VEuG0Atd/s/XdbpF9uCzy0cC5JUJYyW/" %}
[Contributing Guide](https://app.gitbook.com/o/-MWSSST6\_GF5VEuG0Atd/s/XdbpF9uCzy0cC5JUJYyW/)
{% endcontent-ref %}

***

## Finding projects to contribute to

{% hint style="info" %}
See _**Collabo Projects**_ in the sidebar to find _**Software Engineering**_ project list and documentation pages. You will be able to get the link to the Github repository for the project that interests you from the pages there.
{% endhint %}

***

## Git workflow: Fork and Clone repository

Once you find a Software Engineering project that interests you contribute to, head over to the Github repository for that project.&#x20;

{% hint style="info" %}
Fork the repository. Then clone the forked repository unto your local computer.
{% endhint %}

**HTTPS url option:** If you are using `https` url, the clone command with your url will look like this:

{% code overflow="wrap" %}
```
git clone https://github.com/your-own-github-account-user-name-will-be-here-instead/the-repo-name.git
```
{% endcode %}

**SSH url option:** [See GitHub documentation for SSH configuration](https://docs.github.com/en/authentication/connecting-to-github-with-ssh) incase you wish to be able to work with SSH url for git operations (that is, if you have not set it up before). If you are using `SSH` url, the clone command with your url will look like this:

{% code overflow="wrap" %}
```
git clone git@github.com:your-own-github-account-user-name-will-be-here-instead/the-repo-name.git
```
{% endcode %}

{% hint style="info" %}
You can get the url to clone the project with, through the green code button in the repository on Github as shown below.
{% endhint %}

<figure><img src=".gitbook/assets/Screenshot 2023-11-13 at 01.39.27 (1).png" alt=""><figcaption><p>Position of the Green Code button and the popup to copy URL on GitHub</p></figcaption></figure>

***

## Installing dependencies and running the project locally

{% hint style="info" %}
Every project may have different instructions for how to install dependencies and how to run the project locally. See the _**Local development instructions**_ section of the documentation page of the project you are contributing to, so get specific instructions for that project.
{% endhint %}

***

## Git workflow: Create new branch to make your changes in

Except you are requested to create your branch from another branch, always create your new branch from the `develop` branch:

```
git checkout develop
```

```
git checkout -b replace-this-part-with-the-name-of-your-new-branch
```

***

## Git workflow: Add, commit and push changes to remote

**Make the desired changes** you wish to submit to the project, add, commit and push your changes:

```
git add .
```

```
git commit -m "replace this part with a commit message that describes your changes"
```

```
git push origin replace-this-part-with-the-name-of-your-branch
```

Then **send a pull request** for your changes to be reviewed.

***

## Pull request guidelines

See page below for the **guidelines for submitting pull requests to any repository**.

{% content-ref url="https://app.gitbook.com/o/-MWSSST6_GF5VEuG0Atd/s/kz0h3jWUEnMa4Mjjkort/" %}
[Pull Request Guidelines](https://app.gitbook.com/o/-MWSSST6\_GF5VEuG0Atd/s/kz0h3jWUEnMa4Mjjkort/)
{% endcontent-ref %}

***

# NativeScript Core Blank Template
App templates help you jump start your native cross-platform apps with built-in UI elements and best practices. Save time writing boilerplate code over and over again when you create new apps.

## Quick Start
Execute the following command to create an app from this template:

```
tns create my-blank-js --template ns-template-js
```

> Note: This command will create a new NativeScript app that uses the latest version of this template published to [npm] (https://www.npmjs.com/package/ns-template-js).

If you want to create a new app that uses the source of the template from the `master` branch, you can execute the following:

```
# clone repo locally
git clone git@github.com:shiv19/ns-js-template.git

# create app template from local source
tns create my-blank-js --template ns-template-js
```

**NB:** Please, have in mind that the master branch may refer to dependencies that are not on NPM yet!

## Walkthrough

### Architecture
The application root component is located at:
- `app-root.xml` - sets up a Frame that lets you navigate between pages.

There is a single blank component located in:
- `/home/home-page.js` - sets up an empty page layout.

**Home** page has the following components:
- `ActionBar` - It holds the title of the page.
- `GridLayout` - The main page layout that should contains all the page content.

## Get Help
The NativeScript framework has a vibrant community that can help when you run into problems.

Try [joining the NativeScript community Slack](http://developer.telerik.com/wp-login.php?action=slack-invitation). The Slack channel is a great place to get help troubleshooting problems, as well as connect with other NativeScript developers.

If you have found an issue with this template, please report the problem in the [NativeScript repository](https://github.com/NativeScript/NativeScript/issues).

## Contributing

We love PRs, and accept them gladly. Feel free to propose changes and new ideas. We will review and discuss, so that they can be accepted and better integrated.

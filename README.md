
Instructions to arthmate devs:
1. Repository is available publicly on github to be cloned
2. Repository is an initialized react application with the required html/jsx/css needed for the website version of the page
3. The form is just added as an image for now but has to be converted to textboxes and the form has to be submitted to google sheets API using your google sheets API key
4. It is recommended to not hardcode the google sheets api key in code, upload it to AWS secret manager using an existing AWS dev account and use a secret manager API to fetch the value
5. The current code repository has some dev dependencies specified in package.json which may need to be added to your existing package.json to work correctly. Storybook is optional and can be removed if necessary



## Getting started

> **Prerequisites:**
> The following steps require [NodeJS](https://nodejs.org/en/) to be installed on your system, so please
> install it beforehand if you haven't already.

To get started with your project, you'll first need to install the dependencies with:

```
npm install
```

Then, you'll be able to run a development version of the project with:

```
npm run dev
```

After a few seconds, your project should be accessible at the address
[http://localhost:1234/](http://localhost:1234/)


If you are satisfied with the result, you can finally build the project for release with:

```
npm run build
```

## Storybook

After installing, you can view your storybook by running:

```
npm run storybook
```

After a few seconds, your storybook should be accessible at the address
[http://localhost:6006/](http://localhost:6006/)

You can build your storybook for release with:

```
npm run build-storybook
```

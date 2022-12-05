> ⚠️ Warning - Alpha version - 
    This framework is under development and is unstable. It is not recommended to use it in production.

# Introduction
Angelic is a new batteries included web development framework for NodeJs. It is inspired from frameworks like .NET Core and Django.

# Installing
To install the framework, download or clone the project repository and place it in the bin folder of your project.

Run `npm install --save ./bin` to install the framework.

# Generating project template.
Project template can be generated using the Angelic-CLI. Run `angelic init` to create a new project.

This will create a new blank project and install all the dependencies.

# Running the project
If installed using the CLI, you can run the project using `node app.js` command.

## Use nodemon during development
Nodemon is automatically installed if the project is created using the CLI. If not, install nodemon using `npm install nodemon --dave-dev` command.

Add the following line to *package.json* under the scripts section.

```json
"scripts": {
    "start": "nodemon app.js",
    "test": "echo \"Error: no test specified\" && exit 1"
},
```

Run the project using:
```
npm run start
```
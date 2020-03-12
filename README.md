#Getting Started With Jest
Following [Facebook's Jest Tutorial](https://jestjs.io/docs/en/getting-started)

Created with Create React App.

**Issues:**
Per [StackOverflow](https://stackoverflow.com/questions/49616199/create-react-app-jest-syntaxerror-unexpected-token-import/49619012) add the following line to package.json to get the default CRA to work with the tutorial testing:
`"test": "react-scripts test --transformIgnorePatterns \"node_modules/(?!ui-core)/\" --env=jsdom"`

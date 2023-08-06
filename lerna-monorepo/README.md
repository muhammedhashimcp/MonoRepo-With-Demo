create a folder for project

create a folder for packages

create react app using npx create-react-app web-client in packages

create a server-api in packages folder

npm init -y

from the root folder 

npm init -y

npm i lerna -D

npx lerna init

npx lerna clean -y

installing package dependencies to root node_modules using:
npx lerna bootsrrap --hoist

add some scripts into root package.json

    "start": "lerna run start",

    "new-version":"lerna version --conventional-commits --yes",

    "diff":"lerna diff",

    "test": "lerna run test"

run the test script : npm run test

run script: npm run start

add scope for the scripts

    "test": "lerna run test --scope={web-client}",

    "start": "lerna run start --scope=web-client",

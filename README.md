# React-Prismic
Integration between React and Prismic

## Step to step
* Initialize project with: 
```bash
npm init or npm init -y if you want to skip the configuration
```
* Installing Typescript and Ts-Node-Dev
```bash
npm i typescript -D -E
npm i ts-node-dev -D -E
```
* * To add command-line scripts
```bash
"build": "tsc",
"start": "ts-node-dev src/index.ts",
"test": "echo \"Error: no test specified\" && exit 1",
"lint": "eslint --max-warnings 0 --ext .ts src/"
```
* Create the "src" folder and within the "index.ts" file

* Run in the console: 
```bash
npm run start -- --init
npm run build -- --init
```
It creates the tsconfig.json

* Please install Eslint
```bash
npm i eslint -D -E
```
* Let's initialize Eslint. Running the following command, it creates the eslintrc.json
```bash
npx eslint --init 
```
* Update the tsconfig.json based on your preferences! Git ignore must be updated to check the "# Compiled binary addons". Run the following command for creating your built solution:
```bash
npm run build
```
* At this point, our project should compile successfully! Take a look on eslintrc.json and tsconfig.json if you have issues.
# Terminal-Commands

## All basic terminal commands in one place

<h3 align="center">Show some ❤ by <img src="https://imgur.com/o7ncZFp.jpg" height=25px width=25px> some repositories</h3>

You can contribute to this readme
If you want to contribute with a loooot of commands make a new .txt file / if you see old commands don't tell me fork it and feel free to contribute in this OpenSource Project..

<hr>
<p text-align="center">

[Git Commands](https://github.com/shehza-d/Terminal-Commands#git-commands)

[NEXT JS Commands](https://github.com/shehza-d/Terminal-Commands#next-js-commands)

[Tailwind Commands](https://github.com/shehza-d/Terminal-Commands#tailwind-css-commands)

[React Commands](https://github.com/shehza-d/Terminal-Commands#react-commands)

[Node Commands](https://github.com/shehza-d/Terminal-Commands#node-commands)

[ExpressJS Commands](https://github.com/shehza-d/Terminal-Commands#expressjs-commands)

[React-Native Commands](https://github.com/shehza-d/Terminal-Commands#react-native-commands)

[FireBase Commands](https://github.com/shehza-d/Terminal-Commands#firebase-commands)

[Netlify Commands](https://github.com/shehza-d/Terminal-Commands#netlify-commands)

[TypeScript Commands](https://github.com/shehza-d/Terminal-Commands#typescript-commands)

[Important NPM Packages](https://github.com/shehza-d/Terminal-Commands#important-npm-packages)

[Linux COMMANDS](https://github.com/shehza-d/Terminal-Commands#linux-commands)

</p>
<hr>

## Git Commands

```
git init

git add *

git commit -m "Pushing new Changes"

git branch -m main

git add remote url_here

git push -u origin main
```

```
git branch branch_name
```

```
git checkout branch_name
```

first time only

```
git config --global user.name "Shehzad"
git config --global user.email "shehzaddiqbal@gmail.com"
```

```
git status
```

to save git credential

```
git config --global credential.helper 'cache --timeout=2628288'
```

`.gitignore` will prevent untracked files from being added (without an add -f) to the set of files tracked by Git. However, Git will continue to track any files that are already being tracked.
<https://stackoverflow.com/a/1274447/18210334>
To stop tracking a file, we must remove it from the index:
```bash
git rm --cached <file>
```

To remove a folder and all files in the folder recursively:
```bash
git rm -r --cached <folder>
```

<hr>

## NEXT JS Commands

```
npx create-next-app
```

NEXT 13

```
npx create-next-app@latest --experimental-app --typescript --eslint
```

```
npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion @chakra-ui/icons
```

<hr>

## Tailwind CSS Commands

```
npx tailwindcss init -p
```

```
npm i -D tailwindcss postcss autoprefixer
```

```
npm i -D prettier-plugin-tailwindcss
```

to sort tailwind classes(prettier extension needed)

```
npx tailwindcss init  sdConfig --full
```

<hr>

## TurboPack Commands

```
npx create-next-app@latest -e with-turbopack
```

```
npx create-next-app --example with-turbopack
```

```
next dev --turbo
```

<hr>

## React Commands

```
npx create-react-app myappname
```

(to create react project)

```
npx create-react-app app_name --template redux-typescript
```

<hr>

## Node Commands

```
node --version
```

```
node index.js
```

(to execute a file e.g node fileKaName.js)

installing nvm

```
nvm install (version) like (12.16.3)
```

phir

```
nvm use 12.16.3
```

<hr>

## ExpressJS Commands

```
npm init -Y
```

(to initinil node project is easy words to create package.json) -y for default settings

    npm install express

(to initilize express project express ky liye)

```
node index.mjs
```

<hr>

## React-Native Commands

```
npx react-native init AwesomeProject
```

```
npx react-native start
```

```
npx react-native run-android
```

<hr>

## FireBase Commands

```
npm install -g firebase-tools
```

(install CLI(also use this command to update CLI))

    firebase login

(first time only)

    firebase init

(initilize project(apne project ma run karna ye))

    firebase deploy --only hosting

firebase deploy other options [(--only hosting),(--only database),(--only storage),(--only firestore),(--only functions)]

```
npm install firebase@latest --save
```

```
firebase --help
```

<hr>

## Netlify Commands

```
npm install netlify-cli -g
```

(first time only)

```
netlify login
```

(first time only)
!(netlify init)

```
netlify deploy --prod
```

    netlify status

```
netlify help
```

```
netlify logout
```

<!-- ## MongoDB Commands
```
npm i mongoose
``` -->
<hr>

## Material UI

```
npm install @mui/material @emotion/react @emotion/styled
```

```
npm install @mui/material @mui/styled-engine-sc styled-components
```

```
npm install @fontsource/roboto
```

<hr>

## TypeScript Commands

```
npm install typescript --save-dev --global
```

```
tsc --init
```

(to make ts.config)

```
tsc index.ts
```

(file name to compile a file)

```
npx create-react-app app_name --template typescript
```

<hr>

## Prettier

```
npx prettier --write .
```

to format all files in a project (even without extension installed)

<hr>

<!-- ## Sanity

```
npm create sanity@latest -- --template get-started --project key --dataset production --provider github
```

<hr> -->

## Important NPM Packages

```
npm i mongoose cors formik yup react-router-dom react-icons prompt-sync
```

<hr>

## Linux COMMANDS

show wifi passwords linux
```
nmcli device wifi show-password
```

1. cd
   dir or ls (to view files in directories.)

```
sudo apt install node npm git code
```

```
sudo snap install vlc code telegram-desktop chromium gimp && sudo snap install shotcut --classic
```

## DotNet on Ubuntu for C#

sudo apt-get install wget apt-transport-https

wget https://packages.microsoft.com/config/ubuntu/20.04/packages-microsoft-prod.deb

sudo dpkg -i packages-microsoft-prod.deb

sudo apt-get update

sudo apt-get install dotnet-sdk-5.0

dotnet --version

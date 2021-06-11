# BYU_RN_Template

Barebones-Yet-Useful React Native starter template

Idea: Barebones-Yet-Useful puts in only the very important extra libraries for navigation, basic components, etc and gets you started with building react native apps without initial setup of very useful features most app ideas require.

How to?

1. Clone the repo
2. Change folder name to something of your choice
3. `cd <folder_name> && yarn install`
4. `cd ios && pod install`

How to change name?

1. A super useful package "react-native-rename" already gets installed as part of previous yarn install
2. `npx react-native-rename <new_name>`
3. For Android to change the bundle name as well - `$ npx react-native-rename <newName> -b <bundleIdentifier>`
4. For iOS, clean the build folder (or use XCode), re-build, and then re-install all packages.

Committing this new repo to Github?

1. `gh repo create` - ignore the error thrown that remote origin exists (it will be fixed below).
2. `git remote remove origin`
3. Open the created repo page (.git)
4. Then follow steps below "…or push an existing repository from the command line"
5. Edit the README.md file in root of this repo to suit your needs.

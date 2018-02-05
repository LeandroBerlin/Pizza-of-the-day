# Pizza-of-the-day

Modified version of Wes Bos "React for Beginners" course app. Eat Pizza instead of fishes!

![Screenshot](./screen.png?raw=true "Screenshot")

## Features

- The StorePicker components show a list to *"View existing Stores"* from Firebase
- Images are stored locally
- Currency is € and formatted also in the Inventory edit
- Some styles have been added
- Auth method is only github
- Rewrited custom names/adjectives in helper file
- Changed deployment workflow on Now.sh
- Added serve package
- Fixed reload issue

## Deployment
The app is on Now.sh, I deployed using "serve":

- add serve

npm install --save serve

- in Package.json add a script

"now-start": "serve --single ./build"

- deploy using

now

## Project

### Homepage
https://cotd-ydnmcyegrm.now.sh/

### Existing Store example
https://cotd-ydnmcyegrm.now.sh/store/bella-roma

:pizza: Enjoy!

# node_react
 brew tap mongodb/brew
 brew install mongodb-community
 sudo mkdir -p /System/Volumes/Data/data/db
 sudo chown -R `id -un` /System/Volumes/Data/data/db
 brew services run mongodb-community
 brew services list
 mongo
 
 show dbs
 use signatures
 show collections
 db.createCollection('guest_signatures')
 
 npx express-generatort
 npm i
 touch .gitignore  # add node_modules
 npm start
 
https://dev.to/pacheco/my-fullstack-setup-node-js-react-js-and-mongodb-2a4k
npm init -y
npm install express body-parser mongoose
npm install --save-dev nodemon concurrently
mkdir models routes
touch index.js


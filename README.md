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
 
 npx express-generator
 npm i
 touch .gitignore  # add node_modules
 npm start
 

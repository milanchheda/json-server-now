# json-server-now
Getting json-server to work on now.sh

#Getting started.
```
git clone https://github.com/milanchheda/json-server-now.git

cd json-server-now
npm install
node db.js
npm install now (To get now.sh working)
now (and your backend is up and running)
```
=======

#Need some fake data for your team mates? Here is what you can do:

Just change the package.json's script section to look like this:

```
"scripts": {
    "start": "json-server faker.js"
}
```

then type:
```
now
```

Your backend is up and running in the cloud with 100 amazingly real looking fake users ready for your app or front end

NPM package: https://www.npmjs.com/package/json-server
Github: https://github.com/typicode/json-server

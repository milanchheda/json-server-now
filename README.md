# json-server-now
Getting json-server to work on now.sh

#Getting started.
```
git clone https://github.com/milanchheda/json-server-now.git

cd json-server-now
npm install
node db.js <-- to run locatlly.
npm install now (To get now.sh working)
now (and your backend is up and running)
```
=======

#Need some "Fake" informatin in your people's table to get real looking users in your system?

Want to run it on now.sh? Simple.
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

ENJOY!!!  

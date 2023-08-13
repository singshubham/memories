# Memories-Bazinga

![Image 1](https://raw.githubusercontent.com/paramj0t/memories-bazinga/master/images/1.png)  


Memories-Bazinga is a website where users can add their Memories. In order to review or add memories or anything, you must have an account.

This project was created using React, Node.js, Express, MongoDB, and Material-UI. JWT and Google OAuth was used to handle authentication.

## Features

- Users can create, edit, and remove Memories.
- Users can review memories, and edit or remove their post.
- Search memories by name of post or tag.
- User can like others post.
- User can add Images.

## Run it locally

1. Install [mongodb](https://www.mongodb.com/) add your credentials

```
git clone https://github.com/paramj0t/memories-bazinga.git
cd Memories
npm install
```

Create a .env file (or just export manually in the terminal) in the root of the project and add the following:

```
DATABASEURL='<url>'
```

Run `mongod` in another terminal and `node app.js` in the terminal with the project.

Then go to [localhost:3000](http://localhost:3000/).

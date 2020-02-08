# fullstackJS-blog
React.js, Javascript, React Router Dom, Npm, Babel, Nodemon, Webpack, Express.js, Node.js, MongoDB

**Front-End**

Create a React App

`npx create-react-app blog --use-npm`

Run react

`npm start`

Install react-router-dom
`npm install react-router-dom`

**Back-End**

```
npm init -y
npm install --save express
npm install --save-dev @babel/core @babel/node @babel/preset-env
```

Run node server

`npx babel-node src/server.js`

Install other useful packages

```
npm install --save body-parser

npm install --save-dev nodemon

npx nodemon --exec npx babel-node src/server.js
```
Create Database Directory and give yourself user rights

```
sudo mkdir -p /data/db
sudo chown -R `id -un` /data/db
```

Install Mongo
`npm install --save mongodb`


Simple blog deployed using an AWS EC2 instance http://ec2-18-232-150-118.compute-1.amazonaws.com/

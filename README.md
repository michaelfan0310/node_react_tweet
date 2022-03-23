



Homebrew Commands:
```javascript
brew update
brew upgrade
```

Check which version of Node and NPM you are running:
```javascript
node -v
npm -v
```

Initialize a React App:
```javascript
npx create-react-app frontend
or
npm init react-app ./frontend
```

Initialize the Node backend:
```javascript
mkdir backend
cd backend
npm init -y
```

frontend folder needs this package installed:
```javascript
npm install react-router-dom
```

backend folder needs these packages installed:
```javascript
npm install --save-dev nodemon
npm install express body-parser concurrently
```

Update the frontend/package.json with the "proxy" code:
```javascript
"proxy": "http://localhost:4000/",
```

See the package.json file for npm run scripts.
bkend: npm run server
ftend: npm start

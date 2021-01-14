v. 1.0.0

npm init -y # creates a default package.json

npm i -D webpack webpack-cli

mkdir src
cd src
echo "console.log("test") > index.js

cd ..
vim webpack.config.js

npm i -D html-webpack-plugin

touch src/template.html

npm i -D clean-webpack-plugin

npm i -D babel-loader @babel/core @babel/preset-env @babel/plugin-proposal-class-properties @babel/preset-react

npm i -D webpack-dev-server

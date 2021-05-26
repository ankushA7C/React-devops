# React-devops

npm install pm2-windows-startup -g
pm2 start node_modules/react-scripts/bin/react-scripts.js --name projectname -- start
pm2 start node_modules/react-app-rewired/scripts/start.js --name projectname -- start
pm2-startup install
pm2 save
 

![image](https://github.com/justin0006/Manual-3-tier/assets/116922065/b6f38ea9-3818-41cc-a0e9-b76b6257e185)![image](https://github.com/justin0006/Manual-3-tier/assets/116922065/835bf334-3b28-450c-979b-e8235da38d7e)# Manual-3-tier
git clone https://github.com/justin0006/todoapp-frontend-react.git

Install NodeJs 16.x and NPM on Ubuntu ===>> google to install specific version of nodejs16

Update the backend URL in the src/TodoApp.js

Run npm install   ===>>> you need to be inside your dir and run command then node_modiles dir is going to be created. 

RUn npm run build  ===>>> by running this command we will get build dir where all css, html etc present 

Install nginx ===>> gooogle to get commands

Make sure port 80 is opened
copy ip and go to browser paste ip:80  ///to make sure nginx is running
you need to be inside build
we need to copy all our artifacts inot /var/www/html
sudo cp -r * /var/www/html   ===>>> all artifact copied here
sudo systemctl restart nginx


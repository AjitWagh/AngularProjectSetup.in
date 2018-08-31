# project.in
It containing normal setup of angular

#Basic structure
GIT
Sign up and Create Repository
Create repository on command line(also refer ss) -
		
		Angular Setup

Structure - 
client – Its a user View
	index.html – includes all files
	app.js –  includes state(URL)
	index.js – includes all modules names
	Modules(folder) –  it will contain different different modules folders and each 				module will contain 3 files controller,index.js,template html 				file 
	for ex –  main module(folder) - 
			index.js –  contains template url 
			controller.js – contains controller of module
			main.html –  template of module  
	css(folder) – css file or bootstrap file can put 
	lib(folder) - 

bower.json –  contains all dependencies
package.json – contains packages
server.js – contains server details
node_modules - 

# Commands and setup

Project setup : 

npm init
npm intall
bower install
npm install bower
sudo npm install -g  bower
npm install -g bower
node server


git : 

git remote add origin https://github.com/saitejan/oredersquery.git
git push -u origin master
git commit -m "second commit"
git init

AWS

once account is created do following :
first go to home directory

cd
after account creation on aws one file will be downloade(pem file) save it carefully and run below command.	

ssh -i grocerydeal.pem ubuntu@18.217.5.131
chmod 700 grocerydeal.pem 
ssh -i grocerydeal.pem ubuntu@18.217.5.131
git clone https://github.com/AjitWagh/GroceryDeals.git
ls
ls -lah grocerydeal.pem 
cd GroceryDeals	
sudo apt-get update
pm2 start app.js –name="GROCERY"


*************AWS********************

cd ~
ssh -i grocerydeal.pem ubuntu@18.217.5.131
pm2 list
cd GroceryDeals
pm2 start app.js 
forever list










#####AWS######
cd ~
ssh -i grocerydeal.pem ubuntu@18.217.5.131    ==>login to aws
ls
cd GroceryDeals    ===> name 
ls
git pull     ====> pull data(project) from github 
pm2 list  ===>
forever list  ===> running 
forever restart cClY(uid)  ====>restart with userid











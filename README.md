# Publish JS package to NPM for sharing


As we know, we can publish .Net packages to Nuget, in Node JS, we also can publish JS file as package to NPM which is the package manager for Node JS. This documentation will show you how to get started

1, download Node JS and install it in your local machine c://
2, create a folder called TieshanNode in c://TieshanNode
3, come to github to create a new repository such as TieshanNode
4, open gitshell in local machine and run command git clone https://ithub.com/davidlizhonghuang/tieshannode, this repository is copied to local
5, cd tieshannode to let cmd access to this github folder
6, now we are in place to create package, however, at first, we need to configure my account 
run 
  1,npm set init.author.name "david huang"
  2,npm set init.author.eamil "clousoversea@gmail.com"
  3,npm set init.author.url "http://www.y9se.com"
run
  npm adduser
7, now add index.js file to this folder, add some js code in
8, now the key step is to run 
>npm init
this command will create package.json via ask you some questions
9, we have a index.js and a package.json file in this folder
10, you can test the code or you can directly to publish both to NPM
11, in gitshell to run 
>git add package.json  index.js 
12, 
>git commit -m "prepare for 0.0.1"
13, check version
>npm version
14, now run
>git push
>git push --tags  //this said everything is up-to-update
15, publish JS files
>npm publish 
+ tieshannode@0.0.1  it the output
16, cmd to another folder such as c://000at
17, run 
npm install tieshannode
18, this package is installed in 000at folder with folder node_modules 
19, open this node_modules folder, you can see all JS files are downloaded
20, npm install is downloading this apckage from your github with the URL od repository we worked on
21, github will update record to tell you you just are making a new contribution
22, so this package is shared by anyone in this world.





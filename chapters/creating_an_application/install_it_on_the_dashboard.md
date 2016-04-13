# Install an application on the Dashboard

Once you have created your first app, you will be able to install it on the dashboard. 

You can do it in some different ways:


### 1. Install an application through Netbeast Market

People can publish their apps & plugins on github and they will be able to people directly on the dashboard. If you want to see more information about this, go [here](publish_your_app.md)

Then, you only need to click on the "explore" icon and then look for that apps and plugins you want to install.

Really easy :smiley:


![Install through explore](../../img/install_explore.gif)



### 2. Install an application through github

1. Firstly you need to upload your application to a github repository.

2. Secondly, go to the >Install secction on the dashboard and then click on the option "with git". After that, you only need to copy your repository name there and click on "install".

3. Finally you will have your app installed.

![Install through github](../../img/github_app.gif)


### 3. Install an application through Drag & Drop

First you need to package your folder application in a .tar.gz format

#### Package your app
```
beast pkg .
# alias for "netbeast package"
```

Will output app.tar.gz

**But you could do that also manually!** Using the UNIX compressing tool:
```
tar -zcvf app.tar.gz directory-name
```
Or a standard desktop compressor.


#### Drag & Drop

Drag and drop the above resulting file to the dashboard, or go to the 'install' section from the tool bar and follow the instructions.



### 4. Install through SDK
```
beast install app.tar.gz
```
It will prompt to ask you which Netbeast to install in if there are a number of them running in the same network.


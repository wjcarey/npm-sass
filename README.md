# npm-sass
Quickly intall Sass on a exsisting project works with WordPress too!

## Requirements
node.js and commandline

### instructions for fresh install
from your commandline, navigate to the directory you will be working from. 
~~~
git clone https://github.com/wjcarey/npm-sass.git
~~~

Copy the repository files into your directory and run 
~~~
npm install.
~~~

### instructions for project already configired with a package.json file
Ammend your exsisting pacakge.json file with the additional object. Edit the object to reflect your current css file structure/location or create this file structure.
~~~
sudo touch assets/css/app.css && style.css
~~~

re-run npm install to configure sass into the project.
~~~
npm install
~~~

### post install
to compile files run:
~~~
npm watch
~~~

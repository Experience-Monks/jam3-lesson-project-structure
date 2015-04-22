# jam3-lesson-project-structure


This is a lesson on how Jam3 structures projects. In an effort to reduce project set up times and improve consistency, Jam3 is presently in the process of standardizing its project structure and formalizing it into a yeoman generator. If you would like a more indepth look at the folder structure and file contents install the generator and you will be able explore the contents of a standard Jam3 project.

If you would like to take a look at the Jam3 Generator and see how to use it, please visit the github repo: https://github.com/Jam3/generator-jam3


<a name="readme"></a>
##Project Root

```
project
    ├── README.md
    ├── package.json
    ├── bower.json    
    ├── Gruntfile.js
    ├── index.js
    ├── app
    ├── lib
    ├── node_modules   
    ├── raw-assets    
    ├── tasks
    └── test
```
<a name="readme"></a>
####README.md
The `README.md` file is the first thing you should read or write when starting on a project. Typically it will contain a brief technical overview, set up and run instructions, deployment strategy, as well as style guide and any reference material.

<a name="packagejson"></a>
####package.json
This contains a list of all your npm modules being used in the project as well as info about project. You will most likely not have to edit this manually after it is created with the genetator. Ensure you are using --save when installing a new module, or --save-dev when installing a module that is not used in the final javascript bundle.

<a name="bowerjson"></a>
####bower.json
This file contains all the packages that are brought in through bower. This is not a mandatory file in all projects, it is only required if the developers choose to use it.

<a name="gruntfile"></a>
####Gruntfile.js
This file contains all tasks used to build the project. The generator creates many of the tasks you will need, but new tasks may need to be added.

<a name="gruntfileex"></a>
####index.js
The entry point for your application, there should be very little logic in this file, simply instantiating your app is the general use.

<a name="lib"></a>
##lib

Your application logic goes into the lib folder. The structure of the folder is detailed below.

```
project
    └── lib
        ├── framework
        │   ├── index.js
        │   └── routes.js
        ├── less
        │   ├── fonts.less
        │   ├── global.less
        │   ├── main.less
        │   ├── normalize.less
        │   └── vars.less
        ├── model
        │   └── index.js
        ├── sections
        │   └── Landing
        │       ├── index.js
        │       └── style.less
        └── ui
            └── Landing
```
<a name="framework"></a>
###lib/framework
Framework logic built off of bigwheel. For documentation on the framework, visit the github page: https://github.com/Jam3/bigwheel

* `index.js`
* `routes.js`

<a name="less"></a>
###lib/less
The root less folder contains all your global project styles. normalize.less should not be modified as it is an external stylesheet. 

* `fonts.less`
* `global.less`
* `main.less`
* `normalize.less`
* `vars.less`

<a name="model"></a>
###lib/model
This file contains copy and settings for each of your sections. If the copy needs to be multilingual, it is wise to put it into external files and load them dynamically.

* `index.js`

<a name="sections"></a>
###lib/sections
All the logic, styles, and templates for a sepcific section. the template file will change depending on the templating system used. Common templating systems used are handlebars and vuejs.

* `Landing/index.js`
* `Landing/style.less`
* `Landing/template.*`

<a name="ui"></a>
###lib/ui
lorem ipsum

* `Landing/`



<a name="app"></a>
##app

lorem ipsum



<a name="node_modules"></a>
##node_modules

lorem ipsum


<a name="raw-assets"></a>
##raw-assets

lorem ipsum

* `fonts`
* `images`
* `json`
* `sounds`
* `tp`
* `videos`



<a name="tasks"></a>
##tasks

lorem ipsum



<a name="test"></a>
##test

lorem ipsum


<a name="fullprojecttree"></a>
##Full Project Tree

```
project
    ├── Gruntfile.js
    ├── README.md
    ├── app
    │   └── index.html
    ├── bower.json    
    ├── index.js
    ├── lib
    │   ├── framework
    │   │   ├── index.js
    │   │   └── routes.js
    │   ├── less
    │   │   ├── fonts.less
    │   │   ├── global.less
    │   │   ├── main.less
    │   │   ├── normalize.less
    │   │   └── vars.less
    │   ├── model
    │   │   └── index.js
    │   ├── sections
    │   │   └── Landing
    │   │       ├── index.js
    │   │       └── style.less
    │   └── ui
    │       └── Landing
    ├── node_modules
    ├── package.json    
    ├── raw-assets
    │   ├── fonts
    │   ├── images
    │   ├── json
    │   ├── sounds
    │   ├── tp
    │   │   ├── common
    │   │   └── common.tps
    │   └── videos    
    ├── tasks
    │   └── texturepacker.js
    └── test
```

## Usage

[![NPM](https://nodei.co/npm/jam3-lesson-project-structure.png)](https://www.npmjs.com/package/jam3-lesson-project-structure)

## License

MIT, see [LICENSE.md](http://github.com/Jam3/jam3-lesson-project-structure/blob/master/LICENSE.md) for details.

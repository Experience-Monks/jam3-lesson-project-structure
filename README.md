# jam3-lesson-project-structure


This is a lesson on how Jam3 structures projects. Maybe a note about generator-jam3.



<a name="readme"></a>
##Project Root
---

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
lorem ipsum

<a name="bowerjson"></a>
####bower.json
lorem ipsum

<a name="gruntfile"></a>
####Gruntfile.js
lorem ipsum

<a name="gruntfileex"></a>
####index.js
lorem ipsum


<a name="lib"></a>
##lib
---

lorem ipsum

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
lorem ipsum

* `index.js`
* `routes.js`

<a name="less"></a>
###lib/less
lorem ipsum

* `fonts.less`
* `global.less`
* `main.less`
* `normalize.less`
* `vars.less`

<a name="model"></a>
###lib/model
lorem ipsum

* `index.js`

<a name="sections"></a>
###lib/sections
lorem ipsum

* `Landing/index.js`
* `Landing/style.less`

<a name="ui"></a>
###lib/ui
lorem ipsum

* `Landing/`



<a name="app"></a>
##app
---
lorem ipsum



<a name="node_modules"></a>
##node_modules
---
lorem ipsum


<a name="raw-assets"></a>
##raw-assets
---
lorem ipsum

* `fonts`
* `images`
* `json`
* `sounds`
* `tp`
* `videos`



<a name="tasks"></a>
##tasks
---
lorem ipsum



<a name="test"></a>
##test
---
lorem ipsum


<a name="fullprojecttree"></a>
##Full Project Tree
---
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

# Project Name - V0.0.0

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 

* Browsers: Chrome, Internet Explorer (IE9 and over), Firefox, Opeara
* Responsive: Yes
* Form Validation: Yes
* CMS: Ektron
* Back-end Language: C#.NET

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

This project workflow is comprised of tools for improving your productivity and satisfaction when building a web project.


## Contacts
* [First Last](first.last@email.com) - Project Manager
* [First Last](first.last@email.com) - Front End Lead
* [First Last](first.last@email.com) - Back End Lead
* [First Last](first.last@email.com) - QA Lead


## Requires
Install or make sure you have installed:

* Install Grunt globally: `npm install -g grunt-cli`. Check Grunt version `grunt -v`.
* Install Bower globally: `npm install -g bower`. Check Bower version `bower -v`.
* Node.js, Git and Compass.


## Getting Started
Clone the project on your [dev] folder.
```
git clone ssh_url
```

Access your project folder
```
cd project_name
```

Intall project dependencies
```
npm install
```

Intall packages 
```
bower install
```


## Documentation
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 

* [Basics](http://project-basic)
* [CSS](http://project-css)
* [Forms](http://project-forms)
* [Components](http://project-components)
* [JavaScript](http://project-javascript)


## Grunt Tasks
See `package.json` for more details on dependancies.

Run project and preview in browser
```
grunt serve
```

Building project for production
```
grunt 
```


## Features

* CSS Autoprefixing *(new)*
* Built-in preview server with LiveReload
* Automagically compile Sass files
* Automagically lint your scripts
* Automagically wire up your Bower components with [bower-install](#third-party-dependencies).
* Awesome Image Optimization (via OptiPNG, pngquant, jpegtran and gifsicle)
* Foundation Framework - Bootstrap
* CSS extension language - Sass
* Optional - Leaner Modernizr builds *(new)*
* Includes html5shiv and respond.js for IE8 and lower browsers

For more information on what tools this project contains, take a look at the `package.json`.


## Third-Party Dependencies

*(HTML/CSS/JS/Images/etc)*

Third-party dependencies are managed with [bower-install](https://github.com/stephenplusplus/grunt-bower-install). Add new dependencies using **Bower** and then run the **Grunt** task to load them:

```bash
  bower install --save jquery
  grunt bowerInstall
```

This works if the package author has followed the [Bower spec](https://github.com/bower/bower.json-spec). If the files are not automatically added to your index.html, check with the package's repo for support and/or file an issue with them to have it updated.

To manually add dependencies, `bower install depName --save` to get the files, then add a `script` or `style` tag to your `index.html` or another appropriate place.

The components are installed in the root of the project at `/bower_components`. To reference them from the `grunt serve` web app `index.html` file, use `src="bower_components"` or `src="/bower_components"`. Treat the references as if they were a sibling to `index.html`.


## Testing Note
A project checked into source control and later checked out, needs to have `bower install` run from the project root.

### SEO Testing
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 

### Accessibility Testing
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 


## Options
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 


## Modifications and Fixes
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 


## License
Company_Name

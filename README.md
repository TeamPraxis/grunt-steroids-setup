# grunt-steroids-setup

> Script the creation of a steriods build

## Getting Started
This plugin requires Grunt `~0.4.4`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-steroids-setup --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-steroids-setup');
```

## The "steroids_create" task

### Overview
In your project's Gruntfile, add a section named `steroids_create` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  'steroids_create': {
    options: {
      // Task-specific options go here.
    },
    your_target: {
      // Target-specific file lists and/or options go here.
    },
  },
});
```

### Options

#### options.buildFolder
Type: `String`
Default value: `./build`

The build folder to create the Steroids template in

#### options.steroidsPath
Type: `String`
Default value: ``

Path to the steroids application



## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History
_(Nothing yet)_

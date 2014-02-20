*This repository is a mirror of the [component](http://component.io) module [component/cookie](http://github.com/component/cookie). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-cookie`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# cookie

  Cookie component.

## Installation

    $ component install component/cookie

## Example

```js
// set
cookie('name', 'tobi')
cookie('name', 'tobi', { path: '/' })
cookie('name', 'tobi', { maxage: 60000 }) // in milliseconds
cookie('species', 'ferret')

// get
var name = cookie('name')
// => "tobi"

var cookies = cookie()
// => { name: "tobi", species: "ferret" }

// clear
cookie('name', null)
```

## License

  MIT

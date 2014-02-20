*This repository is a mirror of the [component](http://component.io) module [stagas/dropdown](http://github.com/stagas/dropdown). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/stagas-dropdown`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# dropdown

a minimal dropdown with UX details

## Installing

```sh
$ component-install stagas/dropdown
```

## Usage

All the events & methods of [Menu](https://github.com/stagas/menu).

## Events

- `select` when an item is selected

## Example

```js
var input = document.getElementById('input')

var dropdown = Dropdown(input)

dropdown
.add('One')
.add('Two')
.add('Three')

dropdown.on('select', function (item) {
  // do something with item
})
```

## License

MIT

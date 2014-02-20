*This repository is a mirror of the [component](http://component.io) module [yuehu/password-strength](http://github.com/yuehu/password-strength). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yuehu-password-strength`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# password-strength

Check if a password is strong enough. Available on Node and Browser.

[![Build Status](https://travis-ci.org/yuehu/password-strength.png?branch=master)](https://travis-ci.org/yuehu/password-strength)

## Installation

Install with [component(1)](http://component.io):

    $ component install yuehu/password-strength

Install with npm:

    $ npm install password-strength

## API

```js
var valid = require('password-strength');
valid(password);
// -> {valid: true, strength: 'medium', hint: null}
```

### .min

The min length of the password, default is 4.

### .words

The password can't be these words, default is [].

## License

MIT

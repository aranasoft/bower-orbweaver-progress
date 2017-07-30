# packaged orbweaver-progress

This repository is for `npm` and `bower` distribution. The source for this module is in the
[Orbweaver sourcecode](https://github.com/aranasoft/orbweaver/tree/master/src/) repository.
Please file issues and pull requests against that repository.

## Install

You can install this package either with `npm` or with `bower`.

### npm

```shell
npm install orbweaver-progress
```

Then add `orbProgress` as a dependency for your app:

```javascript
angular.module('myApp', [require('orbweaver-progress')]);
```

### bower

```shell
bower install orbweaver-progress
```

Add a `<script>` to your `index.html`:

```html
<script src="/bower_components/orbweaver-progress/orbweaver-progress.js"></script>
```

Then add `orbProgress` as a dependency for your app:

```javascript
angular.module('myApp', ['orbProgress']);
```

## License

Orbweaver is copyright of Arana Software, released under the [BSD License](http://opensource.org/licenses/BSD-3-Clause).

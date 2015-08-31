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

The BSD 3-Clause License

Copyright (c) 2013-2015, Arana Software - www.aranasoft.com
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.

3. Neither the name of Arana Software nor the names of its contributors may be
   used to endorse or promote products derived from this software without
   specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
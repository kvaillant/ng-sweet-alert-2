[![Latest Stable Version](https://img.shields.io/npm/v/ng-sweet-alert-2.svg?style=flat-square)](https://www.npmjs.com/package/ng-sweet-alert-2)
[![NPM Downloads](https://img.shields.io/npm/dm/ng-sweet-alert-2.svg?style=flat-square)](https://www.npmjs.com/package/ng-sweet-alert-2)
[![Latest Stable Version](https://img.shields.io/bower/v/ng-sweet-alert-2.svg?style=flat-square)](http://bower.io/search/?q=ng-sweet-alert-2)
[![Build Status](https://img.shields.io/github/forks/tushariscoolster/ng-sweet-alert-2.svg?style=flat-square)](https://github.com/tushariscoolster/ng-sweet-alert-2)
[![Build Status](https://img.shields.io/github/stars/tushariscoolster/ng-sweet-alert-2.svg?style=flat-square)](https://github.com/tushariscoolster/ng-sweet-alert-2)

# Thanks to
This repository was cloned from https://github.com/tushariscoolster/ng-sweet-alert/. Thanks Tushar Borole for your work!

# ng-sweet-alert-2

ng-sweet-alert-2 is an directive for sweet alert 2 [sweetalert2]. Integration of sweet alert 2 becomes very easy with angular js. There is no need to write a single line of javascript code. Only few html attribute is enough to use sweetalert2.

## Getting Started

Install via bower

```sh
bower install ng-sweet-alert-2
```

Install via npm

```sh
npm install ng-sweet-alert-2
```

Add dependency in your module

```javascript
angular.module('yourApp',[   'ng-sweet-alert-2' ]); 
```


## Configure

```html
<input sweetalert sweet-options="{title: 'Are you sure?',text: 'You will not be able to recover this imaginary file!',type: 'warning',showCancelButton: true,confirmButtonColor: '#DD6B55',confirmButtonText: 'Yes, delete it!',cancelButtonText: 'No, cancel plx!'}" sweet-success-option="{title: 'Deleted!',text: 'Your imaginary file has been deleted.',type: 'success'}" sweet-dismiss-option="{title: 'Cancelled!',text: 'Your imaginary file is safe',type: 'error'}" type="submit" name="login-submit" sweet-on-cancel="checkCancel()" sweet-on-confirm="checkConfirm()" id="login-submit" tabindex="4" class="form-control btn btn-login" value="Log In">
```

## Documentation


|                  | Option| 
 ----------------- | ---------------------------- | ------------------
| sweet-options | `'{title: 'Are you sure?',text: 'You will not be able to recover this imaginary file!',type: 'warning',showCancelButton: true,confirmButtonColor: '#DD6B55',confirmButtonText: 'Yes, delete it!',cancelButtonText: 'No, cancel plx!'}'` 
| sweet-success-option| `"{title: 'Deleted!',text: 'Your imaginary file has been deleted.',type: 'success'}"`            
| sweet-dismiss-option| `{title: 'Cancelled!',text: 'Your imaginary file is safe',type: 'error'}` 
| sweet-on-cancel| `checkCancel()` 
| sweet-on-overlay| `checkOverlay()` 
| sweet-on-close| `checkClose()` 
| sweet-on-timer| `checkTimer()` 
| sweet-on-confirm| `checkConfirm()` 


----------

## Contributing

Open an issue first to discuss potential changes/additions. If you have questions with the guide, feel free to leave them as issues in the repository. If you find a typo, create a pull request. The idea is to keep the content up to date and use github’s native feature to help tell the story with issues and PR’s, which are all searchable via google. Why? Because odds are if you have a question, someone else does too! You can learn more here at about how to contribute.

*By contributing to this repository you are agreeing to make your content available subject to the license of this repository.*

### Process
    1. Discuss the changes in a GitHub issue.
    2. Open a Pull Request, reference the issue, and explain the change and why it adds value.
    3. The Pull Request will be evaluated and either merged or declined.

## License

 Use this guide. Attributions are appreciated._

### Copyright

Copyright (c) 2016-2017 [Karl Vaillant](http://www.karlvaillant.fr)

### (The MIT License)
Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
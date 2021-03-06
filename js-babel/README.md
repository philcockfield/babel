# js-babel
Consolidated [Babel](https://babeljs.io/) dependencies for core ES transpiling.


#### IMPORTANT
**Do not reference this library** unless you are happy staying in lock-step with the babel transpiler plugins used by my [modules](https://github.com/philcockfield/modules) and other idiomatic decisions that I make.


## Install
A single dependency will bring all the standard babel presents and plugins:

    npm install --save-dev js-babel

```json
{
  "devDependencies": {
    "js-babel": "^6.0.0"
  }
}
```



## Configure
#### .babelrc
The references in this module's `package.json` allow for the following presents and plugins in your `.babelrc` file:

    {
      "presets": ["es2015", "stage-0"],
      "plugins": ["transform-class-properties"]
    }




## Tests
    npm install
    npm test


---
### License: MIT

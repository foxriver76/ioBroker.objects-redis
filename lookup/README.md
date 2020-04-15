# Info on how to use lookups

For each new version a directory is created here and the index.js and index.js.map is put into it.

Please commit these files to GitLab. They can be used when checking error messages.

## js-controller versions to objects-lib map

* objects-lib 3.3.1: js-controller 3.0.11 +


## How to lookup

Change into relevant lookup directory based on the version and execute

node node_modules/.bin/sourcemap-lookup index.js:LINE:COLUMN

and you see the relevant code line
Get Licenses
============

Get all of the licenses/license-info about the open source libraries you have installed.

```sh
npm install -g get-licenses
```

Single directory (will place the files in a licenses folder).
```sh
get_licenses node_modules
```

Multiple directories (will look for each directory and place the found files in the licenses folder).
```sh
get_licenses node_modules,app/bower_components
```

Multiple directories (will look for each directory and place the found files in your specified folder)
```sh
get_licenses node_modules,app/bower_components my_licenses
```

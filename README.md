## Description:
This is a materialize clockpicker designed as an addition to http://materializecss.com/

Most of the source code is taken from: 
https://github.com/weareoutman/clockpicker
with the Materialize adapation taken from:
https://github.com/chingyawhao/materialize-clockpicker

All thanks and rights goes to these original authors, I simply made this modification for a personal project.
I highly appreciate the effort that they put into this.

## Install:

### npm
`npm i https://github.com/battesonb/materialize-clockpicker/tarball/master --save`

## Options:
Here are some options and their defaults:
```
container: '',         // default container is within the calling component. Otherwise
default: '',           // default time, 'now' or '13:14' e.g.
fromnow: 0,            // set default time to * milliseconds from now
donetext: 'Done',      // done button text
autoclose: false,      // auto close when minute is selected
ampmclickable: false,  // set am/pm button on itself
darktheme: false,      // set to dark theme
twelvehour: true,      // change to 12 hour AM/PM clock from 24 hour
vibrate: true          // vibrate the device when dragging clock hand
```

## Screenshots:
![Image of Materialize Clock Light](https://github.com/battesonb/materialize-clockpicker/blob/master/images/material-clock-light.PNG)
![Image of Materialize Clock Dark](https://github.com/battesonb/materialize-clockpicker/blob/master/images/material-clock-dark.PNG)


## Developing:
```
npm i gulp bower -g
npm install
bower install
gulp watch
```
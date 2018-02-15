<strong><p align="center" style="font-size: 18pt;">Resources Repository</p></strong>

***

| Directory | Description | URL |
| --------- | ----------- | --- |
| <p align="center">`/images`<p>  | General Access directory for use as both a backup image host for     different web applications, as well as general image hosting for Readme files. `{SUBDIRECTORY}` is either the name of an application, or `/global` for images that are used globally.  | http://arjaycodes.com/images/{SUBDIRECTORY}
| <p align="center">`/scripts`</p> | General access directory for commonly used scripts across `www.arjaycodes.com` applications. Scripts such as the TrafficTracker drop-in can be found here. Referenced by `{SCRIPTNAME}`. | http://arjaycodes.com/scripts/{SCRIPTNAME} 
| <p align="center">`/libs`</p> | General Access to various libraries used across apps, such as `jQuery`, `Bootstrap`, `Semantic UI`, or `Foundation`. With an active effort to keep all versions up to date with the most stable release. These will also be hosted by a dedicated Heroku dyno in addition to this domain, with a REST API managing the serving of libraries that have more complex directories of multiple files. | http://arjaycodes.com/libs/{LIBRARYNAME} 
| <p align="center">`/styles`</p> | All stylesheets commonly used across applications on the arjaycodes.com domain, as well as more general use ones such as supplemental scripts that override certain defaults in the Semantic UI and Bootstrap libraries. `{SYNTAX}` can be either `css`, `scss`, or `less` depending on which is available. `{SHEETNAME}` is the name of the desired stylesheet. | http://arjaycodes.com/styles/{SYNTAX}/{SHEETNAME}

***

©️ 2018 Robert J. Jones (arjaycodes). All Rights Reserved.
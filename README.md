# (ArcGIS.js <= 100)
### Welcome to the 100 Lines or Less ArcGIS JavaScript Code Challenge!

Everybody loves a cool mapping app.  Here's your chance to write the coolest application in 100 lines or less with the [ArcGIS API for JavaScript](http://help.arcgis.com/en/webapi/javascript/arcgis/index.html) and win a one-year subscription to [ArcGIS Online](http://www.esri.com/software/arcgis/arcgisonline) and a free 2014 Esri Dev Summit pass - a $3,500 value, a free pass to the 2014 Esri Dev Summit - a $1000 value or a $100 Esri Press gift certificate.  Anyone can enter, but just to make things a little more exciting, we'll be announcing the winners at the [2013 Esri International Developer Summit](http://www.esri.com/events/devsummit/index.html).  You don't need to attend the DevSummit to win or claim your prize however.

To enter all you need to do is make a pull request to submit your code (see How to Enter below).    

Best of luck!

![App](https://raw.github.com/Esri/100-lines-or-less-js/master/100-lines-or-less.png)

## Current Entries

Be the first to submit!

## Contest Period
- Starts: 9:00 AM PST Friday, Mar 8, 2013
- Closes: 6:00 PM PST Wednesday Mar 27, 2013 (No entries will be accepted after this time.)

## How to Enter
1. Fork and then clone this repo.
2. Add a folder to the repo with your app in it (see example).
3. Make a pull request to submit your entry. This request represents your agreement to the [Terms and Conditions](http://esri.github.com/100-lines-or-less-js/Terms and Conditions Agreement.pdf).

NOTE: Be sure to Pull and Merge from this repo to get the latest before making your pull request!

## Rules

1. Max 100 (sloc) lines of client-side JavaScript code. Max 80 chars per line. Not compressed.
2. Must use the [ArcGIS API for JavaScript](http://help.arcgis.com/en/webapi/javascript/arcgis/index.html).
3. All JavaScript code must be in a single .js file (see Example below).
4. All project code must reside in a single folder (HTML, css, js).
5. Application must be fully functional, portable, deployable and accessable from any public web-enabled directory.  
6. Applications must be freely distributable via Apache 2.0 license.
7. IMPORTANT: Libraries other than the ArcGIS API for JavaScript can be used and do not count toward the 100 line limit. Libraries referenced must be published and publicly available prior to March 1, 2013.  So that means you can't write libraries to hide your ArcGIS code!  You can use previously published ArcGIS libraries however.

See all rules, terms and conditions [here](http://alaframboise.github.com/100-lines-or-less-js/Terms and Conditions Agreement.pdf).

## What can I win?
1. One year ArcGIS Online Subscription & Esri International Developer Summit Pass for 2014
2. Esri International Developer Summit Pass for 2014
3. $100 Esri Press gift certificate

Winners will be announed at the Esri Dev Summit Mar 28!

## Judging Criteria

1. Effective use of the ArcGIS API for JavaScript
2. Usability (UX)
3. Creativity
4. Coding style

## Judges
- [@AL_Laframboise](https://twitter.com/AL_Laframboise) 
- [@derekswingley](https://twitter.com/derekswingley)
- [@jerrysievert](https://twitter.com/jerrysievert)

## Example Entry

Follow the structure of [this](https://github.com/Esri/100-lines-or-less-js/tree/master/basemaptour) example.  View it live [here](http://esri.github.com/100-lines-or-less-js/basemaptour/basemaptour.html).


```
\project\
\project\css\
\project\js\ArcGIS.js
\project\images\
```

```
<!DOCTYPE html>
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=7,IE=9">   
  <meta name="viewport" content="initial-scale=1, maximum-scale=1,user-scalable=no">
  <title>Your App</title>
  <link rel="stylesheet" type="text/css" href="http://serverapi.arcgisonline.com/jsapi/arcgis/3.3/js/esri/css/esri.css">
  <script src="http://serverapi.arcgisonline.com/jsapi/arcgis/3.3compact"></script>
  <!-- Load your project JavaScript and CSS -->
  <link rel="stylesheet" type="text/css" href="css/project.css">
  <!-- ArcGIS.js contains the code for the contest entry --> 
  <script src="js/ArcGIS.js"></script>  
</head>
  <body>
    <div id="mapDiv"></div>
  </body>
</html>
```

## Resources

* [Esri International Developer Summit](http://www.esri.com/events/devsummit)
* [ArcGIS API for JavaScript Resource Center](http://help.arcgis.com/en/webapi/javascript/arcgis/index.html)
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis/)
* [@esri](http://twitter.com/esri)

## Licensing
Copyright 2012 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](https://raw.github.com/Esri/100-lines-or-less-js/master/license.txt) file.

[](Esri Tags: ArcGIS Web Mapping Contest)
[](Esri Language: JavaScript)

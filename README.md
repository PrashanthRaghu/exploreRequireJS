# Explore as I Learn guide to Require.JS - Prashanth Raghu

## Why are you here ?
Do not know anything about RequireJS but everyone's jumping on the bandwagon or heard about it at a recent hackathon ? Want to impress your manager with some awesome cool stuff ?

### What RequireJS is not ?
Wanna beautify your page or wanting to add some animation/slideshows to your html5 mobile app ? RequireJS is just not what you wished it was. While it adds no functionality to your page/app it helps organizing and maintaining it on the long run. So wanna just beautify your page, now is the time to close this browser tab.

### What is it to a layman developer like me ?
Programmed with Java before ? (I hope you did else it's kinda difficult to explain) 
One really cool feature about java is that it lets us organize our application as modules and seperates scope through packaging. So a File from java.io.File is totally independant from a File object I defined under my.prashanth.test.File as long as the developer chooses the right package to import. Can you do it with Javascript ? Yes to a limited extent but not as succicntly as we can with Java. requireJS is a javascript module loader which helps developers modularize js apps and help manage dependancies. So it is kind of a class loader + package manager from Java for our web pages. ( Got it ? No: Trust me it is. )

Welcome to the "Explore as I Learn guide to Require.JS" by Prashanth Raghu. Hope you have we have our expectations right at this stage. 

## What is RequireJS ?
### What they say ?

RequireJS is a JavaScript file and module loader. It is optimized for in-browser use, but it can be used in other JavaScript environments, like Rhino and Node. Using a modular script loader like RequireJS will improve the speed and quality of your code.

### What I understood ?
Baaaaah :P What on earth does that mean ? 

## Time to dig in.
So how do you generally import a script ?
Like this ?

```html
<script type="text/javascript" src="file.js"> </script> 
```

Two scripts ?
```html
<script type="text/javascript" src="file1.js"> </script> 
<script type="text/javascript" src="http://cdn.slowcdn.com/file2.js"> </script> 
```

What if file1 had a dependancy on a function from file2? Could we indicate to the browser to load file2 before file1 ? No. 
To fix this we would generally load file1 and late load file2 through an AJAX call. Yipeeee it works. But that's kind of eating a dosa using a fork. AJAX is not designed to understand the modularity of our application/ act as a manifest to our application dependancies.










Meteor API for the Atom Editor
=======================================

Bring Isomorphic javascript to the editor with Meteor API snippets!  


---------------------------------------
#### Installation  

Go to **Atom > Open Your Snippets**, and copy the contents of ``snippets/meteor.api.cson`` into the file.  Once we get the API completely covered, we'll publish through the Atom package system.  


---------------------------------------
#### Open Files From the Command Line

````sh
# link your atom binary so it can be run from the command line
sudo ln -s /Applications/Atom.app/Contents/MacOS/Atom /usr/local/bin/atom

# open a file
meteor create helloworld
cd helloworld
atom helloworld.js
````

---------------------------------------
#### Meteor API Coverage

[List of Covered Meteor API Syntax](https://github.com/awatson1978/meteor-api-for-atom-editor/blob/master/api.md)  


---------------------------------------
#### Recommended Packages  

If you want a complete javascript IDE experience with, we recommend the following packages to run with Meteor API Snippets. 

````sh
Atom Lint
Atom Beutify
Atom Jshint
Atom Prettify
Autocomplete
Bracket Matcher
Filetype Color
Grammar Selector
Snippets
Wrap Guide
````

---------------------------------------
#### Contributing / Next Steps

[Custom Syntax Highlighting](http://blog.gaku.net/create-a-custom-syntax-highlighting-with-atom-editor/)  
[Javascript Grammar](https://github.com/atom/language-javascript/blob/master/grammars/javascript.cson)  

Meteor API Snippets for the Atom Editor
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
#### Recommended Packages  

````sh
Atom Lint
````

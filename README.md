Meteor API Snippets for the Atom Editor
=======================================

Bring Isomorphic javascript to the editor with Meteor API snippets!  


---------------------------------------
#### Installation  

Go to **Atom > Open Your Snippets**, and copy the contents of ``snippets/meteor.api.cson`` into the file.  Once we get the API completely covered, we'll publish through the Atom package system.  

---------------------------------------
#### Contributing  

Pull requests encouraged!  If you're new to Meteor and want to help contribute, while learning the API, here's a great little project to help you get up to speed.  Simply follow the examples in ``snippets/meteor.api.cson`` and help create a snippet for each command in the following list using the documentation from [docs.meteor.com](http://docs.meteor.com/#meteortestpackages).  When you're done, uncomment the line item.  




---------------------------------------
#### Core

````js
isClient
isServer
startup
absoluteUrl
````

#### Publish and Subscribe
````js
publish
subscribe
````

#### Methods
````js
//methods
//error
//call
//apply
````

#### Connections
````js
//status
//reconnect
//disconnect
//connect
````

#### Collections
````js
//find
//findOne
//insert
update
//upsert
//remove
//allow
//deny
````

#### Session
````js
//set
//get
//equals
//default
````

#### Templates
````js
Template
events
helpers
rendered
created
//destoryed
//findAll
//$
//find
//firstNode
//lastNode
//data
//autorun
//view
//registerHelper
//instance
//currentData
//parentData
//body
````

#### Match
````js
//check
//test
````

#### Timers
````js
//setTimeout
//setInterval
//clearTimeout
//clearInterval
````

#### Tracker
````js
//autorun
//flush
//nonreactive
//active
//currentComputation
//onInvalidate
//afterFlush
//Computation
//Dependency
````


#### EJSON
````js
//parse
//stringify
//equals
//clone
//tojson
//type
````

#### HTTP
````js
//call
//get
//post
//put
//del
````

#### Email
````js
//send
````

#### Assets
````js
//getText
//getBinary
````

#### Router
````js
Router
route
UpsertRoute
//ListRoute
//RecordRoute
````

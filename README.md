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
absolute
````

#### Publish and Subscribe
````js
publish
subscribe
````

#### Methods
````js
methods
error
call
````

#### Connections
````js
status
reconnect
disconnect
onConnection
````

#### Collections
````js
Collection
find
findOne
insert
update
upsert
remove
allow
deny

````

#### Session
````js
set
get
equals
setDefault
````


#### Accounts
````js
user
userId
users
loggingIn
logout
loutOtherClients
loginWithPassword


Accounts
validateNewUser
onCreateUser
//validateLoginAttempt
onLogin
onLoginFailure
````
#### Accounts
````js
createUser
changePassword
forgotPassword
resetPassword
setPassword
verifyEmail
sendResetPassword
sendEnrollmentEmail
sendVerificationEmail
````


#### Templates
````js
Template
events
helpers
rendered
created
destoyed
registerHelper
````

#### Blaze  
````js
render  
renderWithData
remove
getData
toHTML
toHTMLWithData
isTemplate
````


#### Match
````js
check
test
````

#### Timers
````js
setTimeout
setInterval
clearTimeout
clearInterval
````

#### Tracker
````js
autorun
flush
nonreactive
active
currentComputation
onInvalidate
afterFlush
````


#### EJSON
````js
parse
stringify
clone
toJSON
fromJSON
isBinary
//equals - namespace conflict with Session.equals
//addType
````

#### HTTP
````js
call
get
post
put
del
````

#### Email
````js
Email
````

#### Assets
````js
getText
getBinary
````

#### Router
````js
Router
route
UpsertRoute
//ListRoute
//RecordRoute
````

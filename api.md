Meteor API Coverage

The following are the Meteor API that is currently covered.

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

## CompoundJS + JugglingDB + MongoDB version

 See the demo from <a href="http://dixitruth.com:3000/rests/">http://dixitruth.com:3000/rests/</a>

$ cd __HERE__

$ npm install -l

$ node server.js

This will start a server listening in 3000 for MongoDB's CRUD.

The Database name/Collection name: tests/Test

## DB Structure (Test Collection):

<pre>
name: String
  info {
   first_name: String
   last_name: String
   phone: String
   e_mail: String
  }
  count {
   contacts: Number
   prospects: Number
   closings: Number
   listings: Number
  }
  createdAt: Date
  active: Boolean
</pre>

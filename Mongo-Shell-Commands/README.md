Copied from
[Abdul Rehman](https://github.com/AbdulRehmanAtcha/Mongo-Shell-Commands)

## Mongo-Shell-Commands

<ul>
  <li>Run Mongo Shell.</li>
  <li>To see databases type show dbs</li>
  <li>To create Database simply type <b>use databaseName</b></li>
  <li>If a database is present with that name, it will shift to that, otherwise it will create a database with that name.</li>
  <li>To create a collection inside a database simply type <b>db.createCollection("Name Here")</b>.</li>
  <li>To see collections insert <b>show collections</b></li>
  <li>To insert a single document inside a collection simply write <b>db.collectionName.insertOne({Here your fields with value})</b>.</li>
  <li>To insert multiple documents inside a collection simply write <b>db.collectionName.insertMany({Here your fields with value}, {Here your fields with value})</b></li>
  <li>To read documents inside collection <b>db.collectionName.find(query, projection)</b></li>
  <li>Some other methods to read are <b>db.collectionName.find(query,projection).limit(how many values you want).skip(how many values you want to skip)</b></li>
  <li>To update a document's field there are two ways for it.</li>
  <ul>
    <li>To update a single document <b>db.updateOne({filter}, {$set: {update}}})</b></li>
    <li>To update many documents <b>db.updateMany({filter}, {$set: {update}}})</b></li>
  </ul>
</ul>

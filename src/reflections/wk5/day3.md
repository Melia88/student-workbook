Day 3

Daily Challenge https://github.com/Melia88/spring21-gregslist-server

Read Servers with Node/Express > MongoDb Relationships and answer the following questions

In simple terms what is a sub-document?
> Subdocuments in the MongoDb are documents that are nested in other documents.

When might you use a sub-document?
> When you need to nest a child Schema inside a parent Schema.

How do you add to a collection of sub-documents? What about editing them?
> Pass it into a new model and edit by using an array to get and change things. First you start by using the findone method to get the subdocument. If you are adding additional information you will use the push method to add it. Other way to edit the document is to edit the obect directly like you would a normal object
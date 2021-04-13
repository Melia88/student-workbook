Day 2

Daily Challenge

Read Servers with Node/Express > MongoDb Relationships and answer the following questions

What are the three types of relationships?
>One-To-One (1:1)
One-To-Many (1:N)
Many-To-Many (N:M)

What are the benefits of the traditional linking of relationships instead of Embedding
>Linking is used like a reference so it can help prevent reaching max document size of 16 MB and it's also much easier to return paginated comments as the application can slice and dice the comments more easily.

What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
> 
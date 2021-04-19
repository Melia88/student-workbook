Day 4

Daily Challenge Got w our groups and set up for fridays hackathon

Read Servers with Node/Express > MongoDb Relationships and answer the following questions

What is a virtual property?
>Mongoose virtuals are document properties that you can get and set but are not saved in MongoDB. These properties are computed whenever you access them. Virtual attributes are attributes that are convenient to have around but that do not get persisted to mongodb.

When might you use a virtual property?
>  If by chance you have two differnt input fields but want to use those fields to combine into one, the example given was getting a persons first name and last name then using that create a persons full name.

How do you search by a virtual properties value?
> By using getters and setters to obstain the info you want to either combine or spilt apart.
Day1

Afternoon Challenge https://github.com/Melia88/csGregslistApi


Read Foundations of C# > C# Data Types and answer the following questions

What are the three categories of data types? How are they different?
>Value type: A data type is a value type if it holds a data value within its own memory space. It means the variables of these data types directly contain values. When you pass a value-type variable from one method to another, the system creates a separate copy of a variable in another method. If value got changed in the one method, it wouldn't affect the variable in another method. These include  bool
 byte
 char
 decimal
 double
 enum
 float
 int
 long
 sbyte
 short
 struct
 uint
 ulong
 ushort


Reference type: Unlike value types, a reference type doesn't store its value directly. Instead, it stores the address where the value is being stored. In other words, a reference type contains a pointer to another memory location that holds the data. When you pass a reference type variable from one method to another, it doesn't create a new copy; instead, it passes the variable's address. So, If we change the value of a variable in a method, it will also be reflected in the calling method. These include 
String
 Arrays
 Class
 Delegate

Pointer type

What are the Value-type data types? What differences do you notice from JavaScript?
>

In your own words how do Reference types get stored in memory? How does this differ from Value types?
> Reference types are like storing an address in gps, if you change the address in the gps you will end up with a different location. With a value type its like taking a picture of a house, the house doesnt change even if you draw changes on the picture.
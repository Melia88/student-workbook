Day3

Afternoon Challenge

Read Foundations of C# > C# Enum's and answer the following questions

What is an Enum, and what are some use cases for them?
>In C#, an enum (or enumeration type) is used to assign constant names to a group of numeric integer values. It makes constant values more readable, for example, WeekDays. Monday is more readable then number 0 when referring to the day in a week.
Enum provides a concise way to assign names to a bunch of integers, so we can use simple loops through integers to move through months.
enum<enum_name>
{
  enumartion list
}

 
enum Tempurature
{
  Low,
  Medium,
  High,
};

How can you modify an Enum?
>

How have you used Enums in your afternoon lab projects this far?(if you have not yet, give an example of how you could)
> I have not yet but I think it could be used to make something more readable if I was using dates or something else that used an index of numbers.
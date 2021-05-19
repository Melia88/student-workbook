# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespaces are used to provide a "named space" in which your application resides. It is what your application as a whole is called.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value types and classes are reference types.
value types always contains a value
reference types can contain a null-reference, meaning that they don't refer to anything at all at the moment(a pointer)
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the data type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only code in the same class or struct.
```
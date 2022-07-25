# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
a namespace is a container for all the classes and interfaces in a project.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
a class is a blueprint for an object. a struct is a blueprint for a value.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
the constructor.
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
public.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
 the string name of a method
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
  the class from being instantiated.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
  to override the method in the base class.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, protected, private, internal.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
the parent class or the parent method.
```
# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
To orginize files based on relevancy.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A stuct represents data structure while a class contains methods as well.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
The instance of a class has a void return method.
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
Public.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
its the return type of the function.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It is to indicate that it is meant to only be the base of another class.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
 Virtual is meant to indicate that the method can be overridden when it is inherited.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, private, protected, internal 
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only local methods. 
```
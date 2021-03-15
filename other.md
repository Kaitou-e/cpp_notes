### Namespaces

Namespaces help prevent name conflicts in programs. They are a collections of variables, functions, and/or classes. 
#### Defining namespaces
```cpp
{...}
namespace a {
 // definitions here
}
```
In the code above, `namespace a` is defined. Functions and variables defined in this way can be used in the following format: `namespaceName::varorfunc`. ex:
```cpp
{...}
namespace a{
  int b = 9;
}

int main(){
 std::cout << a::b;
 // should output 9 to the console
}
```
Note: namespaces can be nested
#### `using`

The using method sets a default namespace; which means that when there is no namespace mentioned, it will use the default namespace. `std` is a namespace often set as the default. ex:
```cpp
{...}
namespace a{
  int b = 9;
}
int main(){
  using namespace a;
  std::cout << b;
  // should output 9
}
```
### Main
`main` is a required fuction in every c++ program. 

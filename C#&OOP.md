# Tell me about you self?
My name is Muhammad Abdullah and I'm a Software  Engineer with 6 years of experience in Creating
1. Web application
2. SaaS Solutions
3. MVPs for startups & companies

Using different technologies like
1. BackEnd  : C# + ASP.NET MVC + ASP.NET WEB API
2. FrontEnd : HTML + CSS + JavaScript + React JS
3. Database : Microsoft SQL Server  
4. Testing : Selenium+Coypu+Puppeteer +TDD+BDD
5. Source Controls : BitBucket, GIT, TFS, Source Tree
6. CI/CD : Bamboo + Azure


Apart from that 
I recently completed google project management certification from google. & Top rated freelancer at upwork with happy clients with 76% satisfaction rate.





# Managed and unmanaged code.
Managed : Code writen in C# , that need Common language runtime is called managed code. We cant execute this code directly on OS.
Unmanage : Code written in c, c++ is that execute directly on OS.


Ref VS Out
1. Ref:  The parameter or argument must be initialization first before it is passed to ref.
2. Out:  It is compulsory to initialize a parameter or argument before it is passed to an out.

# Constants Vs Read-only
1. Constant : Value type + Initalize at Compile Time
2. Read Only : Reference type + Initalize at Run Time

# Reflection 
1. The process of describing the metadata of types, methods and fields in a code. 
2. System.Reflection enables you to obtain data about the loaded assemblies, the elements within them like classes, methods and value types. 

# Why refection?
1. To get all global and non-global methods defined in the module.
2. To get method info to look at information such as parameters, name, return type, access modifiers and implementation details.
3. To get event info to find out the event-handler data type, the name, declaring type and custom attributes.
4. To get Constructor Info parameters, access modifiers, and implementation details of a constructor.
5. To get property info.


# Dynamic keyword
1. Skip type-checking at compiler time.
2. Delay type-checking until runtime.

# Reflection Vs Dynamic?
1. Both used when we want to operate on an object during runtime.
2. Reflection have no caching while dynamic have.
3. Reflection have static class while dynamic don't.
4. Reflection we can invoke private members while dynamic we can't.
5. Both we can invoke publick members.
6. Reflection have meta-data inspection while dynamic does not.

# Binding 
when an object is assigned to an object variable. They C# compiler perform a process called Binding. There are 2 types of binding.
1. Early Binding or Static Binding
2. Late Binding or Dynamic Binding

# Early binding Vs late binding
1. Early binding compiler recognizes and checks the methods, or properties during compile time. 
2. Late Binding compiler does not know about what kind of object it is and what are the methods or properties it holds, here the objects are dynamic objects.

#  VAR and Dynamic keyword?
1. var : should be initialized at the time of declaration. It cannot be used for properties or returning values from the function. It can only used as a local variable in function.
2. Dynamic : The variable of this type need not be initialized at the time of declaration. Because the compiler does not know the type of the variable at compile time.It can be used for properties or returning values from the function.

# Type safety and casting in C#?
Converting one type of data to another type is call type Casting or type safty.
1. Implicit type conversion:  conversions from smaller to larger integral types and conversions from derived classes to base classes.
2. Explicit type conversion:  These conversions are done explicitly by users using the pre-defined functions. Explicit conversions require a cast operator.

# Stack Vs Heap.
1. Stack stored value types + Last In First Out + Access is fast + Variables can’t be Resized
2. Heap stored reference types. + Any Order + Access is Slow + Variables can be Resized

# Differentiate between Boxing and Unboxing?
Boxing : Converting value type to reference type. 
Unboxing : Converting reference type to value type.

# Performance durring boxing and unboxing?
1. Boxed value type objects take up more memory.
2. Boxed value type objects require an additional read
3. Boxing and unboxing operations consume CPU & time.

# How to prevent boxing & unboxing:
1. Use ToString method of numeric data types such as int, double, float etc.
2. Use for loop to enumerate on value type arrays or lists (do not use foreach loop or LINQ queries)
3. Use for loop to enumerate on characters of string (do not use foreach loop or LINQ queries)
4. If you define your own value type then override implementation of basic object methods.
5. Don’t assign value type instance to object unless unavoidable
6. Use generic List<>, Dictionary<> (et al) instead of ArrList & HashTable.
7. Use Nullable<> value types (examples int?, float? etc)
8. When using string.Format (SrtingBuilder.AppendFormat) or similar API’s that use ‘params object[]’ pass on value type objects by calling ‘ToString()’ method.

# Convert.toString and .toString () method?
Convert" function handles NULLS, while "i.ToString()" does not it will throw a NULL reference exception error. So as good coding practice using "convert" is always safe.

# String Vs string?
"string" is just an alias of System.String

# Inheritance
Same object with different behavior . we use inheritance to increase reusibiltiy, extendibility, and modify.

# Interface Vs Abstract Class
1. Abstract Class : only allows other classes to inherit from it but cannot be instantiated. In other words its a contract that defines specific set of methods and their arguments.
2. Interface :  interfaces are used to implement multiple inheritance.

The main difference between them is that a class can implement more than one interface but can only inherit from one abstract class. 

# Delegates
A obA=new A();
Here, the object reference obA points to an object of A. Similar to this, delegates 
are reference types, but the key difference is that they point to methods. Simply put, 
a delegate is an object that knows how to invoke a method. A delegate derives from 
System.Delegate class





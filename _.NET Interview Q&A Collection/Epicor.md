# Epicor

## Asked for Devops with C# Position

### Telephonic

1.  Branching Strategies in TFS

2. Walk me through how do you setup CI/CD pipeline in VSTS(Azure Devops)

3. Where do you put articrafts and how do you deploy them.

4. What is Shelveset. Can you create build with Shelveset.

5. When you do Git init command what happens ? Does it create source code ?

6. Tell some commonly used Git commands

7. How good are you at powershell. Can you talk a bit about where and how you have used powershell in your projects.

## F2F

1. Explain main concepts of OOPS.

2. What are the different types of polymorphism ?

3. What is the use of IDisposable ? When should you use it.

4. Can you use `try` and `finally` statements without using catch.

5. Can you use only `try` without `catch` or `finally`.

6. What happens if exception is thrown in `finally` block.

7. When you throw exception you can do `throw` and `throw ex`. What is the difference

8. Let's say you have a clas and have two methods. What is the output. Does it work or will it give any error. If error
   what error does it give. Compile time or Run time?

    ```csharp

    void DoWork(double a) { }

    void DoWork(int a) { }    

    ```

9. What is `static` class ? What is its significance. When should we use static class ?

10. When does the `static` variables are initialized ? Let's say I have a static class like below. What is the output ? 

    ```csharp

    static class A {

        public static int Num = 1 + B.Num;

    }

    static class B {

        public static int Num = 1 + A.Num;
    }

    static void Main(string[] args) {

        Console.WriteLine(A.Num);
        Console.WriteLine(B.Num);
    }
    ```

11. Let's say I have classes like below. What statements hold good and what is the output.

```csharp

    class A {

        
    }

    class B: A{

    }

    A a1 = new A();
    A a2 = new B();
    B b1 = new A();
    B b2 = new B();
```
12. What are the data structures you have used. What are stack and queue and how its stored in memory ? Can you explain how stack works.

13. When do you get stack overflow exception ?

14. Write a program to print sum of all integers upto `n`. Suppose `n = 5`, then it should do `1+2+3+4+5` and print the output as `15`.

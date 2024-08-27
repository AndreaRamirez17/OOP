Ejercicios resueltos de la sección de *Object Oriented Programming* de HackerRank
1. **Java Inheritance I:**  Agregar un metodo sing a la clase Bird, luego modifica el metodo main para que el codigo imprima las siguientes lineas:
   - I am walking
   - I am flying
   - I am singing
2. **Java Inheritance II:** Escribir en el editor de codigo:
- Una clase llamada Arithmetic con un metodo llamado add que acepte integers como parametros y regrese un integer representrando la suma.
- A class named Adder that inherits from a superclass named Arithmetic.
Your classes should not be Public.
3. **Java Abstract Class:** A Java abstract class is a class that can't be instantiated. That means you cannot create new instances of an abstract class. It works as a base for subclasses. You should learn about Java Inheritance before attempting this challenge.
   You have to create another class that extends the abstract class. Then you can create an instance of the new class. 
Notice that setTitle method is abstract too and has no body. That means you must implement the body of that method in the child class.
In the editor, we have provided the abstract Book class and a Main class. In the Main class, we created an instance of a class called MyBook. Your task is to write just the MyBook class. Your class mustn't be public.
4. **Java Interface:** A Java interface can only contain method signatures and fields. The interface can be used to achieve polymorphism. In this problem, you will practice your knowledge on interfaces. You are given an interface AdvancedArithmetic which contains a method signature int divisor_sum(int n). You need to write a class called MyCalculator which implements the interface. divisorSum function just takes an integer as input and return the sum of all its divisors. For example divisors of 6 are 1, 2, 3 and 6, so divisor_sum should return 12. The value of n will be at most 1000. Read the partially completed code in the editor and complete it. You just need to write the MyCalculator class only. Your class shouldn't be public.
5. **Java Method Overriding:** When a subclass inherits from a superclass, it also inherits its methods; however, it can also override the superclass methods (as well as declare and implement new ones). Complete the code in your editor by writing an overridden getNumberOfTeamMembers method that prints the same statement as the superclass' getNumberOfTeamMembers method, except that it replaces n with 11 (the number of players on a Soccer team).
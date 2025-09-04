Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.
===
Lab #2

Part 2
1. x
2. 0 in the balance
3. the ticket machine still prints the ticket regardless of the money inserted
4. x
5. the machine prints a 10 cent ticket if i input 10
7. error; the class icon is covered in red stripes
8. class TicketMachine: code works without public access modifier
9. public TicketMachine: code doesn't work without the class
10. x
11. public TicketMachine(int cost): no return type (void, int, string, etc.) before the variable, and there are parentheses after the variable
12.
private int count: int is the return type
private Student representative: Student
private Server host: Server

13.
private boolean alive: alive is the name of the field
private Person tutor: tutor
private Game game: game

14. x
15. x
16. the ; is essential at the end of most lines, including field declarations
17. x
18. public Student(String name) belongs to the class Student
19. public Book(String title, double price) has 2 parameters, first is a string type and the second is a double type
20. i think both parameters have to be stored somewhere
21.
public Pet(String petsName)
{
private String petsName
}

22. x
23. the getBalance method uses Balance as a variable in the header and balance in the body, while the getPrice method uses Price as a variable in the header and price in the body

24. i would characterize it as "how much money has been inserted into the machine"

25. the code seems to work with getAmount as the method shows the exact money i inserted. HOWEVER, the code will break if i change the field to return amount; as "amount" doesn't exist

26. the getTotal method displays the total money the user has ever inserted into the machine

27. the error message says: "missing return statement"

28. getPrice uses the get accessor method while printTicket uses the print accessor method. get is used to retrieve the value of an objet, and print is used to display information

29. insertMoney and printTicket do not have a return statement because they do not need to retrieve the value of a prior object

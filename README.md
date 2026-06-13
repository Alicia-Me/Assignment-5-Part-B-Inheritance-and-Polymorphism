# Assignment-5-Part-B-Inheritance-and-Polymorphism

This program addresses Chapters 2, 3, and 6.

Working Hard

The world is full of hardworking individuals.  There are all types of workers, including those that are doctors, lawyers, software engineers, and sales.  Every worker has the following characteristics:

Constructor (accepts values for name and salary)
Name (type string)
Salary (type double)

For name and salary, implement the accessor and mutator functions.  In addition,
implement the following function:

double salaryPerWeek()

Make sure that the Worker class is abstract (i.e. one of the functions must be a pure virtual function – it is up to you what you want to do for that).  Keep in mind that, on average, doctors earn $294,000 per year, lawyers earn $144,230 per year, software engineers earn $108,080 per year, and salespeople earn $64,310 per year.  Assume that a year is 52 weeks long.

Once you’ve created a base class for the worker and derived classes for each of
the 4 types of workers, write a driver (test) program which shows salaries for
each of the 4 types of workers.  You must split all of the classes into their respective .h and .cpp files, even if they are small.

Each class should be defined and declared in their own .h and .cpp files that are safeguarded by preprocessor directives.

Write a function printSalary() that is not a class function, but will be a polymorphic function that takes in a base class argument.  This will go in the same file as the main function for this program.  Test your function for all derived classes.

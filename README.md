# Lab-Task-3
Pipe and Filter Pattern in Java

Working of the Code:

Initialize Input List

A list of integers from 1 to 10 is created as the initial data.

Define Filters (Processing Steps)

The program defines multiple filter functions, each performing a specific transformation:

filterEvenNumbers: Keeps only even numbers.

squareNumbers: Squares each number.

filterNumbersGreaterThanTen: Keeps numbers greater than 10.

doubleNumbers: Doubles each number.

Store Filters in a Pipeline

Filters are stored in a list of Function<List<Integer>, List<Integer>>, which represents a processing pipeline.

Process the Data Through the Pipeline

The input list is passed through each filter sequentially.

Each filter modifies the list before passing it to the next filter.

Print the Final Processed List

The final transformed list is printed.
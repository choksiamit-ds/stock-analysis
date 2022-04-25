# stock-analysis

## Overview of Project

This project analyses the stock performance and gives a visual output based on volume and percentage gain/loss.


## Results: 

Below are the results from the original script and the refactored script.
The results are the same, but there is a significant performance improvement in the refactored code output.

### Results from Original Script

![VBA_Challenge_2017_OrigScript](https://user-images.githubusercontent.com/103329721/165004427-5884a232-f75c-42cf-bc11-b59e4c0d40ed.png)

![VBA_Challenge_2018_OrigScript](https://user-images.githubusercontent.com/103329721/165005081-5646374a-084f-47be-8fe0-d58d29a0776c.png)

### Results from Refactored Script

![VBA_Challenge_2017](https://user-images.githubusercontent.com/103329721/165004810-3e048ba8-363e-41ec-bb87-e7a1b25f7b9d.png)

![VBA_Challenge_2018](https://user-images.githubusercontent.com/103329721/165005099-615130e8-b0bb-400a-81ea-474685bc45f2.png)

## Summary:

There is a significant performance improvement when using the refactored code due to algorithmic refinement. The performance gain is very significant as stated below when the nested for loop is removed. 

## Advantages or disadvantages of refactoring code?

Both the code before and after refactoring work the same and give the same output. However the refactored code has significant performance improvements.

* In Original Routine there is a nested forloop which increases the performance penalty by n^n
* In the Refactored routine a nested forloop is avoided and the code uses two forloops instead and hence the perfornace penalty is 2n.
* For a n size of 12, the first algorithm will execute 144 instructions and the second algorithm will execute 24 instructions. 
* Non refactored   1.11, 1.09 for years 2017 and 2018 respectively
* Refactored  0.15, 0.13 for years 2017 and 2018 respectively
* There is a 7x performance improvement.


## How do these pros and cons apply to refactoring the original VBA script?

### Pros
#### Clean Code
* Easily maintainable
* Less error prone
* Good coding practices
* Default initializations done for ticker volume

#### Significant Performance Improvement
* 7x performance improvement

### Cons
* More code in refactored code


Finally both the routines are well commented. These instructions are not of any meaning to the computer but it is very easy to convey the intent of the developer in case a different developer needs to maintain the code after the author has left the project or company. This is a real world scenario and a discipline in coding can go a long way in producing clean code with no hidden bugs and easy maintainability. 

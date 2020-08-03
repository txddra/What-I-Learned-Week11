# What-I-Learned-Week11


### Overview
   
We covered quite a bit in this week, a lot,
 honestly a little *too* much if you ask me, but 2 of the concepts I wanted to hone in on, to include:

## Keyword ['this'](https://www.w3schools.com/js/js_object_methods.asp) *
What is this?

The JavaScript this keyword refers to the object it belongs to.

It has different values depending on where it is used:

- **In a method**, this refers to the owner object.

- **Alone**, this refers to the global object.
  
- **In a function**, this refers to the global object.



## [__dirname](https://www.geeksforgeeks.org/difference-between-__dirname-and-in-node-js/) *

we'll be going over the differences between `__dirname` & `./`



|`__dirname`       |`./`     | 
| :------------- | :----------: | 
| - returns the path of the folder where the current JavaScript file resides | - gives the current working directory   |
|  - used to get the filename and directory name of the currently executing fil   | -only case when `./` gives the path of the currently executing file is when it is used with the require() |

  I've included links for some pages for some added clarity to reference. *
Find the tests with different results 
===================  
In order to find tests with different results, using vimdiff my-markdown-parser/results.txt cse15lsp22-markdown-parser/results.txt command  
By knowing how different the results are, we can have the ideas improving it.  
![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/diffresult.png)  
  
Test with different result 1  
===================  
[test-file 481](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/test-file%20481)  

my output: ![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/test481%20my%20actual.png)  

provided output: ![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/test481%20provided%20actual.png)  

We found that My inplementation's result /uri "title" is right, and the result, [], of provided implementation is wrong.  
By comparing the results implementation, I guess the problem exists in finding the location of links. 
Thus, We need add some IF loops to check the condition for locate the right place. 
In this case, by observing the testfile, We found that the code cant recognice the 1st letter "<" 
This maybe the bug making ouput empty 
Thus, the place we need to change:  
![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/fix1-1-1-1.png)  
  
Test with different result 2  
===================  
[test-file 487](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/test-file%20487)  

my output: ![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/test487%20my%20actual.png)  

provided output: ![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/test487%20provided%20actual.png)  

In this case, Provided implementation is right bc there is no valid link in testfile  
By comparing the results implementation, I guess the problem exists in the condition for checking.  
For example the condition for "("
or the condition for "/"
These may be the distractor for gettting correct links
Thus, the place we need to change:  
![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/fix2.png)   

  




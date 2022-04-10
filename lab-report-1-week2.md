![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/lab%201.png)

In this step, all you need to do is to install VScode and open it.

![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/remote%20connecting.png)

In this step, you need to use ssh username@hostname and password to log in.

![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/running%20command.png)

In this step, try some command such as ls, cd, and cat.

![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/moving%20with%20cp.png)

![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/moving%20with%20scp.png)

In this step, create a file in your computer. WhereAmI.java, and use scp command to  move file. scp WhereAmI.java cs15lsp22zz@ieng6.ucsd.edu:~/ 

![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/ssp%20keys.png)

In this step, call ssh-keygen and steps will shown above.

for optimizing remote running, make a local edit on  WhereAmI.java,then copy it to remote server. try $ cp WhereAmI.java OtherMain.java; javac OtherMain.java;
java WhereAmI

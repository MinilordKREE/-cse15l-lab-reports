Installing VScode
===================

![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/lab%201.png)

In this step, all you need to do is to install VScode and open it.

Remotely Connecting
===================

![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/remote%20connecting.png)

In this step, you need to use ssh username@hostname and password to log in.  

[link](https://docs.google.com/document/d/1fSx-8s0cI6G9k8hgGCZSRa-dhT2r7Wi4qDDpcGsex08/edit#heading=h.s8u88f6kqofr)  

`ssh csels22au@ieng.ucsd.edu`

Trying Some Commands
====================

![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/running%20command.png)  

[link](https://docs.google.com/document/d/1fSx-8s0cI6G9k8hgGCZSRa-dhT2r7Wi4qDDpcGsex08/edit#heading=h.s8u88f6kqofr)


In this step, try some command such as ls, cd, and cat.

Moving Files with scp
=====================

![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/moving%20with%20cp.png)

![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/moving%20with%20scp.png)  

[link](https://docs.google.com/document/d/1fSx-8s0cI6G9k8hgGCZSRa-dhT2r7Wi4qDDpcGsex08/edit#heading=h.s8u88f6kqofr)  

---

`scp WhereAmI.java csels22au@ieng.ucsd.edu`

Setting an SSH Key
=================

In this step, create a file in your computer. WhereAmI.java, and use scp command to  move file. scp WhereAmI.java cs15lsp22zz@ieng6.ucsd.edu:~/ 

![Image](https://github.com/MinilordKREE/-cse15l-lab-reports/blob/main/ssp%20keys.png)  

[link](https://docs.google.com/document/d/1fSx-8s0cI6G9k8hgGCZSRa-dhT2r7Wi4qDDpcGsex08/edit#heading=h.s8u88f6kqofr)

In this step, call ssh-keygen and steps will shown above.

Optimizing Remote Running
=========================

for optimizing remote running, make a local edit on  WhereAmI.java,then copy it to remote server. try $ cp WhereAmI.java OtherMain.java; javac OtherMain.java;
java WhereAmI

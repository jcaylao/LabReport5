# **Lab Report 5 - Lab Report 3 in a Different Way!**

## **The `less` command**

### **`less -N`**

The `-N` option of less is used to number the lines and display them at the beginning of each line. This option is useful because the numbered lines makes it easier to identify the specific location of a certain thing that a user may be looking for.  

Example 1:

This example shows how the usage of the `-N` option is useful for files with lots of lines and words because without it, the words and lines begin to look look the same and difficult to differentiate. The lines being numbered allows the user to easily identify where a specific word or phrase is located in a file.

Before: input `less California-History.txt`

![Image](https://github.com/jcaylao/LabReport5/blob/main/2.JPG?raw=true)

After: input `less -N California-History.txt`

![Image](https://github.com/jcaylao/LabReport5/blob/main/1.JPG?raw=true)

Example 2:

This example shows that the `-N` option is useful when used on a directory with a large amount of files. As you can see, scrolling through this may make it difficult for the user to identify the file they are looking for. The lines being numbered makes it easier to identify the files especially when scrolling up and down the list.

Before: input `less berlitz2`

![Image](https://github.com/jcaylao/LabReport5/blob/main/4.JPG?raw=true)

After: input `less -N berlitz2`

![Image](https://github.com/jcaylao/LabReport5/blob/main/3.JPG?raw=true)

### **`less -X`**

The `-X` option allows the output of the command to be left on the terminal. This is useful because normally when exiting from a file using less, the output from the command disappears. So instead of having to re-enter the command, the `-X` option allows the user to keep the output on the terminal and saves time. Example 1 shows the command being used on a .txt file and example 2 shows the command being used on a directory.

Example 1:

![Image](https://github.com/jcaylao/LabReport5/blob/main/6.JPG?raw=true)

Example 2: 

![Image](https://github.com/jcaylao/LabReport5/blob/main/5.JPG?raw=true)

### **`less -I`**

The `-I` option is used to ignore the cases in a search, meaning uppercases and lowercases. This is useful because it allows the computer to identify matches without taking in to account whether the cases match up or not, reducing the errors of the user. Example 1 shows the command being used with an all uppercase input. Example 2 shows the command being used with an all lowercase input.

Example 1: California-History.txt file

Input: `CALIFORNIA`

Before inputting `-I`

![Image](https://github.com/jcaylao/LabReport5/blob/main/not.JPG?raw=true)

After inputting `-I`

![Image](https://github.com/jcaylao/LabReport5/blob/main/eye.JPG?raw=true)

![Image](https://github.com/jcaylao/LabReport5/blob/main/CALI.JPG?raw=true)

Example 2: China-History.txt file

Input: `chinese`

Before inputting `-I`

![Image](https://github.com/jcaylao/LabReport5/blob/main/notfount.JPG?raw=true)

After inputting `-I`

![Image](https://github.com/jcaylao/LabReport5/blob/main/eye.JPG?raw=true)

![Image](https://github.com/jcaylao/LabReport5/blob/main/chinese.JPG?raw=true)



## **Sources**
https://phoenixnap.com/kb/less-command-in-linux
https://www.geeksforgeeks.org/less-command-linux-examples/
https://linuxhint.com/linux-less-command/

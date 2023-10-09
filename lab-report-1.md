The working directory while running these commands was /home. 

cd
![Image](cdexamples.png)

- when running cd with no arguments nothing happened
- when running cd with a directory, in this case 'lab1', the directory was changed to lab1
- when running cd within the new directory with a file 'lab.txt', the error 'bash: cd: lab.txt: Not a directory' was outputed. I would assume this is because cd is used to change directories and giving it a file name would cause an error since it is looking for a directory, not a file.

ls
![Image](lsexamples.png)

- when running ls with no arguments the folders within the current directory were outputed, in this case 'lab1' and 'lecture1'
- when running ls with the directory 'lab1' the contexts of that folder were outputed: 'lab.txt' and 'test'
- when running ls with the file 'lab.txt' it says that ls cant access that file since theres no such file 


cat
![Image](catexamples.png)

- when running cat by itself nothing happens
- when running cat with a directory 'lecture1' it outputs 'cat: lecture1: Is a directory'. cat is supposed to print the contents of the file so when it recieves a directory theres isnt anything to print
- when running cat with a file 'lab.txt' it says that there is 'No such file or directory'. this error is because there was no filepath

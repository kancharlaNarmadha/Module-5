
# EX 5A Data Hiding and Encapsulation
## DATE:
## AIM:
To apply encapsulation concepts that has only one field with its setter and getter methods.Display the name of the person use java code.














## Algorithm

1.Create a class Student with a private variable name.

2.Define a getName() method to return the value of name.

3.Define a setName(String name) method to set the value of name.

4.In the main() method, create an object of Student and read user input using a Scanner.

5.Set the name using setName() and display it using getName().







## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.*;
class Student{  

private String name;  
 
public String getName(){  
return name;  
}  

public void setName(String name){  
this.name=name;
}  
}  
public class Test{  
public static void main(String[] args){  
Scanner sc=new Scanner(System.in);
Student s=new Student();  

s.setName(sc.nextLine());  

System.out.println(s.getName());  
}  
}  


    
```

## Output:
![image](https://github.com/user-attachments/assets/2465dadd-0b7d-43ad-aa8e-1ee59f9d606c)


## Result:
The program successfully demonstrates encapsulation by using private data members with public getter and setter methods to access and modify the value of name.


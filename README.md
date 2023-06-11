## Ex-07:
## INSERT THE ARRAY INTO THE ELEMENT
### AIM:
To write the java program to insert an element into array

### ALGORITHM:
1. Create the class and declare the main method so that the JVM will identify the main program to run.
2. Declare an array and accept the input from user.
3. To accept the inputs from user import Scanner and get the input and store them.
4. Inside for loop use SCANEER to accept the elements of array
5. Print the output using for loop and SYSTEM.OUT.PRINT
6. The program will be executed after the compilation and results are printed.

### PROGRAM:
```java
import java.util.Scanner;
public class Ex7 {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int n= sc.nextInt();
        int[] arr =new int[n];
        for(int i=0;i<n;i++){
            arr[i]=sc.nextInt();
        }
        System.out.print("Array elements are: ");
        for(int i=0;i<n;i++){
            System.out.print(arr[i]+" ");
        }
    }
}
```

### OUTPUT:
<img width="193" alt="7" src="https://github.com/KeerthikaNagarajan/Java-Ex-7/assets/93427089/1df6ff1d-d890-4e6a-b94c-f1769b126958">

### RESULT:
Thus The Program is complie successfully.


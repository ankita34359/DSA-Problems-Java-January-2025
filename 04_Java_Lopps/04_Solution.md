# Task

![Screenshot](i1.png)

# Solution 

```java

import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.regex.*;



public class Solution {
    public static void main(String[] args) throws IOException {
        BufferedReader bufferedReader = new BufferedReader(new InputStreamReader(System.in));

        int N = Integer.parseInt(bufferedReader.readLine().trim());

        bufferedReader.close();
        
        if(N>=2 && N<=20){
        for(int i=1; i<=10; i++){
            int result = N*i;
            System.out.println(N + " x " + i + " = " + result);
        }
        }
    }
}


```

# Output Screenshot

![Screenshot](i2.png)

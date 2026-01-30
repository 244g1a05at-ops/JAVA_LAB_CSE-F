# Additional exp
## TITLE: 1.substring
```
import java.util.Scanner;
public class InsertSubstring {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the main string: ");
        String mainString = sc.nextLine();
        System.out.print("Enter the substring to insert: ");
        String subString = sc.nextLine();
        System.out.print("Enter the position to insert the substring: ");
        int position = sc.nextInt();
        if (position < 0 || position > mainString.length()) {
            System.out.println("Invalid position!");
        } else {
            String firstPart = mainString.substring(0, position);
            String secondPart = mainString.substring(position);
            String resultString = firstPart + subString + secondPart;
            System.out.println("Resulting string: " + resultString);
        }

        sc.close();
    }
}
```

# OUTPUT
![substr](https://github.com/user-attachments/assets/115efb8c-47bf-4b5c-9bec-b319b55f9b5d)


## TITLE: 3.palindrome
```
import java.util.Scanner;
public class PalindromeCheck {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a string: ");
        String str = sc.nextLine();
        int start = 0;
        int end = str.length() - 1;
         boolean isPalindrome = true;
        while (start < end) {
            if (str.charAt(start) != str.charAt(end)) {
                isPalindrome = false;
                break;
            }
            start++;
            end--;
        }
        if (isPalindrome) {
            System.out.println("String is a palindrome");
        } else {
            System.out.println("String is not a palindrome");
        }

        sc.close();
    }
}
```

# OUTPUT 
![palindrome](https://github.com/user-attachments/assets/d5bc37da-8f83-401a-a11c-6b56b7040b1e)


## TITLE: 4.perfectnum
```
import java.util.Scanner;
public class PerfectNumber {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a positive integer: ");
        int num = sc.nextInt();
         int sum = 0;
         for (int i = 1; i <= num - 1; i++) {
            if (num % i == 0) {
                sum = sum + i;
            }
        }
        if (sum == num) {
            System.out.println(num + " is a perfect number");
        } else {
            System.out.println(num + " is not a perfect number");
        }

        sc.close();
    }
}
```

# OUTPUT 
![perfectnum](https://github.com/user-attachments/assets/87ffb4c8-faae-455b-b3cc-99b688a02262)



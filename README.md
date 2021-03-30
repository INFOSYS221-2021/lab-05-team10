# Lab-05

Update this README to include your team name and team members. Don't forget to record all your answers to lab 05 in this repository.
Lab-05-Team-10

1. Olivia Daw
2. Benyamin Shahmohammadi
3. Yun-Ting Lin
4. Michael Shirley

## Exercise 01
public class ExerciseOne {
    public static void main(String args[]) {
      ExerciseOne ex01 = new ExerciseOne();

      System.out.println(ex01.reverseString("hello world"));
      System.out.println(ex01.reverseString("Dad"));
      System.out.println(ex01.reverseString("Bsuiness School"));
      
      // Uncomment the following statements after finishing Exercise Four
    //   System.out.println(ex01.isStringPalindrome("hello world"));
    //   System.out.println(ex01.isStringPalindrome("Dad"));
    //   System.out.println(ex01.isStringPalindrome("radar"));
    }
    
    // Exercise One
    private String reverseString(String word) {
        // Complete this method to return the reveresed order of the given word
        String revWord = "";
    for (int i = word.length()-1; i >= 0; i--) {
        revWord = revWord + word.charAt(i);
    }
    return revWord;
  }
    
    
    // Exercise Four
    private boolean isStringPalindrome(String word) {
        // Complete this method to deermine if the given word is a palindrome
        return false;
    }
}

 ##Exercise 02
 
 Program to display the Fibonacci sequence up to n-th term

nterms = int(input("Which Position? "))

 first two terms
n1, n2 = 0, 1
count = 0

 check if the number of terms is valid
if nterms <= 0:
   print("Please enter a positive integer")
elif nterms == 1:
   print("Fibonacci sequence upto",nterms,":")
   print(n1)
else:
   print("Fibonacci number:")
   while count < nterms:
       nth = n1 + n2
       # update values
       n1 = n2
       n2 = nth
       count += 1
print(n1)

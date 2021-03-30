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

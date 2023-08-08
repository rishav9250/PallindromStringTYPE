# PallindromStringTYPE
here is a code of PalindromNumber in(STRING) java.

public class StringPalindrom {
    public static boolean Palindrom(String str){
        for(int i=0;i<str.length()/2;i++){
            int n =str.length();
            if(str.charAt(i)!=str.charAt(n-1-i)){
              
 System.out.println("not palindrom");
   return false;
            }
        }
        System.out.println("palindom no.");
    return true;
    }
public static void main(String[] args) {
    String str ="racecar";
    System.out.println(Palindrom(str));
}
}


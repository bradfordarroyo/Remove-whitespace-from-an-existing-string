# Remove-whitespace-from-an-existing-string
Remove whitespace from an existing string
public class Main {
   public static void main(String[] args) {
     //declare and initialize a string with certain content
     String sentence = "F re et u t s.n et";
     System.out.println("\n\nInitial string: " + sentence);
     //use replaceAll() method to remove spaces
     sentence = sentence.replaceAll(" ", "");
     System.out.println("String after removing spaces: " + sentence);
 
     System.out.println("\n----------------------------------");
     System.out.println("This program is posted at Freetuts.net");
   }
}

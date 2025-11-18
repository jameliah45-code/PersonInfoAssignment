Step 1: Pseudocode: Print a fictional person’s information

BEGIN
    // Declare and assign variables
    SET firstName = "James"
    SET lastName = "Smith"
    SET streetAddress = "123 Maple Avenue"
    SET city = "Springfield"
    SET zipCode = "54321"

    // Print each piece of information on its own line
    PRINT firstName
    PRINT lastName
    PRINT streetAddress
    PRINT city
    PRINT zipCode
END

Step 2: Java Source Code

public class PersonInfo {
    public static void main(String[] args) {
        // Declare and initialize variables
        String firstName = "James";
        String lastName = "Smith";
        String streetAddress = "123 Maple Avenue";
        String city = "Springfield";
        String zipCode = "54321";

        // Print each variable on its own line
        System.out.println(firstName);
        System.out.println(lastName);
        System.out.println(streetAddress);
        System.out.println(city);
        System.out.println(zipCode);
    }
}

Step 3: How to Compile and Run
- Save the file as PersonInfo.java
-Complie it:
javac PersonInfo.java
→ This will create a PersonInfo.class file.
-Run it: java PersonInfo
Expected Output: 
James
Smith
123 Maple Avenue
Springfield
54321

# Birthday-Look-Up

import java.util.HashMap;
import java.util.Scanner;

public class Birthday {
    public static void main(String[] args) {
        HashMap<String, String> birthdays = new HashMap<>();
        birthdays.put("Koua", "06/15/1992");
        birthdays.put("Santa", "03/15/1954");
        birthdays.put("John", "09/21/1989");
        birthdays.put("Jesus", "12/25/1965");
        birthdays.put("Charlotte", "02/01/2019");
        birthdays.put("Abdul", "05/24/1991");


        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter your name: ");
        String name = scanner.nextLine();
        if(birthdays.get(name) != null)
            System.out.println(name + " your birth date is: " + birthdays.get(name));
        else
            System.out.println("Birth date not found");
    }
}

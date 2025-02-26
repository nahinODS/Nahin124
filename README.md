
public class Main {
    public static void main(String[] args) {
        // Defining personal information variables
        String name = "MD Abdulah AL Nahin";
        String studentId = "E243015";
        int age = 19;
        String email = "Nahin23@gmail.com";
        String phone = "+8801894178202";
        String address = "Mirsarai, Chattogram";

        // Using println to display the information
        System.out.println("Personal Information:");
        System.out.println("Name: " + name);
        System.out.println("Student ID: " + studentId);
        System.out.println("Age: " + age);
        System.out.println("Email: " + email);
        System.out.println("Phone: " + phone);
        System.out.println("Address: " + address);

        // Using printf just once after all println statements
        System.out.printf("\nFormatted Information:\nName: %s\nStudent ID: %s\nAge: %d\nEmail: %s\nPhone: %s\nAddress: %s\n", name, studentId, age, email, phone, address);
    }
}

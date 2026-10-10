# Studentgradeinformation-
This code utilize student Information And Grade 
       
       
       public class GradeAcceptance {
        public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter your Name: ");
        String name = scanner.nextLine();
        
        System.out.print("Your Age: ");
        int age = scanner.nextInt();
        
        System.out.print("Science Grade: ");
        double science = scanner.nextDouble();
        
        System.out.print("Math Grade: ");
        double math = scanner.nextDouble();
        
        System.out.print("English Grade: ");
        double english = scanner.nextDouble();
        
        double average = (science + math + english) / 3.0;
        
        String remark;
        if (average >= 75) {
            remark = "Passed";
        } else {
            remark = "Failed";
        }
        
        // Printed results inside the main method
        System.out.println("\n============Information==========");
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Your average: " + average);
        System.out.println("Remark: " + remark); // Added this to display the result
        
        scanner.close(); // Good practice to close the scanner
         }
     }

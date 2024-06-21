import java.util.*;

public class StudentGradeCalculator {

    public static String calculateGrade(double percentage) {
        if (percentage >= 90) {
            return "A+";
        } else if (percentage >= 80) {
            return "A";
        } else if (percentage >= 70) {
            return "B+";
        } else if (percentage >= 60) {
            return "B";
        } else if (percentage >= 50) {
            return "C";
        } else if (percentage >= 40) {
            return "D";
        } else {
            return "F";
        }
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        // Input: Take marks obtained in each subject
        System.out.print("Enter the number of subjects: ");
        int subjects = sc.nextInt();
        double[] marks = new double[subjects];
        
        for (int i = 0; i < subjects; i++) {
            System.out.print("Enter marks obtained in subject " + (i + 1) + ": ");
            marks[i] = sc.nextDouble();
        }
        
        // Calculate Total Marks
        double totalMarks = 0;
        for (double mark : marks) {
            totalMarks += mark;
        }
        
        // Calculate Average Percentage
        double averagePercentage = totalMarks / subjects;
        
        // Grade Calculation
        String grade = calculateGrade(averagePercentage);
        
        // Display Results
        System.out.println("Total Marks: " + totalMarks);
        System.out.println("Average Percentage: " + String.format("%.2f", averagePercentage) + "%");
        System.out.println("Grade: " + grade);
        
        scanner.close();
    }
}

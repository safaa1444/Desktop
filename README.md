/*
*Assignment 1
*Student.java
 * Safaa Shnewer
 * W0501121
 */




public class Student {
    public String name;
    public double assignment1;
    public double assignment2;


    public Student(String name, double assignment1, double assignment2) {
        this.name = name;
        this.assignment1 = assignment1;
        this.assignment2 = assignment2;
    }


    public double getTotal() {
        return assignment1 + assignment2;
    }


    public void outputStudentDetails() {
        System.out.println(
            name + ":\t\tAssignment1 – " + assignment1 +
            "\t\tAssignment2 – " + assignment2 +
            "\t\tTotal – " + getTotal()
        );
    }
}


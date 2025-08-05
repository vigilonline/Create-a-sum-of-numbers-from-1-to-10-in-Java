public class Sum1to10 {
    public static void main(String[] args) {
        int t = 0;

        for (int i = 1; i <= 10; i++) {
            t = t + i; // Add current number to the total
            System.out.println("Adding " + i + ", current sum: " + t);
        }

        System.out.println("TOTAL is: " + t);
    }
}

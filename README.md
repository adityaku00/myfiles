public class Pattern0599 {
    public static void main(String[] args) {
        int rows = 10; // Total number of rows
        for (int i = 0; i < rows; i++) {
            // Print leading spaces for alignment
            for (int space = 0; space < i; space++) {
                System.out.print("     "); // 5 spaces to match "0599" length
            }
            // Print "0599" (rows - i) times
            for (int j = i; j < rows; j++) {
                System.out.print("0599 ");
            }
            System.out.println();
        }
    }
}

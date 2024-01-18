# Array-Bidimensional-para-probar-SSH
Array Bidimensional en Java prueba para hacer clave SSH

public class TwoDArrayExample {
    public static void main(String[] args) {
        // Declare and initialize a 2D array
        int[][] twoDArray = new int[3][4]; // 3 rows, 4 columns

        // Populate the array with values
        for (int i = 0; i < 3; i++) {
            for (int j = 0; j < 4; j++) {
                twoDArray[i][j] = i * 4 + j + 1;
            }
        }

        // Display the contents of the 2D array
        System.out.println("Contents of the 2D array:");
        for (int i = 0; i < 3; i++) {
            for (int j = 0; j < 4; j++) {
                System.out.print(twoDArray[i][j] + " ");
            }
            System.out.println(); // Move to the next line after each row
        }
    }
}

// PrintRectangle.java

import java.util.Scanner;

public class PrintRectangle {
    public void draw() {
    Scanner scanner = new Scanner(System.in);

    System.out.print("Enter height: ");
    int height = scanner.nextInt();

    System.out.print("Enter width: ");
    int width = scanner.nextInt();

    System.out.print("Enter character: ");
    char printCharacter = scanner.next().charAt(0);

    for (int i = 0; i < height; i++) {
    drawLine(width, printCharacter);
    }
    }

    public void drawLine(int width, char printCharacter) {
    System.out.println("in drawLine, width = " + width + " character = " + printCharacter);
    }
}

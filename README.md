# test
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Hur many times did Samuel say it?");
        float fWord = scanner.nextFloat();
        System.out.println("Hur many movies did he play?");
        float movies = scanner.nextFloat();
        float snitt = fWord / movies;
        System.out.println("Samuel L Jackson säger i snitt MF-ordet " + snitt + " gånger per film");
    }
}

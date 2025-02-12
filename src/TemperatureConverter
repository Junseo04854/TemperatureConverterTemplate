import java.util.Scanner;

public class TemperatureConverter{
    public double toCelsius(double fahrenheit){
        return (fahrenheit - 32) * 5/9;
        

    }
    public double toFahrenheit (double celsius){
        return (celsius * 9/5) + 32;

    }
    public static void main(String[] args) {
        Scanner scnr = new Scanner(System.in);
        TemperatureConverter tc = new TemperatureConverter();
        double fahrenheit;
    
        System.out.println("Enter a Temperature in Fahrenheit:");
        fahrenheit = scnr.nextDouble();
    
        double celsius = tc.toCelsius(fahrenheit);
    
        System.out.printf("%.1fF is equal to %.1fC%n", fahrenheit, celsius);
    }
        }
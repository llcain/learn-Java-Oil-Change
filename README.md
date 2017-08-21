# learn-Java-Oil-Change

import java.util.Scanner;
public class App {

    public static void main(String args[]) {

	//intialize variables

        float odometerNumber;
        float totalMiles = 10000;
        float milesDay = 80;
        float result;

        Scanner Keyboard = new Scanner(System.in);

        //enter current odometer number

        System.out.println("Enter current odometer number");
        odometerNumber = Keyboard.nextFloat();


        //calculate the result of total miles driven

        result = odometerNumber + totalMiles;

        //Display calculation to screen

        System.out.println("Your next oil change is at " + result);



            }
        }

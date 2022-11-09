/**
* Name: Richard C. Cupal
* Section: IT Dept
* Year: 2nd Year
*/
```
package submissions;

/**
 * Name: Abalayan, Elmer P.
 * Section: Altruism 
 * Year: 4th 
 * 
 * 
 * */

import java.util.Scanner;

public class Main{

    public static void main(String[] args) {

        Scanner scan = new Scanner(System.in);
        int grades = 0, total = 0, choice, a = 0;

        do{
            System.out.print("Do you want to enter grade?[Y - Yes/ N - No]: ");
            choice = scan.nextInt();

                if (choice == Y){
                System.out.print("Please Enter your grade: ");
                grades = scan.nextInt();
                total += grades;
                a++;
            }

        }
	while(choice == Y);

        total = total / i;
        System.out.println("Your total average: " + total);

    }

}

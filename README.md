# PP-2.6

/* 

10/2/2022

 Derek Durand 
 
Converts F to C

*/ 

import java.util.Scanner;


public class PP26 {

    
    public static void main(String[] args) {
        
            Scanner sc = new Scanner(System.in);   // requests mile amount
            System.out.print("Enter Mile Amount: ");     
            
            float mileNumber = sc.nextFloat();
            float kiloNumber = (float) ((float) (mileNumber)*(1.60935)) ; // Converts mile amount to KM
            System.out.println("The Kilometer value is " + kiloNumber );
            
       
    }
    
}
